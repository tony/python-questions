Personal repo for examples on sites like StackOverflow, GitHub or GitLab issues

- carefully prepared questions:

  - draft and refine before asking
  - well-researched: reference other attempts / specs / ahead
  - succinct, well-articulated: clean up wording. Differentiate from other, unrelated

- minimal recreation
  - with tests
- reuse: not create a diff different repo each time

# Start

## Create virtual environment

Use [virtualenv] as a sandbox so this doesn't bork your own packages. Have a very recent python
version.

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
