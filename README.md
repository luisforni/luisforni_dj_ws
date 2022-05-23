virtualenv env

en linux
source env/bin/activate

en windows
env\Scripts\activate

pip3 install -r librerias.txt

cd balanz
python manage.py migrate
python manage.py runserver