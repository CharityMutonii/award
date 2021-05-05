# Award

An web application which allows a user to post a project he/she has created and get it reviewed by his/her peers and and review the work submitted by his/her peers. A project can be rated based on 3 different criteria.

Technologies used
Python3
SQLite3
MDBootstrap 4.8.10
jQuery 3.4.1
Django 3.2
Requirements
This project requires python3 to run

Setting up a virtual environement
To create a virtual environement, you will need to install virtualenv

pip3 install virtualenv
Create the virtual environement by running the command in the project root

virtualenv venv
Activate the virtual environement by running the command

source venv/bin/activate
You can always deactivate the virtual environement by entering this command

deactivate
Usage
Make migrations by using the command

python manage.py migrate
You need to create a .env file and set your secret key inside it. To launch the app, simply run the command

 python manage.py runserver
Run tests
python manage.py test
API
Users endpoint

Projects endpoint


Author
Charity Mutoni

Github: @CharityMutonii
