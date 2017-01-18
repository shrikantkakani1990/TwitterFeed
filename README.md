# AlesiatecBackend

# Installing VirtualEnv
Make sure that you're running Python 2.7 or greater but not Python 3.*

Then install virtualenv for the project using '[sudo] pip install virtualenv'.
Once virtualenv is installed, create a new virtualenv by typing 'virtualenv [name_of_your_env]'
Also, make sure to add [name_of_your_env] to .gitignore file.

Why Virtualenv? Read https://pythontips.com/2013/07/30/what-is-virtualenv/

Now, activate your virtualenv using 'source [name_of_your_env]/bin/activate'

# Installing Project Dependencies
Once your virtualenv is up and running, run the following command:
    pip install -r requirements.txt

This will install all the dependencies.

# Make sure to update requirements.txt
requirements.txt is one place where we keep all the dependencies needed for our project. So whenever other developers are working on this, all they'll have to do is to update the new dependencies. Also, as a good developer, please make sure that you update requirements.txt after you add any new dependencies to the project.

# Running the Project
Make sure that your virtualenv is running. Now run 'python manage.py runserver' to run the application locally.
