# try.flask-py-api
Repo for trying out Flask with Python for creating an Api

### Creating Python VirtualEnv, Activating & Deactivating
```bash
try.flask-py-api % python3 -m venv /Users/gameoverzeus/PycharmProjects/try.flask-py-api/venv
try.flask-py-api % source venv/bin/activate
(venv) try.flask-py-api % pip install -r requirements.txt 
(venv) try.flask-py-api % deactivate
```

### Flask debug mode
```bash
$ export FLASK_APP=main.py
$ export FLASK_ENV=development
$ flask run
```

### Flask debug mode in one line command
```bash
$ FLASK_APP=main.py FLASK_ENV=development flask run
$ FLASK_APP=main.py FLASK_ENV=development flask run --port 8080
$ flask run --help
```
