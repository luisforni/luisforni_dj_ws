virtualenv env

source env/bin/activate (linux)

env\Scripts\activate (windows)

pip3 install -r librerias.txt

cd balanz
python manage.py migrate
python manage.py runserver
