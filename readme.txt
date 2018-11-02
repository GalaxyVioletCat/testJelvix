python -m venv venv
pip install -r requirements.txt
python manage.py migrate
python manage.py migrate app
python manage.py runserver