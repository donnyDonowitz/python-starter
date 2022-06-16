# python-starter
Python Project template

## Architecture

TODO

## Environment

This project is a standard Python project using a virtualenv.
To create the virtualenv it assumes that there is a `python3` (or `python` for Windows) executable in your path witch access to the `venv` package.

To manually create a virtualenv, run

```sh
python3 -m venv .venv
```

After the init process completes and the virtualenv is created, you can  use the following command to activate the virtualenv.

```sh
source .venv/bin/Activate
```

If you are on a Windows platform, you would activate the virtualenv like this.

```cmd
.\.venv\Scripts\activate
```

Once the virtualenv is activated, you can install the required dependencies.

```sh
# update dependency file
pip-compile --output-file=requirements.txt requirements.in
# install dependencies
pip install -r requirements.txt
```

And for local development, add set your PYTHONPATH.

```sh
export PYTHONPATH=$PYTHONPATH:....
```

## Formatting

This project is formatted with black.


