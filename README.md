# Django Rest Framework Tutorial

This is the code written while following [William S. Vincent's](https://wsvincent.com) [Django REST Framework Tutorial.](https://wsvincent.com/official-django-rest-framework-tutorial-beginners-guide/)

**Python version: 3.7.1**

**Django version: 2.1.7**

## Set up

### Mac installation instructions

```bash
# Install homebrew 
/usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
brew update

# Install python
brew install python3

# Create a virtual environment for Python
python3 -m venv venv

# Source the virtual environment
source venv/bin/activate

# Install the Python dependencies
pip install -r requirements.txt
```

### Running the local development server

```bash
# Source the virtual environment
source venv/bin/activate

# Run the local development server
python tutorial/manage.py runserver
```

The application can now be accessed at [http://127.0.0.1:8000/](http://127.0.0.1:8000/)

## Utility commands

### Start an interactive shell with the Django context

```bash
# Source the virtual environment
source venv/bin/activate

# Start the interactive shell
python tutorial/manage.py shell
```

### Create an admin account

```bash
# Source the virtual environment
source venv/bin/activate

# Create a super user
python tutorial/manage.py createsuperuser
```

You can now use the credentials you entered to visit the [admin panel.](http://127.0.0.1:8000/admin)
