# F23-Webscraping

## Setup

First, clone this repo (via ssh)

```bash
git clone git@github.com:MichiganDataScienceTeam/F23-Webscraping.git
```

### Virtual Environment

You can choose whether or not to use a virtual environment for this project (though it is recommended). The setup guide shows how to create a venv through pip, but it can also be done via Conda if you want. The important thing is that you can run the commands found in the [Good to go](#good-to-go) section.

We are going to initialize a Python virtual environment with all the required packages. We use a virtual environment here to isolate our development environment from the rest of your computer. This is helpful in not leaving messes and keeping project setups contained.

First create a Python 3.8 virtual environment. The virtual environment creation code for Linux/MacOS is below:

```bash
python3 -m venv venv
```


Now that you have a virtual environment installed, you need to activate it. This may depend on your system, but on Linux/MacOS, this can be done using

```bash
source ./venv/bin/activate
```

Now your computer will know to use the Python installation in the virtual environment rather than your default installation.

After the virtual environment has been activated, we can install the required dependencies into this environment using

```bash
pip install -r requirements.txt
```

### Good to go

This readme was adapted from [W23-Webscraping](https://github.com/MichiganDataScienceTeam/W23-Webscraping/tree/main)