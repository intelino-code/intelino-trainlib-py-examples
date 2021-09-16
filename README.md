# intelino-trainlib-py-examples

[![Documentation Status](https://readthedocs.org/projects/intelino-trainlib-py/badge/?version=latest)](https://intelino-trainlib-py.readthedocs.io/en/latest/?badge=latest)
[![PyPI](https://img.shields.io/pypi/v/intelino-trainlib.svg)](https://pypi.org/project/intelino-trainlib/)
[![PyPI](https://img.shields.io/pypi/pyversions/intelino-trainlib.svg)](https://pypi.org/project/intelino-trainlib/)

Sample code for `intelino-trainlib` - the synchronous intelino train library.

## Download and install

**Download** this repository as a zip file through the github
[download link][github_zip], or you can clone it with:

```console
git clone https://github.com/intelino-code/intelino-trainlib-py-examples.git
cd intelino-trainlib-py-examples
```

[optional] To create and activate a **local environment**, use:

```console
python3 -m venv .env
```

- Linux and macOS
  ```console
  source .env/bin/activate
  ```

- Windows `cmd`
  ```
  .env\Scripts\activate.bat
  ```

To **install** the intelino train library, run:

```console
python3 -m pip install intelino-trainlib
```

For a more detailed installation guide, see our [quick start guide][docs_install].

To **verify** that everything is installed correctly and works, you can turn on
Bluetooth on your device, turn on your intelino smart train and scan for it
with Python.

```console
python3 -m intelino.scan
```

If you don't see your train in the list or you run into some issues, more
details can be found in our [documentation][docs_scanning].


# Running examples

Open the `intelino-trainlib-py-examples` directory in your favorite editor.
You will find all examples under the `examples` directory. You can read them
and run as:

```
python3 ./examples/01_get_train_info.py
```

They always have some descriptive name and at the beginning of each example you
will find more description in three sections: topics, required setup (track
layout) and notes about the program.

Happy coding...


# More resources

- [intelino-code/intelino-trainlib-py](https://github.com/intelino-code/intelino-trainlib-py)
- [intelino-code/intelino-trainlib-async-py](https://github.com/intelino-code/intelino-trainlib-async-py)
- https://intelino.com
- https://lab.intelino.com


[github_zip]: https://github.com/intelino-code/intelino-trainlib-py-examples/archive/refs/heads/master.zip
[docs_install]: https://intelino-trainlib-py.readthedocs.io/en/latest/installation.html
[docs_scanning]: https://intelino-trainlib-py.readthedocs.io/en/latest/scanning.html