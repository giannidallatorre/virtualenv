# Jupyter Notebook
Simple instructions to install and use [**Jupyter Notebook**](http://jupyter.org/) on Mac OS using `python virtual env` and `Python 3`.

## Install Jupyter
New virtual environment for jupyter notebook

    pyvenv venv
Install `notebook` and all the dependency needed by your `project`

    venv/bin/pip install notebook
(These are not needed for jupyter).

    venv/bin/pip install matplotlib
    venv/bin/pip install pandas
    venv/bin/pip install seaborn
    venv/bin/pip install sklearn

Alternatively you can edit a `requirement.txt` for your `project` with all the python dependencies and
install all of them in one step.

    venv/bin/pip install -r project/requirements.txt
## Usage
Activate `python virtual env`

    source venv/bin/activate
Run **Jupyter**

    jupyter notebook
Deactivate `python virtual env`

    deactivate
