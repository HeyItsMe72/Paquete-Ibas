# Paquete-Ibas
 ![HTML5](https://img.shields.io/badge/HTML-orange?style=flat&logo=html5&logoColor=white) ![Static Badge](https://img.shields.io/badge/BOOTSTRAP-purple?style=flat&logo=bootstrap&logoColor=white)
 ![CSS3](https://img.shields.io/badge/CSS-blue?style=flat&logo=CSS3&logoColor=WHITE)
 
![TYPE](https://img.shields.io/badge/Proyecto%20de%20Maquetacion-pink?style=for-the-badge&color=BLUE)![Multipage](https://img.shields.io/badge/Multip%C3%A1gina-pink?style=for-the-badge)

![Responsive](https://img.shields.io/badge/Responsive%20Site%20-green?label=100%25&labelColor=%23336600&color=orange)





![image](https://github.com/HeyItsMe72/Paquete-Ibas/assets/124311622/d4e2296c-5d3d-43d6-8795-bdac4c9c8890)

### **Introducción**
*Paquete Ibas* es un proyecto de maquetación realizado a fin de practicar y aprender a manejar la librería de **bootstrap**. 
Se trata de un sitio web multipágina para una paquetería, cada subpágina mantiene su barra de navegación (con scroll espía) y footer, que muestra las redes sociales del sitio en íconos.

**NOTA:** Es importante destacar que este archivo no contiene funcionalidades javascript propias, todos los *modals* y demás funcionalidades que incluyan el uso de esta tecnología, son proporcionadas por bootstrap.

#### **CSS**
Toda la maquetación realizada, adicionada a los estilos son parte de esta tecnología, que permite realizar los componentes de forma más rápida. Por su parte, el archivo styles.css permite resetear algunos estilos y modificar los de bootstrap, como colores de fondo, la fuente, el color, etc. Además de agregar los keyframes utilizados, en este caso, girar el logo de la página; también se incluyen las medias-queries, en este caso son explícitamente para cambiar los tamaños de las fuentes y algunas imágenes, ya que bootstrap es una tecnología que nos permite manejar la responsabilidad de los elementos desde su maquetación por medio de las clases que indican los tamaños en relación al ancho del dispositivo que visita el sitio. 

### **Secciones**
En el diseño y desarrollo de este sitio se encuentran en la barra de navegación superior 6 subpáginas en las que se pueden navegar: 
- Inicio (index.html)
- Tracking (buscador.html)
- Enviar (enviar.html)
- Conócenos (nosotros.html)
- Clientes (clientes.html)
- Log In (login.html)

#### **Inicio _index.html_**
Incluye al inicio de la página un buscador que permitiría al usuario dar seguimiento a la ruta y ubicación de sus paquetes envías ingresando el número de guía. Para más detalles sobre esta parte del inicio, revisar la sección *Tracking*. 
Seguido a esto se invluye la sección *CONOCENOS* (independiente de la página *Cónocenos* que se muestra en la barra de navegación), en la que se muestra una breve introducción a la historia de la paquetería, su visión y misión. 

Dando uso al componente *Cards* (de bootstrap) se explica a grandes rasgos el proceso de envío, cada tarejta incluye un botón que redirije a la sección correspondiente de la página *Enviar*, además de ser utilizadas en la sección *Oferta* en la que se explica lo que se le ofrece al cliente. 

Para dar estructura a esta página, todas las secciones en este *inicio.html* fue hecho utilizando el layout *Columns* propio de bootstrap.

#### **Tracking _buscador.html_**
La página del buscador incluye únicadmente el header, mostrando el nombre de la página y el buscador (al igual que la primera sección de *Inicio*). El buscador permite al usuario dar seguimiento a sus envíos ingresando el número de guía; al dar click en *Rastrear* se muestra un modal en el que se mostraría la información del número de guía.

#### **Enviar _enviar.html_**
La página de *Enviar* se divide en diferentes secciones. Al inicio de la página se muestran los pasos generales para generar un envío, cada botón es un enlace que lleva al usuario a la sección correspondiente de esta página. 
La sección *Tarifas y tiempos de entrega* muestra un par de inputs que permiten al usuario ingresar su información. Por el momento, el botón de *Calcular* no muestra ninguna función. 
En la sección de *Ubica nuestros centros* se da uso a los *iframe* permitiendo mostrar la ubicación (por ahora random) utilizando google maps. Además, se utiliza texto que incita al usuario a participar en las encuestas de mejoras tanto para el sitio web como para el *proyecto* en general. 
A continuación, la sección *Programar una recolección* muestra un formulario que permite al usuario agendar una recolección, en este caso y por mera funcionalidad, al *agendar* una recolección se envía un correo electrónico. Para esta parte se hizo uso del API de formsubmit, en este caso el email con toda la información proporcionada es enviado al correo que está asinado en el atributo "action" del form. Para más información sobre cómo utilizar esta API se puede visitar: [FormSubmit](https://formsubmit.co/).

Para dar estructura a esta página, todas las secciones en este *enviar.html* fue hecho utilizando el layout *Columns* propio de bootstrap.

#### **Conócenos _nosotros.html_**
Esta página permite al usuario conocer más acerca del proyecto; utilizando *Columnas* propias de bootstrap, se dan estilos a cada sección de información de forma que se permita dar una imagen de bakcground además de una capa de opacidad que permita reducir la claridad de la imagen de fondo. Todos los estilos y estructura de cada página utiliza componentes de bootstrap. Los botones y links en esta sección dan un redireccionamiento del usuario hacia la página correspondiente. 

Además, se agrega un carusel de imágenes en el que se mostrarían las evaluaciones del servicio que proporcionan los clientes.

#### **Clientes _clientes.html_**
En esta sección se muestran tarjetas de diferentes tamaños (ordenador) que muestran una imagen con una cortina de opacidad rosa en la que se muestra un "cliente", en este caso son sitios de compras en línea, cuyo enlace llevará al usuario al sitio oficial del "cliente". El botón *Quiero ser cliente* redirecciona al usuario a la página de *Log In*. 

#### **Log In**
Esta página muestra un pequeño formulario de dos columnas que permitirán al usuario acceder a su cuenta (cuando exista tecnología backend) y que pueda encontrar su información personalizada, envíos y entregas realizadas, atención personalizada, etc. Este formulario fue también creado como un componente de bootstrap. 

## **Mejoras**

![Tracking](https://img.shields.io/badge/Tracking%20-red?style=for-the-badge&label=%C3%81reas%20de%20oportunidad&labelColor=yellow)

Claro que al ser un proyecto único de maquetación, no existe una base de datos ni tecnología backend que permita dar información al cliente acerca del ratreo de su paquete y aunque esta es un área de oportunidad bastante grande, queda fuera del objetivo del proyecto y del campo front-end (aunque se espera implementarlo pronto). 
Un área de oportunidad a corto plazo identificada es validar con regex el contenido de la guía ingresada en el input, además de verificar que exista un dato ingresado antes de que el submit pueda ser generado. 

![Static Badge](https://img.shields.io/badge/Enviar-red?style=for-the-badge&label=%C3%81reas%20de%20oportunidad&labelColor=yellow)

Existen grandes mejoras a corto y largo plazo para este proyecto, sobre todo en la sección de envíos. 
Comenzamos por la parte de *Tarifas y tiempos de envío* en el que recomiendo que los inputs sean de tipo select, reduciendo los errores al dar lectura al valor del input cuando se tenga la tecnología backend para manipular la información. Esto permitirá también darle la funcionalidad correspondiente al botón *Calcular* mostrándole al usuario las cotizaciones correspondientes, ya sea en un modal, en una redirección o en la inserción de información en la misma página. 

La sección de *Programar una recolección* también es bastante mejorable, también se recomienda en un inicio, validar la información que es ingresada en el formulario, de acuerdo a lo que debería ser llenado cada input. También, aunque por ahora se da uso a un API (que en realidad es bastante eficiente) simplemente se hace un envío email, pero a largo plazo, debería añadirse tecnología backend que permita generar un registro de las recolecciones programadas, aunque eso sea un área de oportunidad fuera del entorno frontend. 

## **Funcionalidades**
En general, no existe gran explicación para la funcionalidades, ya que todos los componentes utilizados son brindados por la librería de bootstrap, eso incluye todo lo que pueda necesitar programación en javascript. Para obtener mayor información de su uso, cómo comenzar y cómo maquetar, se puede visitar [Bootstrap](https://getbootstrap.com/).


Los íconos utilizados pueden ser encontrados en: [Flaticon](https://www.flaticon.com/)
