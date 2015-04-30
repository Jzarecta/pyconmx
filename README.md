# PyConMX
Repositorio del sitio django-cms para el PyConMX o Conferencia de Python en Mexico.

## ToDo
Es necesario actualizar este dejango-cms ya que usa un parche depreciado por el nuevo motor de GAE. Se debera reemplazar por Django-nonrel ubicado en https://github.com/django-nonrel

Look and Feel - Tambien es importante agregar un mejor diseño y hacer el contenido más atractivo. Recomiendo implementar un semi sistema de Blurs e insertar carrusel a las notas. Recomiendo un estilo como http://softwarelivre.org/fisl16

El lenguaje se debe cambiar a python2.7 asi como el backend al nuevo HDR.

## Colaboracion
Si quieres contribuir es necesario que abras tu cuenta en Google AppEngine, es gratis si has usado algun servicio de Google. Haz el pull, genera el appID y crea un deploy. Más información en https://cloud.google.com/appengine/docs/python/

Si nunca has usado AppEngine, te recomiendo que hagas el tutorial de la documentacion para que te familiarices con los commandos de gcloud, appcfg.py etc.

Si no conoces Python puedes ayudarnos en el frontend, solo es importante que te familiarices con el sistema de templates que se esta usando para poder insertar tu javascript-css necsario. 

### Rutas relevantes
El codigo se puede percibir en tres niveles:

* Sistema, la raiz del sistema son los archivos y directorios de este primer nivel incluyendo __common/ media/ registration/ templates/__
* Proyecto, es donde vive el CMS estan en el directorio __app1__
* Plantillas, es donde estan los html/css/js ubicados en __app1/templates/app1/__ 

## Contacto
Por twitter en @jza
