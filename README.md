# Computational Content Analysis (MACS 60000 1)
This repository is used for homework submissions and class work for the Computational Content Analysis at UChicago.

### Project Requirements
- Python version: `^3.11`
- [Poetry](https://python-poetry.org/)
  - If NEED be this can be run using the `requirements.txt` file included in the repository.

### Technical Notes
- Any modules should be added via the `poetry add [module]` command.
  - Example: `poetry add black`

## Standard Commands
- `make`: Serially runs the `create-requirements` and `lint` functions.
- `make lint`: Runs `pre-commit`.
- `make create-requirements`: Creates a `requirements.txt` file based off of `pyproject.toml`.
