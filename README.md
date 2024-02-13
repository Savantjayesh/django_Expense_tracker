how run :
follow those command
   virtualenv -p puthon3 env
   source env/bin/activate
   pip install python
   pip install django 
   cd fin_tracker
   python manage.py runserver

as related to models :
    python manage.py makemigration
    python manage.py migrate
   
deploy :
pip install gunicorn
