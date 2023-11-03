# Explicación del pipline del Yelp
primero entiendamos que es un pepline

### ¿Qué es un Pipline?

Un "pipeline" en programación se refiere a una secuencia de pasos o etapas que se utilizan para procesar datos o realizar una serie de tareas de manera ordenada y eficiente. 

En un pipeline, cada etapa puede ser independiente y paralelizable, lo que permite un procesamiento eficiente y la posibilidad de escalar el sistema según sea necesario. Los pipelines son una herramienta poderosa para diseñar sistemas que manejen grandes volúmenes de datos o ejecuten tareas complejas de manera organizada y eficiente.

### ¿Qué es una maquina virtual?

En un pipeline, cada etapa puede ser independiente y paralelizable, lo que permite un procesamiento eficiente y la posibilidad de escalar el sistema según sea necesario. Los pipelines son una herramienta poderosa para diseñar sistemas que manejen grandes volúmenes de datos o ejecuten tareas complejas de manera organizada y eficiente.

## Creación de nuestra automatización

Nosotros estamos trabajando con GCP. Esta plataforma cuenta con multiples herramientas. En este caso por cuestiones de tiempo nos decantamos por trabajar con una VM. En el ambiente de GCP las máquinas virtuales nos permiten a los usuarios crear y administrar servidores virtuales con diferentes configuraciones de hardware y sistemas operativos según nuestras necesidades.

Nos brinda muchisimas ventajas:

* Escalabilidad
* Variedad de sistemas operativos
* Seguridad
* Gestión y automatización
* Integración con otros servicios de GCP
* Migración sencilla

En esta maquina virtual realizamos unas configuraciones e instalaciones de programas, librerias, etc. Para poder hacerla que sea lo más optima posible y que realicé los trabajos que queremos asignarles. Lo que más nos gusta de esta opción es que tiene mucha escalibilidad, ya que si necesitaramos más recursos podemos acceder a ellos.

### Librerias y programas que utilizamos en nuestra VM

* ***Python***: El lenguaje de programación utilizado para escribir y ejecutar código en la VM.
* ***Chromedriver***: El controlador de Selenium para interactuar con el navegador desde Python. Se utilizó para automatizar acciones en el navegador.
* ***Selenium***: Un marco de automatización de pruebas que se utilizó en Python para controlar el navegador.
* ***Google.cloud.storage***: es parte de la familia de bibliotecas de Google Cloud para interactuar con servicios de almacenamiento en la nube de Google, particularmente, Google Cloud Storage. Google Cloud Storage es un servicio de almacenamiento de objetos que permite almacenar y recuperar datos en la nube de Google.
* ***Cron***:  es una forma común de programar tareas en sistemas Unix y Unix-like, incluyendo sistemas Linux. Permite a los usuarios y administradores programar la ejecución de comandos o scripts en momentos específicos, como horas, minutos, días de la semana, etc.


## Video

Creamos un [video](https://drive.google.com/file/d/1m9XfsM0mWxTrELu12oXCSscTuTSSfKtZ/view?usp=sharing) en donde corremos una "*muestra*" de nuestro codigo que esta dentro de nuestra VM en GCP. Allí se puede observar como trabaja el programa que diseñamos de manera local. "*Hará basicamente lo mismo en nuestra VM, solamente que alli ya tiene configurado el CRON*"

### Archivos

* Este es el [archivo](https://drive.google.com/file/d/1GZOP_eBlDjF_9knN3UEGLuZ5hEZ2e1FU/view?usp=sharing) que se muestra en el video
* Estos son los [archivo](https://drive.google.com/drive/folders/112NMQ11iN2ZCEbu4hAtI5gxFHTsvzMWl?usp=sharing) que trabajan en nuestra VM
