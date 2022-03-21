# turtle_i3us
A  ROS metapackage for the TurtleBot2 at I3US

## Descripción

Este metapaquete contiene los drivers, paquetes y ficheros *launch* necesarios para arrancar los TurtleBot2 del Instituto de Ingeniería Informática de la Universidad de Sevilla. 

## Requisitos

- S.O. Linux Ubuntu 16.04 y ROS Kinetic 
- Plataforma TurtleBot2 at I3US

Adicionalmente, es necesario la instalación del paquete para la cámara RealSense2:

```
sudo apt install ros-kinetic-realsense2-camera
```

## Instalación

### Preparación del espacio de trabajo

Crear un *workspace* de ROS vacío siguiendo los pasos en: http://wiki.ros.org/catkin/Tutorials/create_a_workspace

### Instalación del metapaquete

- Clonar este metapaquete dentro de la subcarpeta *src* del espacio de trabajo. 
- Instalar los módulos
  + cd src/turtle_i3us
  + git submodule init
  + git submodule update

## Ejecución

```
roslaunch turtle_i3us_apps turtle_i3us.launch
```


