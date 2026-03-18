# Project Style Guide

## Python
- Follow settings set in `.flake8`, if some rules are not sure you can follow [PEP8](https://peps.python.org/pep-0008/) or trust your guts
- Line length: 120 characters (set in black autoformatter)

## Naming
- Variables: snake_case
- Functions: camelCase
- Classes: PascalCase
- Constants: UPPER_CASE

## Tools
- Lint: flake8
- Formatter: black, isort

### How to:

You can call `make lint` to run flake8 or `make format` to autoformat your code.
