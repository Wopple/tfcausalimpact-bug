To witness bug (ctrl-c will fail to exit the program):

```shell
$ poetry update
$ poetry run python3 main.py
```

Downgrading pyarrow (e.g. to `15.0.2`) will work around the bug.
