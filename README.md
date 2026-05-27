# webapp_VB

## 1. Crear un Ambiente Virtual (Virtual Enviroment)

Crear un virtual environment para instalar las librerias necesarias de Python.

````shell
python3 -m venv .venv
````

## 2. Iniciar el Virtual Environment

Iniciar el virtual environment para instalar las librerías necesarias para el proyecto.

````shell
source .venv/bin/activate
````

## 3. Actualizar **PIP**

Actualizar el instalador de paquetes de Python **pip**.

````shell
pip install --upgrade pip
````

## 4. Instalar el mmicro-framework **web.py**

Instalar el micro-framework **wen.py** para la creación de Aplicaciones Web utilizando Python.

````shell
pip install web.py
````
## 5. Crear el archivo **requirements.txt**

Crear el archivo **requirements.txt** con la lista de las librerias y versiones de cada una, necesarias para el proyecto.

````shell
pip freeze > requirements.txt

## 6. Crear el archivo **runtime.txt**

Crear el archivo **runtime.txt** con la version

````shell

python3 -V > runtime.txt
````

## 7. Crear el archivo **.gitignore**

Crear el archivo **.gitinore** para inidica las carpetasy archivos que no se van a sincronizar con el repositorio.

`````shell

*.pyc
_pycache__/
.venv/
````

## 8. Indexar las carpetas y archivos

Indexar las carpetas y archivos creados o modificados.

`````shell

git add .
````

## 9. Crear el punto de control **commit**

Crear el punto de control con los cambios realizados al proyecto.

````shell
git comit -m "CREATED configuración del virtual environment"
````

## 10. Sincronizar los cambios 

`````shell
git push -u origin main
