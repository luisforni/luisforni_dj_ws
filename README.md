# Entorno Virtual

```bash
virtualenv env
```

En linux
```bash
source env/bin/activate
```

En windows
```bash
env\Scripts\activate
```

## Instalación de librerias

```bash
pip3 install -r librerias.txt
```

## Ejecutar projecto

```bash
cd balanz
python manage.py migrate
python manage.py runserver
```

Abrir en el navegador http://localhost:8000
