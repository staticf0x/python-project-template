# python-project-template

This project serves as a basic [Poetry](https://github.com/python-poetry/poetry)
based Python 3.11 project.

Included:

- [tox](https://github.com/tox-dev/tox) configuration
    + [pytest](https://github.com/pytest-dev/pytest) with [pytest-cov](https://github.com/pytest-dev/pytest-cov)
    + [mypy](https://github.com/python/mypy)
    + [ruff](https://github.com/astral-sh/ruff)
    + [isort](https://github.com/PyCQA/isort)
    + [black](https://github.com/psf/black)
    + Using [tox-poetry](https://github.com/tkukushkin/tox-poetry) to install dependencies
      via Poetry
- Linter configuration
    + Line length set to 100 characters
    + flake8 config just to be sure (setup.cfg)
    + isort profile set to "black"
- Sample `app/` folder with `tests/`
- [EditorConfig](https://editorconfig.org/)
- [Coverage config](https://coverage.readthedocs.io/en/6.5.0/config.html)
- `.gitignore` for common Python related clutter

## How to start working on a project

- Install Poetry: `pip3 install --user poetry`
- Jump in the project folder
- Enter Poetry shell: `poetry shell`
- Install dependencies: `poetry install`
- Run tox: `tox` (or `tox -p` for parallel)

## TODO

- [ ] Ruff config in pyproject.toml
