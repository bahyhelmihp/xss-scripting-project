## Form XSS Experiment
Final group project of Information Security course to demonstrate the vulnerability of a Django project when character escaping is deactivate.

### Usage

1. Install virtualenv if not exist
```pip install venv```

2. Create virtual environment
```python -m venv env```
(run this on project ROOT folder)

2. Activate virtual environment

    Windows: ``` env\Scripts\activate.bat```
    
    Mac:
     ```source env/bin/activate```

3. Install needed requirements
```pip install -r requirements.txt```

4. Migrate Database
```python manage.py makemigrations```
```python manage.py migrate```

5. Runserver on local
```python manage.py runserver```

6. Open http://localhost:5000 and start to inject XSS Script on any form-type founded on the site.
