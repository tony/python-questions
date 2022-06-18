This is a personal repo for examples on sites like StackOverflow, GitHub or GitLab issues, where I'd
like to have working recreation without creating a diff different repo each time.

# Start

## Create virtual environment

Use [virtualenv] as a sandbox so this doesn't bork your own packages.

```console
$ python3.10 -m venv .venv
```

If not, use the latest version of python you have:

```console
$ python3.9 -m venv .venv
```

Last resort, but hopefully you have a new system with a newer python 3.

```console
$ python3 -m venv .venv
```

If the above doesn't work, see [Install packages using pip and virtual environments]. If later on,
that link doesn't work, _search that phrase_.

[virtualenv]: https://packaging.python.org/en/latest/key_projects/#virtualenv
[install packages using pip and virtual environments]:
  https://packaging.python.org/en/latest/guides/installing-using-pip-and-virtual-environments/

## Enter virtual environment

bash / ???:

```console
$ source .venv/bin/activate
```

zsh:

```console
$ . .venv/bin/activate
```

## Install dependencies

```console
pip install -e .
```
