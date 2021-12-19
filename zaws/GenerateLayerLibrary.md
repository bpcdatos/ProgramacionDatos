# Comandos para Agregar una nueva libreria a Lambda-Layers

Como revisamos en clase los comandos para Ubuntu serian los siguientes:


### 1. Preparar

Preparar el entorno de Ubuntu con los programas basicos:
```
sudo apt-get update
sudo apt-get install python3
sudo apt-get install python3-venv
sudo apt install zip
```

### 1. Contruir Env

Construir un enviroment del paquete Python, para esto la nomenclatura es la siguiente:

<center>python3 -m venv #FOLDER# </center>

En este caso el folder es python:
```
python3 -m venv python
cd python
source python/bin/activate
python3 -m pip install pandas==1.2.1
python3 -m pip install fsspec==2021.4.0
python3 -m pip install s3fs==2021.4.0
python3 -m pip install mysql-connector-python==8.0.26
deactivate
```
