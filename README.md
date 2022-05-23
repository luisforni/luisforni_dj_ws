# Cotizador de DOLAR MEP y CABLE

Esta aplicación web está construida con DJANGO y WEBSOCKETS. Permite cotizar el DOLAR MEP y el DOLAR CABLE a partir de los instrumentos AL30 y GD30 en los plazos de liquidación CI, T+1 y T+2.

## Clonar repositorio

```bash
git clone https://github.com/luisforni/luisforni_dj_ws.git
cd luisforni_dj_ws
```

## Crear entorno virtual

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
