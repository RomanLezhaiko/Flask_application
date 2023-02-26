# Flask_application

## Description

Application for registering for an event using the Flask framework.
Everyone can get a list of all participants, cancel their registration by phone number, change data.

## Quick start

In your command line:

```
https://github.com/RomanLezhaiko/Flask_application.git

cd Flask_application
```

Create virtual enviroment:
```
python3 -m venv .venv

source .venv/bin/activate
```

Install requirements:
```
pip install -r requirements.txt
```

Initialize database:
```
python3

from db import init_db

init_db()
```

Run the app:
```
python app.py
```
