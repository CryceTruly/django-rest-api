# full-drf-tutorial
A todo app with user authentication

[Tutorial Playlist Link](https://www.youtube.com/watch?v=zpz5OeNKUug&list=PLx-q4INfd95FWHy9M3Gt6NkUGR2R2yqT8)


### How to setup locally
#### Requirements

- Python3.7
- pip3
- virtualenv


#### setup instructions

- pull the project using git
```cmd
   git clone https://github.com/CryceTruly/django-rest-api.git
   ```
- create   a virtualenv using virtualenv
```cmd
   python -m pip install --upgrade pip
   pip install virtualenv
   virtualenv venv_name
   ```
- activate it 
```cmd
   source venv_name/bin/activate
   ```
- or activate Windows
```cmd
   venv_name/bin/activate.bat
   ```
- install dependencies from the requirements.txt file
```cmd
   pip install -r requirements.txt
   ```

- migrate the database tables
```cmd
   python manage.py migrate
   ```
- start a development server using 
```cmd
   python manage.py runserver
   ```
