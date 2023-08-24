# valuelock

![PyPI](https://img.shields.io/pypi/v/valuelock)
![License](https://img.shields.io/pypi/l/valuelock)
![Python Versions](https://img.shields.io/pypi/pyversions/valuelock)

A Python package for locking based on values.

## Installation

You can install `valuelock` using `pip`:

```bash
pip install valuelock
```

## Usage

```python
import valuelock

# Acquire and release locks to protect shared resources
with valuelock.get_lock("resource_id"):
    # Your protected code here
```

## Features

* Locking based on values.
* Thread-safe.

## Documentation

Detailed documentation can be found on the [GitHub repository](https://github.com/killbus/py-valuelock).
