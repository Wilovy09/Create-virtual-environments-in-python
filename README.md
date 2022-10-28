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
