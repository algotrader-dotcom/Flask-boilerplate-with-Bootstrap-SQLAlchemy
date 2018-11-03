# Flask boilerplate features

- Bootstrap 3 and Font Awesome 4 with starter templates
- Flask-SQLAlchemy with basic User model
- Easy database migrations with Flask-Migrate
- Flask-WTForms with login and registration forms
- Flask-Login for authentication
- Flask-Bcrypt for password hashing
- Procfile for deploying to a PaaS (e.g. Heroku)
- pytest and Factory-Boy for testing (example tests included)
- A simple manage.py script.
- CSS and JS minification using Flask-Assets
- Optional bower support for frontend package management
- Caching using Flask-Cache
- Useful debug toolbar
- Utilizes best practices: Blueprints and Application Factory patterns
- Install the Flask dependencies:

```
sudo pip install flask_script
sudo pip install flask_migrate
sudo pip install flask_assets
sudo pip install flask_bcrypt
sudo pip install flask_cache
sudo pip install flask_debugtoolbar
```

Install and clone cookieclutter

```
sudo pip install cookiecutter
sudo pip install mock==1.0.1
cookiecutter https://github.com/sloria/cookiecutter-flask.git
```

You will be asked some information about your project, enter as you wish:

```
remote: Counting objects: 1545, done.
remote: Total 1545 (delta 0), reused 0 (delta 0), pack-reused 1545
Receiving objects: 100% (1545/1545), 1.57 MiB | 720.00 KiB/s, done.
Resolving deltas: 100% (857/857), done.
Checking connectivity... done.
full_name (default is "Steven Loria")? Steven Loria
email (default is "sloria1@gmail.com")?  slorial@gmail.com
github_username (default is "sloria")?  sloria
project_name (default is "My Flask App")? example
app_name (default is "myflaskapp")? example
project_short_description (default is "A flasky app.")? a flasky app
Then enter your project directory (example) and start the server
```

```
cd example
python manage.py runserver
You can then open http://127.0.0.1:5000
```

cookiecutter
cookiecutter output theme

[<img src="https://pythonspot-9329.kxcdn.com/wp-content/uploads/2015/07/cookiecutter.png">]()

