# Python Project template (using `uv`)

## Instructions

1. Install uv (macOS):

```sh
brew install uv
```

2. Install Python dependencies:

```sh
uv sync
```

3. Install and update pre-commit hooks:

```sh
pre-commit install && pre-commit update
```

4. Activate python env:

```sh
uv shell
```

## Using Ruff

Ruff is used for linting and formatting Python code in this project.

- To check your code for lint errors:
  ```sh
  ruff check .
  ```
- To automatically fix lint issues:
  ```sh
  ruff check . --fix
  ```
- To format your code:
  ```sh
  ruff format .
  ```

Refer to the [Ruff documentation](https://docs.astral.sh/ruff/) for more options and details.
