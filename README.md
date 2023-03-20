https://flask.palletsprojects.com/en/2.2.x/tutorial/

## Installation

Clone the repository. Use the dependency and package manager [Poetry](https://python-poetry.org/) to install all the dependencies of Crew-verve.

```bash
poetry install
```

## Usage
[Activate the Python virtual environment](https://python-poetry.org/docs/basic-usage/#activating-the-virtual-environment) with

```bash
poetry shell
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
