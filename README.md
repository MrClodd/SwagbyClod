# SwagbyClod
This challenge is implemented with behave + selenium in Python


## Set up instructions
You need google chrome installed locally

1. Install pyhton 3.11 or higher https://www.python.org/downloads/
2. Install pipenv https://pypi.org/project/pipenv/
4. Install dependencies:

            pipenv install

5. Execute the tests

            pipenv run behave -f html -o report/

6. generate HTML report with allure

            sudo allure serve -p 38923 report/
