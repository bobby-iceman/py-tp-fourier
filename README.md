Para correr el archivo en Jupyter Lab se necesita correr los siguientes comandos:

1. Crear y activar el entorno virtual de ejecución
  
```
python -m venv venv
./venv/Scripts/activate # Si estás en Windows
source ./venv/bin/activate # Si estás en Linux/Ubuntu
```

2. Instalar Jupyter Lab en la carpeta

```
pip install jupyterlab
```
3. Instalar las dependencias del proyecto   

```
pip install numpy matplotlib scipy sounddevice
```
4. Correr la aplicación, se abrirá en el navegador predeterminado

```
jupyter lab
```
