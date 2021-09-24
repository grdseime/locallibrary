# locallibrary
Mozilla Python Django Tutorial Project

Name: Local Library
Description: A local library catalog of books w/ user authentication. Source, Mozilla tutorial: https://developer.mozilla.org/en-US/docs/Learn/Server-side/Django
Tools: Python/Django, html/css

Progress: Sections 1-8 have been completed and uploaded. Section 9 is in progress. 

To run the site:
1) Set up a python virtual environment
2) Install Django
3) Run these commands:

pip3 install -r requirements.txt
python3 manage.py makemigrations
python3 manage.py migrate
python3 manage.py collectstatic
python3 manage.py test # Run the standard tests. These should all pass.
python3 manage.py createsuperuser # Create a superuser
python3 manage.py runserver

(For the commands, if 'python3' doesn't seem to work, try 'py' instead.) 

4) To create users and/or librarians use the admin page: http://127.0.0.1:8000/admin/
5) To use the main site: http://127.0.0.1:8000
 
