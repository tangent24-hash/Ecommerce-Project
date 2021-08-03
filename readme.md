# install virtual environment
python3 -m venv venv
source venv/bin/activate

# install requirements
pip install -r requirements.txt

# run server
python manage.py runserver

# superuser
email: sohan@example.com
pass: 123