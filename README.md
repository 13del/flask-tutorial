https://flask.palletsprojects.com/en/2.2.x/tutorial/

## Installation

Clone the repository. 

Install the project with

```bash
pip install -e .
```

## Usage

Initialize the database

```bash
flask --app flaskr init-db
```

Run the Flask webserver with

```bash
flask --app flaskr run
```

or in debug-mode with:

```bash
flask --app flaskr run --debug
```

It will run by default on port 8080.

To register a user:

http://127.0.0.1:5000/auth/register

Login:

http://127.0.0.1:5000/auth/login

To run the tests, use the pytest command. It will find and run all the test functions you’ve written.

$ pytest

```bash
pytest
```


If any tests fail, pytest will show the error that was raised. You can run pytest -v to get a list of each test function rather than dots.

To measure the code coverage of your tests, use the coverage command to run pytest instead of running it directly.


```bash
coverage run -m pytest
```

You can either view a simple coverage report in the terminal:

```bash
coverage report
```

An HTML report allows you to see which lines were covered in each file:

```bash
coverage html
```
This generates files in the htmlcov directory. Open htmlcov/index.html in your browser to see the report.
