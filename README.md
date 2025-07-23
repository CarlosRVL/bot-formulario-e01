# bot-formulario-e01
Ejemplo de un bot que automatiza la introducción de datos en un formulario web

## Requisitos
Este proyecto utiliza Pyhon con las librerias: 

- selenium
  - Selenium necesita un "driver" para controlar un navegador específico (Chrome, Firefox, Edge, etc.). Se debe descargar el driver correspondiente al navegador y a su versión. Por ejemplo, para Chrome, ChromeDriver. EL driver debe estar en un lugar accesible para el script, preferiblemente en el PATH del sistema o en la misma carpeta del proyecto.
- webdriver-manager

    
## Entorno Virtual
Elijo utilizar un entorno virtual (vent). Se utiliza así:
- Para crear el entorno por primera vez, en la carpeta del proyecto, se ejecuta:
~~~
python -m venv venv
~~~
- Para ejecutar la aplicación o instalar las librerias se ejecuta cada vez:
~~~
.\venv\scripts\activate
~~~
- Para instalar las librerias o paquetes:
~~~
pip install <paquete>
~~~

## Instalación de paquetes
~~~
pip install selenium
pip install webdriver-manager
~~~
