[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/andmatt/python-tutorials/HEAD)

# python-tutorials
General python tutorials with an emphasis on data analysis with pandas

# Usage
For all python work it's recommended to use a virtual environment to avoid cluttering the default
python namespace.

If you want to do it locally, you can use [virtualenv](https://packaging.python.org/guides/installing-using-pip-and-virtual-environments/). Alternatively, [conda](https://docs.conda.io/en/latest/) has some built in environment management, or you can just use the built in binder link, which builds a transient container using the packages specified in the requirements.txt.

```
# install package
pip install venv

# create env
python3 -m venv env

# activate env
source env/bin/activate
```
