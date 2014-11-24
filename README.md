# TLAFLUO

Tomografía LAser FLUOrescente.

Proyecto para el Science Hack Day - Bogotá 2014

# Visualización

Para ver los archivos con extensión ipynb pueden usar la página [nbviewer.ipython.org](http://nbviewer.ipython.org/)

# Planeación

Unos dìas antes de asistir al SHD-Bogotá 2014 hicimos un plan de trabajo.

Primero debíamos convertir el vídeo a fotogramas, de fotogramas a matrices con las que podríamos trabajar.
[01 Adquisición de Imágenes.ipynb](http://nbviewer.ipython.org/github/flgomezc/tlafluo/blob/master/01%20Adquisicion%20de%20Imagenes.ipynb)

El esquema del proceso de reconstrucción de imágenes por proyecciones está en este link: [02 reconstrucción.ipynb](http://nbviewer.ipython.org/github/flgomezc/tlafluo/blob/master/02%20reconstrucci%C3%B3n.ipynb)

La visualizaciòn queda pendiente.

# Video a Fotos

Acá está el archivo original con el que trabajamos.
[![Vídeo en Youtube](http://img.youtube.com/vi/gh1sMMadxtc/0.jpg)](http://www.youtube.com/watch?v=http://img.youtube.com/vi/gh1sMMadxtc/0.jpg)

Las fotos están en la carpeta "data"

![data/o.tif](https://github.com/flgomezc/tlafluo/raw/master/data/0.tif "Imagen limpia data/0.tif")


# Tomografía

Reconstruímos un primer plano de la muestra a partir de  la imagen data/0.tif

[tomografia.ipynb](http://nbviewer.ipython.org/github/flgomezc/tlafluo/blob/master/tomografia.ipynb)

![img/tomo1.png](https://github.com/flgomezc/tlafluo/raw/master/img/tomo1.png "Imagen reconstruida 1")

![img/tomo2.png](https://github.com/flgomezc/tlafluo/raw/master/img/tomo2.png "Imagen reconstruida y limpia")


Reconstruìmos varios planos, con ellos podríamos reconstruir en 3D nuestra muestra. [tomografía-3D.ipynb](http://nbviewer.ipython.org/github/flgomezc/tlafluo/blob/master/tomografia-3D.ipynb)
