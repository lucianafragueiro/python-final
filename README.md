Hoy vamos a hacer actividad en Python en un día como programadores:
1. Abrir la terminal de Git Bash o terminal en Linux, debe ser como administrador en Window
2. Creamos una carpeta o directorio: 
mkdir python-final
3. Entramos en ella: 
cd python-final
4. Iniciamos el repositorio:
git init
5. Creamos un archivo:
touch finales.py
6. Abrimos VSC:
code .
7. En terminal ingresamos el comando para saber la versión de Python que tenemos instalada:
python -V
python3 -V
8. Creamos el entorno virtual en Python:
python3 -m venv venv #Creamos el entorno virtual
9. Activamos el entorno virtual:
source venv/bin/activate #Activamos el entorno virtual en Linux
venv/scripts/activate #En windows
10. Hacemos actualización del pip de Python
python3 -m pip install --upgrade pip #Actualizamos el pip
11. Investigar ¿Qué es el pip y porque lo actualizamos?
12. Hacer al primer commit de este trabajo y unirlo al repositorio remoto.
13. Enviar el enlace del repositorio remoto donde tiene que tener un README.md con todos los detalles de lo que les fui mostrando en comandos, y las respuesta del punto 11 de más arriba.

¿Que es un pip?
pip es una herramienta en Python que se utiliza para administrar paquetes de software. Su nombre es un acrónimo recursivo que significa "pip Installs Python" o "pip Installs Packages". Algunos puntos clave sobre pip:
Instalación de Paquetes: pip se utiliza principalmente para instalar y administrar paquetes de Python, que son bibliotecas de software que proporcionan funcionalidades adicionales al lenguaje Python.
Repositorio de Paquetes: Por defecto, pip instala paquetes desde el Python Package Index (PyPI), que es un repositorio público de paquetes de software para Python. Sin embargo, también puede instalarse desde otros repositorios o desde archivos locales.
Comandos Básicos:
pip install nombre_paquete: Instala un paquete de Python.
pip uninstall nombre_paquete: Desinstala un paquete de Python.
pip freeze: Muestra todos los paquetes instalados y sus versiones.
pip list: Lista todos los paquetes instalados.
pip search término: Busca paquetes en PyPI basados en un término específico.
Entorno Virtual: pip es fundamental al trabajar con entornos virtuales en Python. Los entornos virtuales permiten aislar dependencias y versiones de paquetes para proyectos específicos.
Versiones y Actualizaciones: pip también gestiona la actualización de paquetes instalados a versiones más recientes, asegurando que tu entorno de desarrollo o producción tenga las últimas correcciones y características.
En resumen, pip es una herramienta esencial para cualquier desarrollador de Python que necesite gestionar paquetes de software de manera eficiente dentro de sus proyectos.