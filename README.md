# Clase 11 Actividad en Python

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


## ¿Qué es el PIP y por qué lo actualizamos?

El Python Package Index (PIP) es una herramienta para instalar y controlar los paquetes de Python. Se utiliza para descargar los paquetes desde PyPI e instalarlos en nuestro sistema. 
Actualizar pip es importante por varios motivos:

1. Corrección de errores y parches de seguridad: las actualizaciones suelen incluir correcciones de errores y vulnerabilidades descubiertas desde la última versión. La actualización garantiza que tendrá la última versión estable con estas correcciones aplicadas, lo que ayuda a mantener seguro su entorno Python.

2. Compatibilidad: Es posible que se requieran versiones más recientes de pip para instalar o administrar los paquetes o dependencias más recientes. Algunos paquetes pueden requerir funciones o correcciones que solo están disponibles en versiones más recientes de pip.

3. Mejoras de rendimiento: las actualizaciones pueden incluir optimizaciones y mejoras de rendimiento que hacen que la instalación, actualización y administración de paquetes sean más rápidas y eficientes.

4. Mejoras de funciones: las nuevas versiones de pip pueden introducir nuevas funciones o mejoras a las funciones existentes, lo que puede mejorar su flujo de trabajo de desarrollo o proporcionar funcionalidad adicional.

5. Soporte de la comunidad: Es posible que la comunidad de Python ya no admita activamente versiones anteriores de pip. La actualización garantiza que pueda beneficiarse del soporte continuo y la compatibilidad con otras herramientas y librerías.

