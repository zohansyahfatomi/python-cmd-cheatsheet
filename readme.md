# Python Cheat Sheet!

## CLI command Python
- `python3 -m venv venv` : Creating virtual environment
- `source venv/bin/activate` : Activate terminal session in virtual environment
- `deactive` : deactive

## Symbol
- `@`

## Pytest
The directory must be:
```
mypackage/
|
|__ mypackage/
|     |
|     |__ mypackage.py
|     |__ __init__.py
|
|__ tests/
|     |__ test.py
|
|__ setup.py
```
- `pip install -e .` : Installing our package. The location is in `setup.py`
- `pytest` (in the root directory) : To execute the pytest