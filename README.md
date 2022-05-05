<img width="20%" src="./.github/assets/logo_light.png#gh-light-mode-only" />
<img width="20%" src="./.github/assets/logo_dark.png#gh-dark-mode-only" />

Slim is a user friendly application which shows where money are being spended and clever ways on how to reduce expenses.

## Idea
Due to the fact that we wanted to spend less and invest more money, we started recording our daily expenses using a spreadsheet. We realized that we could save about 10% per month of unnecessary costs. 

## Table of contents
1. [User Manual](#user-manual)
    - [Development](#development)


## User manual
You will need to have [Python 3.10](https://www.python.org/downloads/release/python-3100/) and [pip](https://pip.pypa.io/en/stable/installation/) installed. Feel free to install a [Python Virtual Environment](https://docs.python.org/3/library/venv.html) to isolate the Python pacages used in the project.

The software requirements for the project are shown in the `requirements.txt` file as well as the versions used in the project.

Install the depentancies using the following command:
```bash
pip install -r requirements.txt
```

Then, open the server and run the application by running:
```
python manage.py runserver
```

### Development
The projects uses Linters and Formaters as well as GitHub Actions for CI (Continius Integration). If you want to open a PR (Rull Request) make sure, to run the folowing commands before commiting:
```
black src
flake8 src
```
The `black src` command formats your code and the `flake8 src` command lint's your code. 
