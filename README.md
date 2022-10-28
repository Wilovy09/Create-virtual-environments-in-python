# How to create a virtual environment

First we need to install virtualenv

```console
pip install virtualenv
```

Once installed **virtualenv**

We will execute these commands in the path where we want our environment to be created

This command will create the environment

```console
virtualenv -p python3 name
```

This command will activate the environment

```console
.\env\Scripts\activate
```

We will see what libraries we installed by default

```console
pip list
```

We update pip (only if necessary)

```console
python.exe -m pip install --upgrade pip
```

## How to disable our terminal environment

We write this command inside our environment

```console
deactivate
```

It will recognize it automatically since we are in our virtual environment

## Create Package

To put the libraries that we use and the versions of these we will write:

```console
pip freeze > requirements.txt
```

## How to install the package

It is necessary to have a virtual environment already created

```console
pip install -r requirements.txt
```

```console
pip list
```

# Como crear un entorno virtual

Primero necesitamos instalar virtualenv

```console
pip install virtualenv
```

Ya una vez instalado **virtualenv**

Ejecutaremos estos comandos en la ruta donde queremos que se cree nuestro entorno

Este comando nos creara el entorno

```console
virtualenv -p python3 nombre
```

Este comando nos activara el entorno

```console
.\env\Scripts\activate
```

Veremos que librerias nos instalo por defecto

```console
pip list
```

Actualizamos pip (solo si es necesario)

```console
python.exe -m pip install --upgrade pip
```

## Como desactivar el entorno de nuestra terminal

Escribimos este comando dentro de nuestro entorno

```console
deactivate
```

Lo reconocera en automatico ya que estamos en nuestro entorno virual

## Crear Paqueteria

Para poner las librerias que usamos y las versiones de estas escribiremos:

```console
pip freeze > requirements.txt
```

## Como instalar la paqueteria

Es necesario tener un entorno virtual ya creado

```console
pip install -r requirements.txt
```

```console
pip list
```
