# globus-jupyter-notebooks

## Install

These notebooks require Python 2.6+ or Python 3.2+. See
http://docs.python-guide.org/en/latest/starting/installation/
for easy Python installation instructions.

You may need to install pip and virtualenv first.  For example, on Mac OS X:

    sudo easy_install pip
    sudo pip install virtualenv

Clone the globus-jupyter-notebooks git reporsitory:

    git clone https://github.com/globus/globus-jupyter-notebooks.git

Create a virtualenv:

    cd globus-jupyter-notebooks
    virtualenv venv
    . ./venv/bin/activate

Install the notebook requirements using pip:

    pip install -r requirements.txt

## Run

To open a browser window with the Jupyter notebook interface:

    jupyter-notebook SDK.ipynb

If running remotely, for example, in a tutorial EC2 instance:

    jupyter notebook --ip="*" --port 443 --no-browser

## Links

* Globus SDK Documentation http://globus.github.io/globus-sdk-python/
* Globus SDK Source: https://github.com/globus/globus-sdk-python
* Globus CLI Source: https://github.com/globus/globus-cli
