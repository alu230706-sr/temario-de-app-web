 # temario-de-app-web

### **Propósito de Aprendizaje 1: Comprender los fundamentos del desarrollo de aplicaciones web.**

## ***1.-Introducción al desarrollo web***

El desarrollo web es el proceso de crear sitios y aplicaciones que funcionan en Internet. Comenzó en los años 90 con páginas muy simples hechas solo con HTML. Poco a poco, se añadieron nuevas tecnologías como CSS (para estilos) y JavaScript (para hacer las páginas interactivas). Más adelante, aparecieron los sitios dinámicos, capaces de mostrar información diferente según el usuario o la situación. Hoy en día, el desarrollo web incluye aplicaciones complejas que funcionan como programas instalados en el ordenador o el móvil.

**Tipos de aplicaciones web**

Estáticas:
Son páginas que siempre muestran lo mismo. No cambian su contenido según quien las visite. Ejemplo: una página con información de contacto.

Dinámicas:
Cambian su contenido según el usuario o las acciones que realiza. Ejemplo: una tienda online que muestra diferentes productos.

SPA (Single Page Application):
Son aplicaciones que cargan una sola página y, al navegar, no recargan toda la web, solo cambian partes específicas. Ejemplo: Gmail.

PWA (Progressive Web App):
Son aplicaciones web que pueden instalarse en el móvil y funcionar incluso sin conexión a Internet, como si fueran aplicaciones nativas. Ejemplo: Twitter Lite.



### ***2.Arquitectura de aplicaciones web***
La arquitectura de una aplicación web describe cómo se distribuyen y comunican sus diferentes componentes para funcionar correctamente. Esto facilita el desarrollo, la escalabilidad y el mantenimiento de las aplicaciones.

Cliente-Servidor
Es el modelo más común en aplicaciones web.
El cliente es el navegador o la app que usa el usuario para interactuar con la aplicación (por ejemplo, Chrome, Firefox).
El servidor es donde reside la lógica, los datos y el procesamiento de la aplicación.
El cliente hace peticiones (requests) al servidor y recibe respuestas (responses), normalmente a través de Internet.
Ejemplo: Cuando buscas algo en Google, tu navegador (cliente) envía la búsqueda al servidor de Google, que responde con los resultados.
Arquitectura de tres capas
Presentación (Frontend):

Es la parte visible para el usuario.
Incluye todo lo que ves y con lo que interactúas (botones, formularios, menús).
Se desarrolla usando tecnologías como HTML, CSS y JavaScript.
Lógica (Backend):

Es el cerebro de la aplicación.
Procesa las acciones del usuario, gestiona reglas de negocio y controla el flujo de información.
Se desarrolla con lenguajes como Python, Java, Node.js, etc.
Datos (Base de datos):

Es donde se almacenan, consultan y modifican los datos.
Ejemplo: información de usuarios, productos, mensajes, etc.
Se usan sistemas como MySQL, PostgreSQL, MongoDB.

**REST y API-first design
REST (Representational State Transfer):**

Es un estilo de arquitectura para diseñar servicios web (APIs).
Permite que diferentes sistemas (web, móvil, otros servidores) se comuniquen de manera sencilla usando el protocolo HTTP.
Se basa en recursos (por ejemplo, usuarios, productos) y operaciones estándar: GET, POST, PUT, DELETE.
Ejemplo: Una app móvil puede consultar una lista de productos a través de una API REST.
API-first design:

Significa que el desarrollo comienza definiendo primero las APIs (cómo se comunican los sistemas).
Esto permite que varios equipos (frontend, backend, móvil) trabajen en paralelo y tengan claro cómo interactuar con la aplicación.
Facilita la integración con otros servicios y sistemas desde el inicio.

### ***3. -Lenguajes y tecnologías fundamentales***

**HTML (HyperText Markup Language)**

Es el lenguaje principal para crear la estructura de una página web.
Define elementos como títulos, párrafos, imágenes, enlaces, tablas, etc.
Todo sitio web comienza con HTML; es la base sobre la que se construyen los demás componentes.

**CSS (Cascading Style Sheets)**

Es el lenguaje que se utiliza para dar estilo y diseño a las páginas HTML.
Permite cambiar colores, fuentes, tamaños, posiciones, crear diseños adaptativos y animaciones.
Gracias a CSS, las páginas web pueden ser visualmente atractivas y responder a diferentes tamaños de pantalla (responsive design).

**JavaScript**

Es el lenguaje de programación que hace que las páginas web sean interactivas.
Permite reaccionar a acciones del usuario (como clics, formularios, desplazamientos), modificar el contenido sin recargar la página y crear efectos dinámicos.
Se ejecuta en el navegador del usuario y es esencial para aplicaciones modernas como SPA.

**PHP**

Es un lenguaje de programación que se ejecuta en el servidor.
Permite crear páginas y aplicaciones web dinámicas, gestionar sesiones, procesar formularios y conectarse a bases de datos.
Muy usado en sistemas de gestión de contenidos como WordPress y en el backend de muchas páginas.

**MySQL**

Es un sistema de gestión de bases de datos relacional, muy popular y ampliamente usado en proyectos web.
Permite almacenar, organizar y acceder a grandes volúmenes de datos de forma eficiente.
Se utiliza junto con lenguajes como PHP para guardar información de usuarios, productos, mensajes, etc.


### ***4.-Control de versiones***

Git es un sistema de control de versiones que permite guardar el historial de cambios en los archivos de un proyecto, trabajar en equipo y recuperar versiones anteriores fácilmente.
GitHub es una plataforma en línea que utiliza Git para alojar proyectos, colaborar con otras personas y compartir código públicamente o de forma privada.
Flujo de trabajo con ramas
Una rama es como una copia paralela del proyecto donde puedes trabajar en nuevas funciones o corregir errores sin afectar la versión principal (normalmente llamada "main" o "master").
El uso de ramas permite que varios desarrolladores trabajen en diferentes tareas al mismo tiempo.
Pasos habituales:

***Branching (crear rama):***
Se crea una nueva rama para trabajar en una característica o corrección específica. Ejemplo: git checkout -b nueva-funcionalidad.

***Trabajar en la rama:***
Se realizan cambios y se guardan usando git commit.

***Merge (fusionar ramas):***
Cuando la rama está lista, se fusiona con la rama principal usando git merge. Así, los cambios se integran en el proyecto principal.

***Pull Request:***
En GitHub, antes de fusionar una rama, se suele crear un pull request para que otros revisen los cambios, comenten y aprueben la integración.

<img width="1000" height="530" alt="image" src="https://github.com/user-attachments/assets/0b3543d6-ffa1-4fd6-9952-73f801c4a11d" />

**Propósito de Aprendizaje 2: Desarrollar componentes y funcionalidades de una aplicación web**

# 1. Diseño e implementación del frontend

El diseño e implementación del frontend es una etapa fundamental en el desarrollo de aplicaciones web, ya que define la experiencia visual e interactiva del usuario. El frontend abarca todos los elementos que el usuario ve y con los que interactúa, como menús, botones, formularios, imágenes y animaciones.

## Maquetación, Wireframe y Mockup

El proceso de diseño comienza con la **maquetación**, donde se organiza la estructura básica de la interfaz, determinando la ubicación de cada elemento en la página para asegurar una navegación clara y efectiva.

A continuación, se crean los **wireframes**, que son esquemas visuales simples y sin detalles gráficos. Estos bocetos permiten definir la disposición de los componentes y validar la funcionalidad y el flujo de la aplicación antes de invertir tiempo en el diseño visual.

El siguiente paso es el **mockup**, una representación más detallada y realista del diseño. Aquí se incluyen colores, tipografías, imágenes y otros elementos gráficos para mostrar cómo lucirá la interfaz final. Los mockups facilitan la comunicación entre diseñadores y desarrolladores y permiten revisar y aprobar el diseño antes de la implementación técnica.

## API en el frontend

Una vez aprobado el diseño, el frontend se implementa utilizando tecnologías como HTML, CSS y JavaScript. Sin embargo, en aplicaciones modernas, el frontend suele requerir datos dinámicos que provienen del backend a través de una **API**.

Una **API (Interfaz de Programación de Aplicaciones)** permite que el frontend obtenga información actualizada, como listas de productos, datos de usuario o resultados de búsqueda, directamente desde el servidor. La comunicación se realiza mediante peticiones HTTP y el intercambio de datos en formatos como JSON. Así, la interfaz puede mostrar datos en tiempo real y responder de forma dinámica a las acciones del usuario.

# 2. Diseño e implementación del backend

El backend es la parte de la aplicación web que se encarga de la lógica, el procesamiento de datos y la interacción con el servidor y las bases de datos. Aunque el usuario no lo ve directamente, es fundamental para que la aplicación funcione correctamente.

## Servidor

El servidor es el software que permanece activo y atento a las solicitudes provenientes de los clientes (navegadores web, aplicaciones móviles, etc.). Cuando un usuario realiza una acción en la web, como enviar un formulario o solicitar información, el frontend envía una petición al servidor, que se encarga de procesarla y devolver una respuesta adecuada.

## Manejo de peticiones y respuestas HTTP

La comunicación entre el cliente y el servidor se realiza mediante el protocolo HTTP. Cada vez que el usuario interactúa con la aplicación, se genera una **petición HTTP** que puede ser de diferentes tipos, como GET (obtener información), POST (enviar datos), PUT (modificar datos) o DELETE (eliminar datos). El servidor recibe estas peticiones, ejecuta la lógica necesaria (como consultar la base de datos o validar información) y responde con los datos solicitados, normalmente en formato JSON para que el frontend pueda interpretarlos fácilmente.

## Conexión a bases de datos (MySQL, PostgreSQL, MongoDB)

Una de las tareas principales del backend es interactuar con bases de datos para guardar y recuperar información. Existen diferentes tipos de bases de datos:

- **MySQL:** Sistema de gestión de bases de datos relacional, muy popular por su rapidez y facilidad de uso. Organiza la información en tablas relacionadas.
- **PostgreSQL:** Otro sistema relacional, conocido por su robustez y capacidad para manejar operaciones avanzadas y grandes volúmenes de datos.
- **MongoDB:** Base de datos no relacional (NoSQL) que almacena los datos en forma de documentos (JSON), ideal para estructuras flexibles y cambiantes.

El backend se conecta a la base de datos usando librerías y herramientas específicas, realizando operaciones de consulta, inserción, actualización y eliminación de datos según las necesidades de la aplicación.

# 3. Bases de datos

Las bases de datos son esenciales en el desarrollo web, ya que permiten almacenar, organizar y acceder a la información de manera eficiente y segura. El backend de una aplicación web se encarga de gestionar la conexión y las operaciones sobre la base de datos.

## Modelado de datos y relaciones

Antes de crear una base de datos, es necesario planificar cómo se organizarán los datos. El **modelado de datos** consiste en definir las entidades (por ejemplo, usuarios, productos, pedidos) y sus propiedades, así como las relaciones entre ellas. En bases de datos relacionales (como MySQL o PostgreSQL), estas entidades se representan como tablas, y las relaciones pueden ser de uno a uno, uno a muchos o muchos a muchos. Un buen modelado facilita la consulta, integridad y escalabilidad de la información.

## ORM (Object Relational Mapping)

Un **ORM (Object Relational Mapping)** es una herramienta que permite interactuar con bases de datos relacionales utilizando objetos y clases del lenguaje de programación, en lugar de escribir directamente las consultas SQL. El ORM traduce las operaciones realizadas en el código (crear, leer, modificar, borrar) a instrucciones que entiende la base de datos. Esto simplifica el desarrollo, reduce errores y mejora la mantenibilidad del proyecto. Ejemplos de ORMs populares son SQLAlchemy (Python), Sequelize (Node.js) y Doctrine (PHP).

## CRUD desde el backend

El backend utiliza el modelo CRUD para gestionar la información en la base de datos. CRUD corresponde a las operaciones básicas:

- **Create:** Crear nuevos registros en la base de datos (por ejemplo, un nuevo usuario).
- **Read:** Consultar y obtener información almacenada (por ejemplo, ver una lista de productos).
- **Update:** Modificar datos existentes (por ejemplo, actualizar la dirección de un usuario).
- **Delete:** Eliminar registros (por ejemplo, borrar un pedido cancelado).

Estas operaciones se implementan mediante rutas y controladores en el backend, que reciben las peticiones del frontend, procesan la lógica necesaria y utilizan el ORM para interactuar con la base de datos de forma segura y eficiente.

# 4. Seguridad básica en aplicaciones web

La seguridad es uno de los aspectos más importantes en el desarrollo de aplicaciones web. Su objetivo es proteger los datos de los usuarios y garantizar que solo las personas autorizadas puedan acceder a ciertas funcionalidades o información. La implementación de buenas prácticas de seguridad ayuda a prevenir ataques y vulnerabilidades comunes.

## Validación de formularios

La **validación de formularios** consiste en comprobar que los datos que introduce el usuario cumplen con los requisitos esperados antes de ser procesados o almacenados. Por ejemplo, verificar que un correo electrónico tiene el formato correcto, que una contraseña es lo suficientemente segura o que no se envían campos vacíos.  
La validación debe realizarse tanto en el frontend (para una mejor experiencia de usuario) como en el backend (para garantizar la seguridad).  
Una validación adecuada ayuda a prevenir ataques como la inyección de código malicioso y a evitar errores en el funcionamiento de la aplicación.

## Autenticación y autorización

La **autenticación** es el proceso de verificar la identidad de un usuario, normalmente utilizando credenciales como nombre de usuario y contraseña. Si los datos son correctos, el usuario puede acceder a la aplicación.

La **autorización** consiste en determinar qué acciones o recursos puede usar cada usuario dentro de la aplicación. Por ejemplo, un usuario normal puede ver su perfil, pero solo un administrador puede modificar la configuración general.

Las técnicas comunes para implementar autenticación y autorización incluyen:

- Uso de sesiones y tokens (como JWT) para identificar a los usuarios.
- Control de acceso a rutas y funcionalidades en el backend.
- Almacenamiento seguro de contraseñas usando algoritmos de cifrado.
  
<img width="358" height="141" alt="image" src="https://github.com/user-attachments/assets/ddd5a5d3-d8cb-47a9-a6c0-ce475f5fb1a5" />

**Propósito de Aprendizaje 3: Implementar y desplegar una aplicación web funcional**
# 1. Integración de frontend y backend

La integración entre frontend y backend es esencial para el funcionamiento de una aplicación web dinámica y moderna. Este proceso permite que la **interfaz de usuario** (desarrollada en el frontend) se comunique de manera eficiente con la lógica y los datos del servidor (backend), proporcionando información actualizada y permitiendo la interacción del usuario con la aplicación.

## Interfaz de usuario y frontend

El **frontend** es responsable de mostrar la interfaz de usuario y gestionar la experiencia visual e interactiva. A través de tecnologías como HTML, CSS y JavaScript, el frontend presenta los datos y funcionalidades al usuario, permitiendo la navegación y la realización de acciones como enviar formularios, buscar información o visualizar reportes.

## Manejo de API

Para obtener datos o realizar operaciones, el frontend se comunica con el backend mediante una **API** (Interfaz de Programación de Aplicaciones). Esta API define cómo el frontend puede solicitar información, enviar datos o realizar cambios a través de peticiones HTTP (como GET, POST, PUT o DELETE). El manejo de API en el frontend suele hacerse utilizando funciones de JavaScript como `fetch` o librerías como `axios`, que permiten enviar solicitudes y procesar las respuestas recibidas.

## Proceso de solicitud y respuesta de backend

Cuando el usuario realiza una acción en la interfaz, el frontend envía una **solicitud** a la API del backend. El backend recibe la petición, la procesa (por ejemplo, consultando una base de datos o aplicando reglas de negocio) y genera una **respuesta** que se envía de vuelta al frontend. Esta respuesta normalmente contiene los datos solicitados en formato JSON, que el frontend interpreta y muestra al usuario de forma dinámica.

# 2. Almacenamiento en Servidor

El almacenamiento en servidor es fundamental para guardar archivos, datos y recursos necesarios para el funcionamiento de una aplicación web. Este almacenamiento permite que la información esté disponible y accesible de forma segura para los usuarios y el sistema.

## Tipos de servidores

Existen diferentes tipos de servidores para el almacenamiento de datos:

- **Servidor dedicado:** Un servidor físico exclusivo para una organización o proyecto. Ofrece alto rendimiento, control total y mayor seguridad, pero suele tener un coste más elevado.
- **Servidor compartido:** Varios usuarios o proyectos comparten los recursos de un mismo servidor físico. Es más económico, pero con menos control y rendimiento.
- **Servidor virtual (VPS):** Se utiliza tecnología de virtualización para crear servidores independientes dentro de un mismo hardware físico. Ofrece flexibilidad, escalabilidad y un buen equilibrio entre coste y recursos.
- **Servidores en la nube:** Los recursos y el almacenamiento se ofrecen a través de plataformas en la nube, como servicios gestionados, permitiendo escalabilidad, disponibilidad y pago por uso.

## Servidores y servicios de hosting

El **hosting** es el servicio que permite publicar aplicaciones y páginas web en Internet, proporcionando espacio en servidores y conectividad. Los principales tipos de hosting son:

- **Hosting compartido:** Varios sitios web comparten los recursos de un mismo servidor. Es ideal para proyectos pequeños y tiene un coste bajo.
- **Hosting dedicado:** Un servidor exclusivo para un solo cliente, recomendado para proyectos con alto tráfico o necesidades específicas de seguridad y rendimiento.
- **Hosting VPS:** Servidores virtuales privados que combinan las ventajas del hosting dedicado y compartido.
- **Hosting en la nube:** Permite alojar aplicaciones en plataformas como AWS, Google Cloud o Azure, facilitando la escalabilidad y la administración automática de recursos.

## Proveedores de Servicios de Almacenamiento

Existen numerosos proveedores que ofrecen servicios de almacenamiento y hosting para proyectos web:

- **Amazon Web Services (AWS):** Proporciona servicios como S3 para almacenamiento de archivos, EC2 para servidores virtuales y RDS para bases de datos.
- **Google Cloud Platform (GCP):** Ofrece almacenamiento en la nube, servidores virtuales y bases de datos gestionadas.
- **Microsoft Azure:** Plataforma de servicios en la nube con opciones de almacenamiento, servidores y bases de datos escalables.
- **DigitalOcean:** Popular por su simplicidad y sus servidores VPS accesibles.
- **Hostinger, Bluehost, GoDaddy:** Proveedores de hosting tradicional, con opciones compartidas, VPS y dedicadas.


# 3. Optimización y rendimiento

La optimización y el rendimiento son aspectos esenciales para asegurar que una aplicación web funcione de manera ágil, eficiente y con una experiencia satisfactoria para el usuario. Un proyecto bien optimizado es más rápido, consume menos recursos y es más fácil de mantener y escalar.

## Optimización de recursos (imágenes, scripts)

Para mejorar el rendimiento, es fundamental optimizar los recursos que la aplicación utiliza, como imágenes y scripts:

- **Imágenes:** Se recomienda comprimir y ajustar el tamaño de las imágenes antes de subirlas a la web, empleando formatos adecuados (WebP, JPEG optimizado) y técnicas como carga diferida (lazy loading) para que se descarguen solo cuando el usuario las necesita.
- **Scripts:** Es importante minimizar y agrupar los archivos JavaScript y CSS, eliminando código innecesario y cargando solo los recursos imprescindibles. El uso de herramientas como Webpack, Babel o minificadores ayuda a reducir el peso de los archivos y acelerar la carga de la página.

## Despliegue de aplicaciones web

El **despliegue** consiste en publicar la aplicación en un servidor o servicio de hosting, haciéndola accesible para los usuarios. Es recomendable automatizar el proceso de despliegue para evitar errores y facilitar actualizaciones, utilizando plataformas como Vercel, Netlify, AWS, o servicios tradicionales de hosting.

## CI/CD básico

La **Integración Continua (CI)** y la **Entrega/Despliegue Continuo (CD)** son prácticas que permiten automatizar pruebas, integración y despliegue de código. Con herramientas como GitHub Actions, Travis CI o Jenkins, se puede configurar el proyecto para ejecutar pruebas automáticamente con cada cambio, validar que todo funciona correctamente y desplegar la aplicación de forma segura y rápida.

## Documentación del proyecto

Una buena **documentación** es vital para que otros desarrolladores puedan entender, mantener y escalar el proyecto. Debe incluir información sobre la arquitectura, instrucciones de instalación, uso de la API, comandos útiles, estructura de carpetas y detalles sobre el proceso de despliegue y pruebas. La documentación puede estar en archivos README.md, wikis o plataformas especializadas.

<img width="800" height="566" alt="image" src="https://github.com/user-attachments/assets/083791ca-b0cb-4e9d-ab3a-12d9f9bafe2a" />
