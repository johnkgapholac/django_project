# django_project

Django is a Python framework that makes it easier to create web sites using Python.

Django takes care of the difficult stuff so that you can concentrate on building your web applications.

To check if your system has Python installed, run this command in the command prompt:
python --version

To check if your system has PIP installed, run this command in the command prompt:
pip --version

Then you have to activate the environment, by typing this command on:
.\Scripts\activate

Note: Remember to install Django while you are in the virtual environment!
Django is installed using pip, with this command:
python -m pip install Django

You can check if Django is installed by asking for its version number like this:
django-admin --version

Now that you have a Django project, you can run it, and see what it looks like in a browser.
Navigate to the /my_tennis_club folder and execute this command in the command prompt:
python manage.py runserver

Start the server by navigating to the /my_tennis_club folder and execute this command:
python manage.py runserver

To open a Python shell, type this command:
python manage.py shell

Hit [enter] and write this to look at the empty Member table:
Member.objects.all().values()

