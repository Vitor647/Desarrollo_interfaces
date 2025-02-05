# Manual de Usuario: Instalación de Python en Ubuntu

## Introducción

Este manual de usuario proporciona instrucciones detalladas sobre cómo instalar Python en un sistema operativo Ubuntu. Python es un lenguaje de programación versátil y popular, utilizado en una amplia variedad de aplicaciones, desde el desarrollo web hasta el análisis de datos y la inteligencia artificial.

## Requisitos Previos

Antes de comenzar con la instalación, asegúrate de cumplir con los siguientes requisitos:
- Un sistema operativo Ubuntu (versión 20.04 o superior).
- Acceso a una terminal con privilegios de superusuario (root).
- Conexión a Internet.

## Pasos para la Instalación

### 1. Actualizar los Paquetes del Sistema

Abre la terminal pulsando `Ctrl + Alt + T` y ejecuta el siguiente comando para actualizar los paquetes del sistema operativo:

```
sudo apt update
sudo apt -y upgrade

### 2. Verificar la Instalación de Python

Ubuntu 20.04 y versiones superiores vienen con Python 3 preinstalado. 
Para verificar si Python ya está instalado en tu sistema, ejecuta el siguiente comando en la terminal:

```
python3 -V

### 3. Instalar Python (si no está instalado)

Si Python no está instalado, puedes instalarlo ejecutando el siguiente comando:

```
sudo apt install -y python3


### 4.Instalar pip

pip es una herramienta para instalar y gestionar paquetes de Python. 
Para instalar pip, ejecuta el siguiente comando:

```
sudo apt install -y python3-pip


### 5. Verificar la Instalación de pip

Para asegurarte de que pip se ha instalado correctamente, ejecuta el siguiente comando:

```
pip3 --versión

### 6. Ahora puedes instalar paquetes de Python utilizando pip. 

Por ejemplo, para instalar el paquete numpy, ejecuta el siguiente comando:

```
pip3 install numpy


### Solución de Problemas
Problema: No se encuentra el comando python3
Si recibes un error indicando que el comando python3 no se encuentra, asegúrate de que Python está instalado correctamente y que la ruta del ejecutable está en tu variable de entorno PATH.

### Problema: Error de permisos
Si encuentras errores de permisos, asegúrate de estar ejecutando los comandos con privilegios de superusuario utilizando sudo.




