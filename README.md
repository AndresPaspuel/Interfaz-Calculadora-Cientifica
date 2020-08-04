1.PLANTEAMIENTO DEL PROBLEMA

NODO RED.

Cómo avanza el tiempo la tecnología crece de una manera inmensa y por ello van saliendo diferentes tipos de programación  como por  ejemplo en este caso NODE-RED  maneja una programación mediante flujos por eso es necesario nosotros como futuros ingenieros en TICS  ir teniendo  los conocimientos adecuados  para ser unos buenos 
profesionales .

Calculadora Científica

Construir una calculadora científica utilizando un  lenguaje de programación   Python  mediante la librería  MATH que desarrolle operaciones básica y científicas .


2. OBJETIVOS

OBJETIVO GENERAL 

NODE-RED

Analizar  e interactuar la página de Node-Red  como un lenguaje de herramientas basado en flujos  para implementar una interfaz  hombre-máquina.

Calculadora Científica

Implementar lo aprendido de Programación en Python  desarrollando un ejemplo de una Calculadora  donde desarrolle operaciones  con  una Librería Específica  utilizando una Pagina de  Programacion llamada withcode.uk donde simularemos con los puertos de la  Raspberry Pi.


OBJETIVOS ESPECÍFICOS 

Node-Red

-Identificar los parámetros y su funcionalidad de Node -Red  para tener conocimiento de otro nuevo lenguaje de programación mediante Flujos .


Diseñar un programa  o ejemplo en NODE-RED que implemente una interfaz HMI (Interfaz Humano Máquina)

Calculadora Científica

-Implementar los conocimientos adquiridos en las clases para realizar una calculadora científica desarrollada en https://create.withcode.uk/ mediante entradas GPIO.


-Implementar la librería MATH  para desarrollar la calculadora 

3.ESTADO DEL ARTE

NODE-RED

Anoja Rajalakshmi y Hamid Shahnasser en el año 2017 en California se realizó una investigación que era sobre el Internet de las cosas usando Node-Red y Alexa, cuyo objetivo  era la mejora hasta qué punto IoT puede conectar dispositivos en diferentes plataformas.los resultados obtenidos son que el proyecto proporciona la elasticidad de alterar el proceso de responder a un evento. Como ejemplo, permite al usuario cambiar una notificación de enviar un correo electrónico a un SMS o activar fuera de la luz para reducir el brillo, además de que con la ayuda de node red la tarea se facilita.


Salas Cifuentes, Eduardo arturo, Santana Hidalgo y Sergio Ricardo en el año 2019 en la ciudad de Guayaquil se realizó una investigación sobre Implementación de un sistema con interfaz HMI para la adquisición de datos en pruebas de transformadores que pretende que el sistema obtenga datos en la menor cantidad de tiempo y procesarlos de mejor manera y sus resultados fueron de que con la interfaz HMI fue de gran ayuda en recolección de datos en circuitos abiertos


Rachid Benhamadi, Mounir Bouhedda, Billel Bengherbia, Hamza Benyezza y Omar Benzineb en el año 2019 en Argelia se realizó un trabajo que consiste en el diseño y la realización de un sistema de monitoreo y control del centro de transmisión basado en Internet de las cosas (IoT) como resultado se obtiene que  se valida con un prototipo realizado donde la supervisión y el control se realizan utilizando una Interfaz hombre-máquina (HMI) diseñada bajo Node-Red de IBM.

Calculadora Científica


Sergio Rojas, Héctor Fernandez y Juan Ruiz en el año 2016 en la ciudad de Caracas se hizo un artículo sobre Aprendiendo a programar en python, entonces los que plantea es que hay adquirir las destrezas que sean suficientes para escribir programas de fácil mantenimiento y de eficiencia razonable.


Gabriel Via Echezarreta en el año 2017 en la ciudad de Santander realizó un trabajo que es: Entorno de desarrollo para la realización de prácticas de sistemas empotrados basado en Raspberry Pi, en este proyecto es la creación de una librería que sirva de interfaz para el desarrollo de aplicaciones que hagan uso del Explorer Phat, y como resultados se obtuvo Mejora del entorno de desarrollo, Librería phat.h: y Explorer Phat. 


Valiente Lerma, Arturo José en el año 2017 en la ciudad de Valencia se realizó un trabajo que consiste en una  Alarma para el hogar basada en Raspberry Pi. cuyos resultado fueron conseguir integrar todos los dispositivos de entrada y salida que se han propuesto en la parte de hardware utilizado, además de conseguir implantar un sistema de seguridad para evitar que toda persona ajena pueda controlar nuestra alarma.


4.MARCO TEÓRICO

NODE-RED


Según (Lekić & Gardašević, 2018), Node-RED es una herramienta de desarrollo basada en flujo de código abierto para la integración de dispositivos de hardware IoT, API(interfaces de programación de aplicaciones) y servicios en línea desarrollados por IBM.

Node-RED es una herramienta gratuita basada en JavaScript, construida en la plataforma Node.js que proporciona un editor visual de flujo basado en un navegador. El sistema contiene nodos que están representados por los iconos apropiados. Y funciona de dos maneras: arrastrar, soltar y conectar nodos, o importar código JavaScript.

El nodo proporciona diferentes funciones, como monitorear el flujo como depurar nodo, o para leer y escribir con pines GPIO de Raspberry Pi, Los flujos creados se almacenan utilizando JSON (Notación de objetos JavaScript). Node-Red Permite a los desarrolladores conectarse a la entrada y salida además de procesar nodos para crear flujos para el procesamiento de datos, controlar cosas o enviar alertas funciona con el principio de permitir la conexión de servicios web o personalizar nodos entre sí o con otras cosas, para realizar funciones como enviar datos de sensores por correo electrónico o servicios como el de realizar análisis complejos.


Node-RED contiene tres componentes básicos:


  Panel de nodos. -    Panel de flujos  -  Panel de información y depuración.
  
  
  ![image](https://user-images.githubusercontent.com/66221550/89250662-dddc2380-d5da-11ea-96cd-d9ac630fa1cb.png)



Node-RED es una herramienta poderosa y flexible que se utiliza para crear prototipos, siendo la esencia de esta herramienta permitir a los ingenieros y técnicos simplemente crear y configurar aplicaciones en tiempo real en dispositivos finales.


Además, (Coen-Porisini, 2018) propone que Node-RED es una herramienta de programación basada en flujos y basada en eventos que pueden comunicarse entre sí y regular el flujo de la información dentro del sistema diseñado. Es una representación visual basada en el navegador ayudando a los desarrolladores a comprender mejor las interacciones que ocurren dentro de toda la red IoT interactuando con entidades tanto de hardware como Sensores y de software como servicios, de igual manera destaca sobre la interfaz que nos brinda Node-RED además de permitir la integración de diferentes tecnologías como:


MongoDB: que es un motor de base de datos no relacional debido a que su mayor eficiencia en responder en muy poco tiempo


Java: es utilizado aquí debido a su amplia adopción en implementaciones reales.


Transporte de telemetría de la cola de mensajes (MQTT): se utiliza como un método ligero de publicación y suscripción para compartir información y notificaciones del sistema además de controlar el flujo de datos que proporciona la lógica de las aplicaciones IoT. 


Según (Rossum, 1995) Python es un lenguaje de programación simple pero potente e interpretado diferente a la programación en C y Shell ideal para la programación desechable y la creación rápida de prototipos. Su sintaxis se elabora a partir de construcciones tomadas de una variedad de otros idiomas, el intérprete de Python se amplía fácilmente con nuevas funciones y tipos de datos implementados en C. Python de igual manera es adecuado como un lenguaje de extensión para aplicaciones C altamente personalizables para varios sistemas operativos como por ejemplos UNIX (incluido Linux), el sistema operativo Apple Macintosh, MSDOS describiéndolo a esta sintaxis y la semántica central del lenguaje como consiso pero intenta ser exacto y completo.

De igual manera (Duque, 2009) argumenta que Python es un lenguaje de programación creado por Guido Van Rossum a principios de los años 90 cuyo nombre está inspirado en el grupo de cómicos ingleses “Monty Python”. Es un lenguaje similar a Perl, pero con una sintaxis muy limpia y que favorece un código legible.


Se trata de un lenguaje interpretado o de script, con tipiado dinámico, fuertemente tipiado, multiplataforma y orientado a objetos.


La ventaja de los lenguajes compilados es que su ejecución es más rápida. Sin embargo, los lenguajes interpretados son más flexibles y más portables. Python tiene, no obstante, muchas de las características de los lenguajes compilados, por lo que se podría decir que es semi interpretado. En Python, como en Java y muchos otros lenguajes, el código fuente se traduce a un pseudo código máquina intermedio llamado bytecode la primera vez que se ejecuta, generando archivos .pyc o .pyo (bytecode optimizado), que son los que se ejecutarán en sucesivas ocasiones.


Tipado dinámico

La característica de tipado dinámico se refiere a que no es necesario declarar el tipo de dato que va a contener una determinada variable, sino que su tipo se determinará en tiempo de ejecución según el tipo del valor al que se asigne, y el tipo de esta variable puede cambiar si se le asigna un valor de otro tipo.


Orientado a objetos


>>> import RPi.GPIO as GPIO #importa la librería de GPIO

#usar número de terminal no de GPIO


La orientación a objetos es un paradigma de programación en el que los conceptos del mundo real relevantes para nuestro problema se trasladan a clases y objetos en nuestro programa. La ejecución del programa consiste en una serie de interacciones entre los objetos. Python también permite la programación imperativa, programación funcional y programación orientada a aspectos.


Python es un lenguaje que todo el mundo debería conocer. Su sintaxis simple, clara y sencilla; el tipado dinámico, el gestor de memoria, la gran cantidad de librerías disponibles y la potencia del lenguaje, entre otros, hacen que desarrollar una aplicación en Python sea sencillo


Raspberry Pi


Según (Aguilar, 2014) la Raspberry Pi es una computadora en una sola tarjeta (Single-Board Computer) creada por la Raspberry Pi Foundation para promover la enseñanza de la programación en escuelas y países en desarrollo.


Biblioteca para acceso a GPIO


>>> import RPi.GPIO as GPIO #importa la librería de GPIO

#usar número de terminal no de GPIO

>>>GPIO.setmode(GPIO.BOARD)


 
