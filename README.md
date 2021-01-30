# Tara's Blogging App

See it in action: https://taras-blogging-app.herokuapp.com/

Simple Flask App where I can share my thoughts!

![](./app.gif)

## Installation and Usage

- `pipenv install -r requirements.txt`
- `pipenv shell`
- Tell terminal which application to work with:
  - `export FLASK_APP=app.py` (Linux/MacOS/GitBash)
  - `set FLASK_APP=app.py` (Windows Command Prompt)
  - `$env:FLASK_APP = "app.py"` (PowerShell)
- Tell terminal which environment to work in:
  - `export FLASK_ENV=development` (Linux/MacOS/GitBash)
  - `set FLASK_ENV=development` (Windows Command Prompt)
  - `$env:FLASK_ENV="development"` (PowerShell)
- `flask run`
