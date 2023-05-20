# python-lsp-blue

Fork of [python-lsp-black](https://github.com/python-lsp/python-lsp-black) that supports [blue](https://blue.readthedocs.io/en/latest/).

## Install

In the same `virtualenv` as `python-lsp-server`:

```shell
pip install git+https://github.com/MatthewScholefield/python-lsp-blue
pip install blue
```

Now, configure `blue` as the import name in a new (or an existing) `pyproject.toml` file:
```toml
[tool.black]
import-name = "blue"
```

# More Info

See [the original repo](https://github.com/python-lsp/python-lsp-black) for more information.
