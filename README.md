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
