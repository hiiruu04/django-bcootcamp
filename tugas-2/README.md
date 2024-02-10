# Tugas 2

## How to use
- `nix-shell` shell.nix
- create python virtualenvironment: `python` -m venv .venv
- activate environment: `source venv/bin/activate`
- install dependencies: `pdm sync` or `pdm install`
- run django-app: `python src/manage.py runserver`
- Go to `localhost:8000/hello/`
