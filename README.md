-------------------------------------------------------------------------------
Please Read carefully and follow ***IMPORTANT***
------------------------------------------------------------------------------

Make sure your current directory is in manage.py and requirements.txt files

Install the Modules:
-------------------------------------------------------------------------------
***First install python software with version 3.6.1.1
After run the command to install all Requirements
***COMMAND:  pip install -r requirements.txt

Important Commands :
--------------------------------------------------------------------------------
Run two commands for create databaase tables and if any modifications done in models(tables)
***python manage.py makemigrations
***python manage.py migrate

RUN THE PROJECT:
----------------------------------------------------------------------

As our project does not have any registration processs so we have to create 
Admin (superuser).... then admin can create staff and students
***To create Admin run this command :  python manage.py createsuperuser 
Give mail and password . The password is not visible but it will valid
Then run the project
***Command : python manage.py runserver***
Login as superuser(admin) 
And create sessions(acadamic year), courses, subjects, sections in courses , and 
create the students along with their personal details session-->course-->section-->rollnumber
Then create staff with their courses, subjects , and their details
