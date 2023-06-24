## Celeste Anahí Menéndez Lima 
##  7690 19 3986 

#  _Chatbot de e-commerce_

##### Para la creación de nuesto Chatbot, las tecnologias que utilizamos fueron las siguientes: 
* Dialogflow
* Postimage
* Telegram 

### DialogFlow: 

Dialogflow es una plataforma que nos permite crear chatbots o bots conversacionales y que pertenece a Google desde su compra en septiembre del 2016. Se trata de una herramienta de creación de chatbots capaz de comprender el lenguaje natural, y que provee la infraestructura adecuada para recrear conversaciones y construir diálogos con el fin de interactuar con el usuario de manera fluida.
Para comprender una parte del potencial de esta herramienta, a continuación vamos a crear un chatbot básico para pedir un delivery en un restaurante de comida rápida. Pero primero, veamos algunos conceptos para entender cómo implementarlo.

*Intenciones  (Intents):* Son los objetivos o intenciones que tiene nuestro usuario al hablar con el chatbot. Se pueden simplificar en las frases que el usuario escribirá en el chat para conseguir su objetivo. En nuestro caso “Quiero hacer un pedido”.

*Entidades  (Entities):* Son los datos que queremos conseguir del usuario o con los que realizaremos ciertas acciones. Estos datos se pueden grabar para posteriores conversaciones. Por ejemplo, “la carta” y “el tipo de pan” que desea.

*Contexto (Context):* Se utiliza para guardar información entre intentos para poder hacer un lenguaje más natural. Castillo [-@castillo2020]. 

### Postimage: 

Postimage es un práctico servicio para almacenar y compartir fotos gratis y online.
La utilidad de esta plataforma es más que evidente, un lugar donde almacenar nuestras fotografías e imágenes fácilmente.
Una vez cargadas nuestras imágenes, tenemos la posibilidad de compartirlas en Internet, redes sociales, correo electrónico, etc.
También podemos insertarlas en nuestros blogs y páginas web, incluso en foros y otros servicios.
Lo más interesante es que Postimage es un servicio de uso gratuito y en el que el registro no es obligatorio.
El sitio está disponible en español y su uso es realmente sencillo, lo que no impide que nos permite realizar algunos ajustes interesantes. Bermudez [-@bermudez2020]

### Telegram:

Es una aplicación de mensajería enfocada en la velocidad y seguridad, es súper rápida, simple y gratuita. Puedes usar Telegram en todos tus dispositivos al mismo tiempo. Tus mensajes se sincronizan a la perfección a través de cualquiera de tus teléfonos, tablets o computadoras. Telegram tiene más de 700 millones de usuarios activos mensuales y es una de las 10 apps más descargadas del mundo.

Telegram es para los que quieran velocidad y fiabilidad en sus mensajes y llamadas. A los usuarios del mundo de los negocios y a los equipos pequeños les pueden gustar los grupos grandes, los nombres de usuario, las aplicaciones para computadora y las poderosas opciones para compartir archivos.

Como Telegram permite tener hasta 200.000 miembros por grupo, tiene respuestas, menciones y hashtags, que ayudan a mantener el orden y la eficiencia en la comunicación para las comunidades grandes. Puedes nombrar administradores con herramientas avanzadas para que te ayuden a mantener la paz y la prosperidad en estas comunidades. Los grupos públicos permiten a cualquiera unirse a ellos y son plataformas poderosas para debatir y recopilar feedback.  Telegram [-@Telegram2023] concluyo. 

#### Comó Iniciamos nuestro Chatbot:

1. Nos fuimos a la pagina oficial de Dialogflow y realizamos el inicio de sesion: 

    * [![Inicio-Primera-Imagen.jpg](https://i.postimg.cc/ryNBrCn9/Inicio-Primera-Imagen.jpg)](https://postimg.cc/WttYRrPD)
    
2. Nos ingresa a la consola y nos vamos al siguiente apartado marcado en amarillo

   * [![Crear-Segunda.jpg](https://i.postimg.cc/nV7nXDBF/Crear-Segunda.jpg)](https://postimg.cc/9zW6SzLK)

3. Ingresamos a la siguiente ventana y nos abre el proyecto completo:

  * [![Proyecto-tercera.jpg](https://i.postimg.cc/W1mDgyZ4/Proyecto-tercera.jpg)](https://postimg.cc/zyBX100m)

4. Agregamos nuestras intenciones, que son las respuestas de nuestro chatbot. 

  * [![Cuarta.jpg](https://i.postimg.cc/rFB9TBJf/Cuarta.jpg)](https://postimg.cc/Xpg5cDt5)
  * [![Quinta.jpg](https://i.postimg.cc/vTDv8MkN/Quinta.jpg)](https://postimg.cc/PvsD2GtW)

Acá podemos observar el menú de opciones de Bienvenida

  * [![Bienvida.jpg](https://i.postimg.cc/PNns16WT/Bienvida.jpg)](https://postimg.cc/301cTFfc)

El menú de opciones del catálogo de nuestra tienda:
   
   * [![Menu-de-opciones-Catalogo.jpg](https://i.postimg.cc/brF31d1P/Menu-de-opciones-Catalogo.jpg)](https://postimg.cc/sG7YrjnH)
 

4. En estas podemos observar toda la configuración que se realizaron para poder agregar las imagenes a nuestro chatbot. como lo indicamos al principio del documento el programa que utilizamos fue: 

   * [![Postgres.jpg](https://i.postimg.cc/66gH6jL1/Postgres.jpg)](https://postimg.cc/LhkkNVWz)

Acá subimos cada una de las imágenes que se cargaron a nuestro chat en Dialogflow:

   * [![imagenes.jpg](https://i.postimg.cc/QdygSV4Y/imagenes.jpg)](https://postimg.cc/nXqQhVtq)

luego ya se da guardar y los cambios quedaron. 

#### Conectar Dialogflow: con Telegram 

1. Primero ir a Telegram y buscar el siguiente chat, para crear nuestro chatbot 
  
    * [![Whats-App-Image-2023-06-24-at-00-27-02.jpg](https://i.postimg.cc/vTn9PvK0/Whats-App-Image-2023-06-24-at-00-27-02.jpg)](https://postimg.cc/XBVpq945)

2. Ingresar al Chat y empezar la creación como se muestra en las siguientes imagenes. 
    * [![Whats-App-Image-2023-06-24-at-00-10-17.jpg](https://i.postimg.cc/fLrjqyRR/Whats-App-Image-2023-06-24-at-00-10-17.jpg)](https://postimg.cc/WF0kh2ZB) [![Whats-App-Image-2023-06-24-at-00-10-17-1.jpg](https://i.postimg.cc/mk13v4PN/Whats-App-Image-2023-06-24-at-00-10-17-1.jpg)](https://postimg.cc/zH5Rh9SV) 
 
  En esta parte nos genera un Token el cuál es el que nos servira para conectar con Dialogflow.
   
  * [![Whats-App-Image-2023-06-24-at-00-10-17-2.jpg](https://i.postimg.cc/6TsVwPRs/Whats-App-Image-2023-06-24-at-00-10-17-2.jpg)](https://postimg.cc/gLDLHNN4) 

3. Al tener el Token nos vamos al apartado de Dialogflow y le damos click a la siguiente ventana: 
  
  * [![Integraciones.jpg](https://i.postimg.cc/DyBj1vqm/Integraciones.jpg)](https://postimg.cc/YhLzHwDw) 
 
Acá nos vamos a la tecnologia a la que queremos intregrar en este caso es Telegram: 

  * [![Telegram.jpg](https://i.postimg.cc/Bnjr6LdJ/Telegram.jpg)](https://postimg.cc/sMR6HXjL) 

* En esta parte se agrega el token que nos proporcionaron en telegram para la creación de nuestro bot y se conecté. Se le da  en Comenzar y automáticamente se incia. Si lo queremos apagar solo le damos en detener como se muestra en la imagen. 

  * [![integracion.jpg](https://i.postimg.cc/TYN8fqNk/integracion.jpg)](https://postimg.cc/LnPQVfpf) 
4. Nos vamos a Telegram y buscamos Nuestro ChatBot con nombre MODAONLINE (Modaonline)

  * [![Whats-App-Image-2023-06-24-at-00-41-53.jpg](https://i.postimg.cc/8P63gQWC/Whats-App-Image-2023-06-24-at-00-41-53.jpg)](https://postimg.cc/WhsS0y5R)

5. Ingresamos y le colocamos Hola para que inicie el chat. 

 * [![Whats-App-Image-2023-06-24-at-00-44-12.jpg](https://i.postimg.cc/GtKvZjrr/Whats-App-Image-2023-06-24-at-00-44-12.jpg)](https://postimg.cc/p599jzp1)
 
6. Luego le damos en catálogo y nos despliega las categorías: 

  * [![Whats-App-Image-2023-06-24-at-00-48-25.jpg](https://i.postimg.cc/NFB1Jz3p/Whats-App-Image-2023-06-24-at-00-48-25.jpg)](https://postimg.cc/R6p6qXVH) 

7. Le damos en cualquiera de las categorías y nos muestra el precio y la imagen de la prenda. 

  * [![Whats-App-Image-2023-06-24-at-00-48-26.jpg](https://i.postimg.cc/KznP52H1/Whats-App-Image-2023-06-24-at-00-48-26.jpg)](https://postimg.cc/47xHJrZG) [![Whats-App-Image-2023-06-24-at-00-48-26-1.jpg](https://i.postimg.cc/G20PY2q0/Whats-App-Image-2023-06-24-at-00-48-26-1.jpg)](https://postimg.cc/cKm8GdpT) [![Whats-App-Image-2023-06-24-at-00-48-26-2.jpg](https://i.postimg.cc/CKnHzDCH/Whats-App-Image-2023-06-24-at-00-48-26-2.jpg)](https://postimg.cc/VS1bhJVd) 

Asi es como realice mi proyecto, por temas de tiempo no pude realizar la base de datos para que se almacenaran los productos. 



