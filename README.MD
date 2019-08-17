## QUE SON LOS SISTEMAS EMPRESARIALES?
*Es una Alternativa para organizar mejor un negocio*

Según la definición de la RAE, un sistema es un conjunto de reglas, principios o cosas que relacionadas y ordenadas entre sí, ayudan a lograr un objetivo determinado. De acuerdo con esto, un sistema empresarial está compuesto por diferentes piezas o funcionalidades que sirven para desarrollar tareas específicas de acuerdo con su especialidad, y que unidas facilitan las labores administrativas de un negocio. Hablar de este sistema empresarial es hablar de un software administrativo, un programa informático diseñado para facilitar las gestiones operativas y gerenciales.
Estos sistemas empresariales han ido evolucionando con el tiempo integrando así nuevas funciones adaptándose a las dinámicas de ventas actuales, automatizando procesos, migrando a la nube, y así eliminar la necesidad de instalarse en un equipo.
## CARACTERISTICAS MAS IMPORTANTES DE UNA APLICACION EMPRESARIAL
- **Plataforma tecnológica**: Es importante considerar dónde se va a ejecutar nuestra aplicación, si en un servidor nuestro o de terceros, sobre qué sistema operativo, con cuáles bases de datos necesita relacionarse y qué lenguaje es el que nos conviene. Este primer punto tiene un abanico muy amplio, ya cada opción nos lleva a tomar decisiones que dictarán los resultados futuros de la aplicación.
- **Flexibilidad**: Debemos tener en claro que, a nivel tecnológico –usando palabras de Heráclito– lo único constante es el cambio. Por ello, debemos considerar que la decisión que tomemos en este momento respecto a la plataforma, bases de datos, sistema operativo y demás debe poder acompasarse a los cambios de tecnología que el mercado nos impone.
- **Escalabilidad**: La alta disponibilidad es fundamental para una aplicación de misión crítica, ya que no podemos permitirnos malos tiempos de respuesta, o peor aún, tiempos en los cuales la aplicación no funcione. En este punto en particular, las posibilidades que brinda el hardware son muy amplias, ya que en el pasado las aplicaciones residían en un servidor y las alternativas para incrementar su potencia conllevaban siempre un cambio de servidor. Pero hoy se tiene una mayor flexibilidad y potencia aumentando procesadores en un mismo servidor, con la posibilidad de tener redundancia para mejorar y garantizar el desempeño y funcionamiento de las aplicaciones.
- **Seguridad**: Con todos estos cambios en las TI, la seguridad se ha vuelto cada vez más importante, ya que dejamos de tener una red local totalmente controlada para estar expuestos al uso de internet, lo que hace que nuestras aplicaciones sean vulnerables a hackeos, pérdida de datos o robo de información. Nuestra aplicación debe de responder y respetar los más altos estándares de seguridad que existan en el mercado y mantenerse actualizada en forma permanente, ya que todos los días se están descubriendo vulnerabilidades de los sistemas.
- **Pruebas (Testing)**: Muy relacionado con los puntos anteriores, las pruebas de la aplicación son fundamentales en estos días que corren, ya que podemos detectar errores en etapas tempranas de desarrollo, lo mismo que vulnerabilidades o problemas de desempeño. Hoy el testing es una disciplina en sí misma en el departamento de informática, tal como lo son la seguridad y el desarrollo y administración de aplicaciones.

## CINCO INSTITUCIONES QUE REQUIEREN APLICACIONES DE MISION CRITICA
Las aplicaciones de misión crítica son aquellas aplicaciones que tienen un impacto muy importante en el funcionamiento de la organización o negocio y cuya falla traería efectos terribles. Ejemplo correo electrónico.
- Colegios
- Librerías
- Escuelas de conducción
- Gimnasios
- Centros de nivelación

Estas cinco instituciones que estan en nuestra sociedad requieren aplicaciones de mision critica debido a que no cuentan con ellas. Ya que en la actualidad es necesario esa interaccion con el usuario y/o cliente.
## DIFERENCIAS ENTRE LA ESCALABILIDAD HORIZONTAL Y ESCALABILIDAD VERTICAL
1. La escalabilidad vertical o hacia arriba, este es el más simple, pues significa ***crecer el hardware***
es decir aumentar el hardware por uno más potente, como disco duro, memoria, procesador, etc. pero también puede ser la migración completa del hardware por uno más potente.

2. El escalamiento horizontal es sin duda el más potente, pero también el más complicado. ***Este modelo implica tener varios servidores (conocidos como Nodos) trabajando como un todo.*** Se crea una red de servidores conocida como Cluster, con la finalidad de repartirse el trabajo entre todos nodos del cluster.

## SERVIDOR WEB Y SERVIDOR DE APLICACIONES
1. **Servidor web o Web Server**
	- Está diseñado para servir contenido HTTP. El servidor de aplicaciones también puede servir contenido HTTP, pero no se limita a solo HTTP. Se puede proporcionar otro soporte de protocolo como RMI / RPC.
	- Web Server está diseñado principalmente para servir contenido estático, aunque la mayoría de los servidores web tienen complementos para admitir lenguajes de script como Perl, PHP, ASP, JSP, etc., a través de los cuales estos servidores pueden generar contenido HTTP dinámico.
2. **Servidor de Aplicaiones**
	- La mayoría de los servidores de aplicaciones tienen Web Server como parte integral de ellos, lo que significa que App Server puede hacer lo que Web Server sea capaz de hacer. Además, el servidor de aplicaciones tiene componentes y características para admitir servicios de nivel de aplicación, como la agrupación de conexiones, la agrupación de objetos, el soporte de transacciones, los servicios de mensajería, etc.

## COMO FUNCIONA EL PROTOCOLO HTTP
*Protocolo http*
**Protocolo de transferencia de hipertexto**. Como cualquier otro protocolo establece la comunicación, y para eso los mensajes deben de ir formateados de cierta manera y sigan las reglas

En el **grafico** se ve el intercambio de mensajes entre el emisor y el receptor
El emisor hace una petición de tipo get hacia un receptor y el cual procesa la solicitud y envía un mensaje de respuesta von el código de estado 200 en este caso que significa que la petición fue llevada exitosamente.

![](https://1.bp.blogspot.com/-jmQUZD3X_3s/XVdrsLhkzOI/AAAAAAAAAcE/S41ON_3E5K4fsbFE_NYkNHYynsLQPLaXQCEwYBhgL/s320/primer%2Bgrafico.jpg)
## ELEMENTOS IMPORTANTES DE REQUEST EN HTTP
Los Elementos importantes en request:
- Método HTTP (HTTP Method): usualmente: GET, POST.
- Recurso al que se accede (URL)
- Parámetros del FORM
- 2010
- Lenguajes Visuales.

## ELEMENTOS IMPORTANTES DE RESPONSE EN HTTP
Los Elementos importantes en response:
- Código de estado (status code): Indica si la operación fue realizada correctamente o no.
- Tipo de contenido (Content Type): Si el contenido es HTML, una imagen, un archivo PDF, etc.
- Contenido: el HTML, la imagen, etc.
- 2010
- Lenguajes Visuales.

## LA ARQUITECTURA JAVA EE
**Java EE** proporciona una arquitectura multi-capa. La capa cliente puede estar constituida por aplicaciones Java de escritorio o navegadores HTML. Las capas proporcionadas por Java EE propiamente dicha son las capas Web (mediante las tecnologías Servlets, JSP y JSF) y las capas de Negocio (mediante tecnologías como EJB, JMS o Web Services). Por último, estas capas se comunican con una capa de datos (base de datos o aplicaciones y sistemas legacy).

![](https://1.bp.blogspot.com/-jjLugLMuPUQ/XVdrsKGmNZI/AAAAAAAAAcI/NmBb9ZVliyUbQ8GdAILZAkEEnxLBa3_DgCLcBGAs/s320/segundo%2Bgrafico.gif)

## CONTENEDORES, COMPONENTES Y SERVICIOS DE JAVA EE
*Java Platform, Enterprise Edition (Java EE)*

***COMPONENTES:***
- Clientes de aplicación y applets (en el cliente): Los clientes en Java EE son Clientes web: navegadores web, páginas web, applets, Aplicaciones de cliente
- Java Servlet, JavaServer Faces (JSF), and JavaServer Pages (JSP) (en el servidor) Java Servlets  Clases escritas en Java que procesan peticiones HTTP y construyen respuestas  JavaServer Pages (JSP)  Documentos basados en texto que contienen dos tipos de texto, una plantilla de datos estática que puede expresarse en un formato como (X)HTML o XML 
- Enterprise JavaBeans (EJB) (o enterprise beans) (en el servidor) 

Los componentes se despliegan y ejecutan en contenedores especializados 
- Ejemplos de contenedores: 
- Contenedor de applets en un navegador Web 
- Contenedor Web Tomcat 
- Contenedor de EJBs

***CONTENEDORES:***
- Un contenedor es un proceso donde se ejecutan los componentes
	1. Gestiona los componentes de la aplicación
		- Ciclo de vida
	2. Proporciona acceso a servicios de la plataforma
		- Seguridad, transacciones, persistencia, conectividad, etc

***SERVICIOS:***
- Cada contenedor Java EE proporciona servicios a los componentes
- Java Naming Direct Interface (JNDI)
- Java Persistence API (JPA)
- Java Database Connectivity API (JDBC)
- Java Transaction API (JTA)
- Java Message Service (JMS)
- JavaMail
- Java Beans Active Framework (JAF)
- Java EE Connector Arquitecture
- Java Authentication and Authorization Service (JAAS)
- Java API for XML Procesing (JAXP)
- SOAP with Attachments API for Java (SAAJ)
- Servicios Web (JAX-WS)
- Java API for RESTful Web Services (JAX-RS)

## METODOS MAS UTILIZADOS EN HttpServlet, HttpServletRequest y HttpServletResponse

***METODO MAS UTILIZADO EN LA CLASE HttpServlet***
- Cualquier clase que implemente la interfaz javax.servlet.Servlet
	- Métodos para gestionar el ciclo de vida del servlet
- También suele ser necesaria la interfaz javax.servlet.ServletConfig
	- Tiene los parámetros de arranque e inicialización para el servlet que le pasa el contenedor 
- Normalmente los servlets se implementan a partir de una de las dos subclases siguientes que implementan ambas interfaces:
	- javax.servlet.GenericServlet
		- Clase que define un servlet independiente del protocolo
	- javax.servlet.http.HttpServlet
		- Para servlets en aplicaciones web, que procesan las peticiones con el protocolo HTTP.

***METODO MAS UTILIZADO EN LA CLASE HttpServletRequest y HttpServletResponse***
*Métodos de la interfaz javax.servlet.Servlet*
1. service(ServletRequest request, ServletResponse response)
	- Cada vez que se invoca un servicio al servlet
	- Dependiendo del tipo de servicio, invoca el método correspondiente al servicio solicitado
	- Normalmente no se reescribe este método, solo los correspondientes a los servicios específicos
	- Pueden invocarse concurrentemente los métodos de servicio, por ello deben ser thread safe
2. También otros usados son:
	- doGet(HttpServletRequest request, HttpServletResponse response) 
	- doPost(HttpServletRequest request, HttpServletResponse response)

![](https://1.bp.blogspot.com/--Ozg8zqDKOU/XVdrzhdmWKI/AAAAAAAAAcM/7mQXMzWO_eIyiWj_3YJvTKNsenFciXpgwCLcBGAs/s320/tercer%2Bgrafico.png)
