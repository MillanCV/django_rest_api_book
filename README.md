# Library web site

Basic Library website built with Djando and DRF


## Crear una app e integrarla

* python manage.py startapp books
* crear modelo
* migrar
* anadir modelo a admin
  * admin.site.register(Modelo)
* anadir vista
  * controla como se muestra el contenido de la base de datos.
  * ListView
* Anadir urlpattern en aplicacion y en admin