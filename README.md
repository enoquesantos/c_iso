# ciso

[![Tests](https://github.com/ioos/ciso/actions/workflows/tests.yml/badge.svg)](https://github.com/ioos/ciso/actions/workflows/tests.yml)
[![Wheels](https://github.com/ioos/ciso/actions/workflows/cibuildwheel.yml/badge.svg)](https://github.com/ioos/ciso/actions/workflows/cibuildwheel.yml)


Fast cythonized code for iso-slices of ocean models properties.


## Comandos
- virtualenv .venv
- source .venv/bin/activate
- pip install -r requirements.txt
- python -m build --wheel . --outdir dist
- abi3audit dist/*.whl --summary --assume-minimum-abi3 3.11 --verbose --strict
