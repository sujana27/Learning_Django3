# Learning_Django3
Beginner(COURSERA)
first-code ref: https://www.dj4e.com/lectures/DJ-02-Model-Single.txt


Python Django 7 Hour Course(https://www.youtube.com/watch?v=PtQiiknWUcI&list=LL&index=3&t=2145s)
https://github.com/divanov11/StudyBud/

#### Create a Django project FIRST time ####
-->1. Move into the directory where we have the project files :
---------------------------------------------------------------------------------------------
E:
cd Django
---------------------------------------------------------------------------------------------


#### Create a virtual environment ####
-->2.Let's install virtualenv first, Then we create our virtual environment & Activate the virtual environment :

---------------------------------------------------------------------------------------------
pip install virtualenv
virtualenv env_name
env_name\scripts\activate
---------------------------------------------------------------------------------------------

#### start a project
-->3. Install the requirements & create first Django project:

---------------------------------------------------------------------------------------------
pip install django
django-admin 
django-admin startproject project_name(Helloworld)
## Move the "env_name" folder into "Helloworld" folder
cd Helloworld
             OR
pip install -r requirements.txt
---------------------------------------------------------------------------------------------

#### Running the App ####
-->4. To run the App, we use :

---------------------------------------------------------------------------------------------
python manage.py runserver
---------------------------------------------------------------------------------------------
⚠ Then, the development server will be started at http://127.0.0.1:8000/



#### Running Django project for 2nd Time ####

-->1. Move into the directory where we have the project files :
---------------------------------------------------------------------------------------------
E:
cd Django\Helloworld
---------------------------------------------------------------------------------------------

#### Re-Activate the virtual environment ####
-->2.Check virtual environment name(env_name) & Activate the virtual environment :

---------------------------------------------------------------------------------------------
env_name\scripts\activate
---------------------------------------------------------------------------------------------

#### Running the App ####
-->3. To run the App, we use :

---------------------------------------------------------------------------------------------
python manage.py runserver
---------------------------------------------------------------------------------------------
⚠ Then, the development server will be started at http://127.0.0.1:8000/



