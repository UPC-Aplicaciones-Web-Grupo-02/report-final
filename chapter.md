# Capítulo V: Product Implementation, Validation & Deployment

## 5.1. Software Configuration Management.

### 5.1.1. Software Development Environment Configuration.
En esta sección, se mencionarán los diversos productos de software empleados por el equipo de desarrollo para la elaboración del proyecto.
<br>

**Project Management**

Google Meet (https://meet.google.com/): Google Meet es una plataforma de videoconferencias que permite realizar reuniones a distancia, facilitando la comunicación entre los integrantes del proyecto.
WhatsApp(https://www.whatsapp.com/?lang=es_LA): WhatsApp es una plataforma de mensajería que permite la comunicación a distancia de manera rápida y efectiva, facilitando la comunicación entre los integrantes del proyecto.
  
<br>

**Requirements Managements**

Trello (https://trello.com/): Herramienta de gestión de proyectos basada en tableros Kanban, usada para organizar tareas de forma visual. Fue utilizado para el Product Backlog.
<br>

**Product UX/UI Design**

UXPressia (https://uxpressia.com/): Plataforma online para crear mapas de experiencia del cliente, personas y customer journey maps, facilitando el diseño centrado en el usuario. Se utilizó para la elaboración de los User Personas, Empathy Maps, Journey Maps e Impact Maps.
Figma (https://www.figma.com/): Figma es un editor de gráficos vectoriales y herramienta de diseño de interfaz colaborativa basada en la web. Se usó para realizar los wireframes, mock-ups y los desktop and mobile application prototype del proyecto.

Miro (https://miro.com/): Es una Pizarra digital colaborativa para lluvia de ideas, diagramación, mapeo de procesos y planificación ágil. Se utilizó para la realización de los As-Is y Tob-Be Scenario Maps.
<br>

**Software Development**

Landing Page: Para la creación de la landing page, se utilizaron las tecnologías base del desarrollo web: HTML5, CSS3 y JavaScript.
GitHub (https://github.com/): Plataforma de alojamiento de código que utiliza Git para el control de versiones y colaboración en proyectos de software. GitHub nos permite trabajar colaborativamente y tener un seguimiento detallado de los avances en el proyecto.
Git (https://git-scm.com/): Este es un sistema de control de versiones distribuido que permite a múltiples desarrolladores trabajar en el mismo código fuente simultáneamente. También se utiliza para trabajar colaborativamente en repositorios que se encuentran subidos en GitHub.

WebStorm: IDE de JetBrains para el desarrollo en JavaScript, TypeScript y tecnologías web moderna.
Rider: Este es un entorno de desarrollo, el cual nos permite trabajar con el lenguaje C# y la plataforma .NET que nos permite crear diferentes tipos de aplicaciones, ya sean móvil, web o de escritorio. En nuestro caso, usaremos ASP .NET para crear un Web Service para nuestro proyecto.
<br>

**Software Deployment**

GitHub Page (https://pages.github.com/): GitHub Pages es un servicio que ofrece GitHub para publicar un sitio web a partir de un repositorio, cabe mencionar que solo permite alojar sitios web estáticos y dinamicos. Se utilizó para desplegar la landing page del proyecto.
<br>

**Software Documentation**

Vertabelo (https://vertabelo.com/): Herramienta visual para modelado de bases de datos, permitiendo diseño de esquemas y generación de scripts SQL. Se usó para diseñar la base de datos del proyecto.

LucidChart (https://lucid.app/): Aplicación de diagramación basada en la nube para flujos de procesos, UML, redes, y colaboración en tiempo real. Fue utilizado en el desarrollo del diagrama de clases UML, así como los Wireflows y User Flows.

Structurizr (https://www.structurizr.com/): Herramienta para crear diagramas de arquitectura de software basados en código y el modelo C4. Structurizr fue utilizado para crear el modelo C4 de nuestro proyecto.
<br>

**Software Testing**

Gherkin: Este es un lenguaje DSL (Domain Specific Language), que nos permite abordar problemas específicos. Esto lo utilizamos para los criterios de aceptación de las historias de usuario de nuestro proyecto.

GitHub Pages (https://pages.github.com/): Este es un servicio que ofrece GitHub para publicar un sitio web a partir de un repositorio, cabe destacar que solo permite alojar sitios web estáticos con archivos HTML, CSS y JavaScript.

Markdown: Lenguaje de marcado ligero para crear contenido formateado de forma sencilla, utilizado en documentación y páginas estáticas. En nuestro proyecto, este lenguaje fue utilizado para redactar el informe y los archivos README en el repositorio de la organización.


### 5.1.2. Source Code Management.
En esta sección, se detallaran las herramientas que  se utilizaron para el seguimiento de las modificaciones, así como la semántica y nomenclatura que se usara para los commits y releases. 
Para el sistema de control de versiones del informe, landing page, web service y front-end se utilizó Git, el cual se encuentra alojado en GitHub.
- Url de la organizacion: [github.com/UPC-Aplicaciones-Web-Grupo-02]( https://github.com/UPC-Aplicaciones-Web-Grupo-02/report-final)

**Gitflow**
Decidimos utilizar este modelo de trabajo ya que permite mantener el codigo ordenado al dividirlo en ramas, de tal forma que nos facilita trabajar colaborativamente. Las ramas que se utilizaron son:
- Main: En esta rama se encuentra el código que se encuentra en producción.
- Develop: En esta rama se encuentra el código que se encuentra en desarrollo.
- Feature: En esta rama se encuentran las nuevas funcionalidades que se están desarrollando.

**Semantic Versioning**
Este es un conjunto de reglas que nos permitirán gestionar correctamente la numeración de versiones de nuestro proyecto.
**Version Principal**
Se incrementa cuando los cambios agregados no son compatibles con las versiones anteriores.

<table align="center" border="1">
    <tr>
        <td>release-1.0.5</td>
    </tr>
    <tr>
        <td>release-2.1.3</td>
    </tr>
    <tr>
        <td>release-2.2.1</td>
    </tr>
</table>

**Conventional commits**
Se utilizó el estándar de commits convencionales para mantener un historial de cambios limpio y ordenado. Los commits se dividen en los siguientes tipos:
- **feat**: Se utiliza para nuevas funcionalidades.
- **fix**: Se utiliza para corrección de errores.
- **chore**: Se utiliza para cambios en el código que no afectan la funcionalidad.
- **refactor**: Se utiliza para cambios en el código que no afectan la funcionalidad.


### 5.1.3. Source Code Style Guide & Conventions.
Para desarrollar nuestro proyecto hemos requerido de algunas nomenclaturas, referencias y lenguajes para la solucion.

**Tecnologias:** Utilizamos HTML5, CSS3 y JavaScript para el desarrollo de la landing page.
- **HTML:** Para el lenguaje HTML, nos planteamos utilizar las convenciones descritas en la guía “HTML Style Guide and Coding Conventions”:
    - Usar nombres de elementos en minúsculas.
    - Cerrar todos los elementos HTML.
    - Usar nombres de atributos en minúsculas.
    - Usar atributos en imágenes.
    - Evitar líneas de código largas.
    - Usar sintaxis simple para los enlaces para las hojas de estilo y para cargar script externos

- **CSS:** Para el lenguaje CSS, utilizaremos las siguientes prácticas para alcanzar un código coherente, sostenible y ordenado:

    - Utilizar minúsculas y guiones para los nombres de propiedades.
    - Utilizar un espacio después de los dos puntos y un punto y coma para separar pares propiedad-valor.
    - Agrupar reglas CSS relacionadas y separarlas con una línea en blanco.
    - Utilizar nombres de clases que sean descriptivos y reflejen el propósito del elemento.
    - Separar los nombres de las clases y ID con un guión

- **Gherkin:** Es un lenguaje de dominio específico diseñado para escribir especificaciones legibles por humanos que describen el comportamiento del software en un formato estructurado y comprensible. En busca de una buena práctica, se utilizarán saltos de línea para mejorar el orden de los escenarios y poder diferenciarlos de forma más óptima. Además, se escribirán los escenarios bajo el formato “Given”, “When”, “Then”, “And” para definir claramente el contexto, la acción y el resultado esperado.
  
-**Herramientas:** Nos apoyamos de las tecnologias mas utilziadas y recomendadeas para el desarrollo web, como los son Webstorm, Git, GitHub, LudcidChart, Figma y Miro.

**Convenciones de idioma:** Uso del idioma ingles para elaborar nuestro codigo, incluyendo la parte de la landing page.

**Conventional commits**
Se utilizó este estandar para garantizar una facil comprension de nuestros registros. Por lo tanto, nos regimos por la siguiente estructura:<br/>

- Type: indica el tipo de commit que se realizó.
- Scope: define el alcance del commit.
- Descripción: describe brevemente el cambio realizado.

### 5.1.4. Software Deployment Configuration.

Para el despliegue de la solucion realizamos los siguientes pasos:

- Ingresar a la organizacion de GitHub a través del URL: [github.com/UPC-Aplicaciones-Web-Grupo-02](https://github.com/UPC-Aplicaciones-Web-Grupo-02/report-final)

![Image](https://github.com/user-attachments/assets/8a49b125-b2ca-4588-8219-89f7626ad5c6)

- Seleccionar el repositorio de la landing page del proyecto

![Image](https://github.com/user-attachments/assets/d1bdef89-5ebe-46e4-8bc5-584acc88f950)

- A continuación clonamos el repositorio en Webstorm usando la URL.
  
![Image](https://github.com/user-attachments/assets/5f9975f9-b892-4019-aad9-d3123290ee67)

![Image](https://github.com/user-attachments/assets/8a609cdb-57bf-411c-8482-14d90d0e59f7)

- Procedemos a ejecutar el archivo index.html para finalmente poder visualizar la landing page en el navegador.
  
![Image](https://github.com/user-attachments/assets/58c39941-02be-4e91-9abe-58ae64bf1c22)

![Image](https://github.com/user-attachments/assets/3425a6a3-91ab-43a5-bdff-4bb9603d490f)



## 5.2. Landing Page, Services & Applications Implementation.

### 5.2.1. Sprint 01

#### 5.2.1.1. Sprint Planning 01.
<table border="1px" align="center">
    <tr>
        <th>Sprint #</th>
        <th>Sprint 1</th>
    </tr>
    <tr> 
        <td colspan="2" style="text-align: center;">Sprint Planning Background</td>
    </tr>
    <tr>
        <td style="font-weight: bold;">Date</td>
        <td>11/04/2025</td>
    </tr>
    <tr>
        <td style="font-weight: bold;">Time</td>
        <td>6:00 pm - 10:00 pm </td>
    </tr>
    <tr>
        <td style="font-weight: bold;">Location</td>
        <td>Modalidad remota a través de WhatsApp y Google Meets</td>
    </tr>
    <tr>
        <td style="font-weight: bold;">Prepared By</td>
        <td> Nestor Velarde Gonzales </td>
    </tr>
    <tr>
        <td style="font-weight: bold;">Attendees (to planning meeting)</td>
        <td>
            Arnold Morales Sosa<br>
            Alonso Muñiz Huayanca <br>
            Nestor Velarde Gonzales<br>
            Rafael Cuya Villegas<br>
            Sebastian Flores Manrique    
        </td>
    </tr>
    <tr>
        <td style="font-weight: bold;">Sprint 0 Review Summary</td>
        <td>No existe.</td>
    </tr>
    <tr>
        <td style="font-weight: bold;">Sprint 0 Retrospective Summary</td>
        <td>No existe.</td>
    </tr>
    <tr> 
        <td colspan="2" style="text-align: center;">Sprint Goal & User Stories</td>
    </tr>
    <tr>
        <td style="font-weight: bold;">Sprint 1 Goal</td>
        <td>
            En este sprint se espera la implementación y despliegue de la landing page con las secciones funcionales, el footer y el diseño responsivo. En el grupo acordamos usar HTML y CSS para hacer la landing page. Al finalizar este sprint, la landing page se desplegó con ayuda de la herramienta GitHub Pages.
        </td>
    </tr>
    <tr>
        <td style="font-weight: bold;">Sprint 1 Velocity</td>
        <td>18</td>
    </tr>
    <tr>
        <td style="font-weight: bold;">Sum of Story Points</td>
        <td>18</td>
    </tr>
</table>


#### 5.2.1.2. Aspect Leaders and Collaborators.

<table>
  <thead>
    <tr>
      <th>Team Member (Last Name, First Name)</th>
      <th>GitHub Username</th>
      <th>Aspect Landing Page Leader (L) / Collaborator (C)</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Velarde Gonzales, Nestor</td>
      <td>VelardeSoft</td>
      <td>L</td>
    </tr>
    <tr>
      <td>Muñiz Huayanca, Percy Alonso</td>
      <td>alomsoo</td>
      <td>C</td>
    </tr>
    <tr>
      <td>Morales Sosa, Arnold Gabriel</td>
      <td>Arnold24x24</td>
      <td>C</td>
    </tr>
    <tr>
      <td>Cuya Villegas, Rafael Alberto</td>
      <td>RafaelCuya</td>
      <td>C</td>
    </tr>
    <tr>
      <td>Flores Manrique, Sebastian Enrique</td>
      <td>Sebas2999</td>
      <td>C</td>
    </tr>
  </tbody>
</table>


#### 5.2.1.3. Sprint Backlog 1.

<table border="1px" align="center"> 
   <tr>
      <th colspan="4"> Sprint # </th>
      <th colspan="7"> Sprint 1 </th>
   </tr>
   <tr >
     <th colspan="4"> User Story </th>
     <th colspan="7"> Work-Item / Task</th>
   </tr>
   <tr>
     <th> Id </th>
     <th colspan="3"> Title </th>
     <th> Id </th>
     <th> Title </th>
     <th> Description </th>
     <th> Estimation (Hours) </th>
     <th> Assigned To </th> 
     <th> Status (To-do / In-Process / To- Review / Done) </th>
   </tr>
   <tr>
       <td> EP01-US01 </td>
      <td colspan="3">Implementación de la sección “Home” de la Landing Page</td>
      <td> W01  </td>
      <td> Sección “Home” </td>
      <td>Implementar la sección “Home” de la Landing Page. </td>
      <td> 3  </td>
      <td> Rafael Cuya </td> 
      <td> Done </td>
   </tr>
   <tr>
      <td> EP01-US02 </td>
      <td colspan="3">Implementación de la sección "Contacto" de la Landing Page</td>
      <td> W02  </td>
      <td> Sección "Contacto "</td>
      <td>Implementar la sección "Contacto" de la landing page. </td>
      <td> 1  </td>
      <td> Alonso Muñiz</td> 
      <td> Done </td>
   </tr>
   <tr>
      <td> EP01-US03 </td>
      <td colspan="3">Implementación inicial de la landing page y código para Landing Page responsiva</td>
      <td> W03  </td>
      <td> Sección "Services" </td>
      <td>Implementación  inicial de la landing page y código para Landing Page responsiva. </td>
      <td> 3  </td>
      <td> Nestor Velarde </td> 
      <td> Done </td>
   </tr>
   <tr>
      <td> EP01-US04 </td>
      <td colspan="3">Implementación de la sección "Suscripciones" de la Landing Page</td>
      <td> W04  </td>
      <td> Sección "Suscripciones" </td>
      <td>Implementar la sección "Suscripciones" en la landing page </td>
      <td> 3  </td>
      <td> Arnold Morales </td> 
      <td> Done </td>
   </tr>
   <tr>
      <td> EP01-US05 </td>
      <td colspan="3">Implementación de la sección "About us" de la Landing Page</td>
      <td> W05  </td>
      <td> Sección "About us" </td>
      <td>Implementar la sección "About us" de la landing page</td>
      <td> 3  </td>
      <td> Sebastian Flores </td> 
      <td> Done </td>
   </tr>   
</table>


#### 5.2.1.4. Development Evidence for Sprint Review.

En esta seccion se evidenciaran los commits realizados para la implementacion de la Landing Page.

![Image](https://github.com/user-attachments/assets/076476c2-3c1d-4be8-ba1f-565ae2490c04)

![Image](https://github.com/user-attachments/assets/e5313656-61fe-46da-826c-483978f13d9d)

![Image](https://github.com/user-attachments/assets/ac6f41be-64c7-4102-b2c6-871c67149b80)

#### 5.2.1.5. Execution Evidence for Sprint Review.

En el primer Sprint se realizó la implementación de la landing page con las secciones funcionales, el footer y el diseño responsivo. A continucacion se muestra la landing page implementada en la version web y la version mobile:

Link de nuestra landing page: [Visita nuestro sitio](https://upc-aplicaciones-web-grupo-02.github.io/landing-page/)

**Versión Web**

![Image](https://github.com/user-attachments/assets/eb356fe5-8ab8-42b0-bc55-02bdc874ac0c)
Portada de nuestra landing page

![Image](https://github.com/user-attachments/assets/9da44016-6bf8-4e00-bc3e-12a3f0f5286a)
Sección Sobre Nosotros

![Image](https://github.com/user-attachments/assets/c7f61a52-2064-43d0-af4d-90e6f474c6b9)
Sección nuestros servicios

![Image](https://github.com/user-attachments/assets/a82de65d-536f-464c-87c0-c6c043ab55ca)
Sección nuestras suscripciones

![Image](https://github.com/user-attachments/assets/4efecc22-9ddc-40b8-a6c0-769c32f391cf)
Sección que muestra a los integrantes del equipo de desarrollo

![Image](https://github.com/user-attachments/assets/ab519cd6-b614-4d7c-bfd0-1caa3fe327b2)
Imagen que muestra el contenido de nuestro footer

**Versión Mobile**

![Image](https://github.com/user-attachments/assets/33865f12-ba7a-4b18-9168-610329eac969)

![Image](https://github.com/user-attachments/assets/39d40e6a-117c-432a-a399-abe2bed43445)

![Image](https://github.com/user-attachments/assets/c6f6b73f-b15c-4e3a-ae2a-62668daaf66a)

![Image](https://github.com/user-attachments/assets/0973415c-1ed8-40b3-91ee-8afe32898116)

![Image](https://github.com/user-attachments/assets/5f361e4f-9680-42d6-b50a-28f57474efd1)

#### 5.2.1.6. Services Documentation Evidence for Sprint Review.

**No aplica para esta entrega**

#### 5.2.1.7. Software Deployment Evidence for Sprint Review.
Para el despliegue de la landing page usamos la herramienta github pages, a continuación mostaremos el link de la landing page desplegada junto con los pasos realizados para publicarla:
[LandingPage](https://upc-aplicaciones-web-grupo-02.github.io/landing-page/)

**Pasos**
- Ingresamos a nuestro repositorio.
![Image](https://github.com/user-attachments/assets/304dc4e0-86c4-4954-a908-664c573b18aa)

- Seleccionamos el repositorio de la landing page.
![Image](https://github.com/user-attachments/assets/dcd7ee86-3e2b-490d-8e08-62deed5bde32)

- Una vez dentro del repositorio de la landing page, nos vamos a la seccion settings.
![Image](https://github.com/user-attachments/assets/0cce6e8d-07ec-4821-a7a1-606bd2f9b401)

- Ingresamos a la seccion pages.
![Image](https://github.com/user-attachments/assets/0e1a11dc-c352-44c0-845b-622fb1fa2f54)

- Nos dirigimos a "Build and Deployment", seleccionamos la rama main para ejecutar el deploy y guardamos.
![Image](https://github.com/user-attachments/assets/1d8133f2-5c56-42b0-b8d0-395988ff27eb)

- Se generará un enlace al cual accederemos.
![Image](https://github.com/user-attachments/assets/2d1b8f09-1a53-4daa-a54f-57ffa17a16ab)

- Finalmente se muestra nuestra landing page.
![Image](https://github.com/user-attachments/assets/eb356fe5-8ab8-42b0-bc55-02bdc874ac0c)


#### 5.2.1.8. Team Collaboration Insights during Sprint.

Colaboración por alumno en la Landing Page:

<table border="1px" align="center">
  <tr>
    <th>Alumno</th>
    <th>Actividad</th>
  </tr>
    <tr>
    <td>Cuya Villegas, Rafael Alberto</td>
    <td>Implementación de la navbar e inicio de la Landing Page.</td>
  </tr>
  <tr>
    <td>Flores Manrique, Sebastian Enrique</td>
    <td>Implementación de la sección "About Us " de la Landing Page.</td>
  </tr>
  <tr>
    <td>Muñiz Huayanca, Percy Alonso</td>
    <td>Implementación de la sección "Contacto" de la Landing Page.</td>
  </tr>
  <tr>
    <td>Morales Sosa, Arnold Gabriel</td>
    <td>Implementación de la sección "Suscripciones" de la Landing Page.</td>
  </tr>
  <tr>
    <td>Velarde Gonzales, Nestor Hernan </td>
    <td>Implementación inicial de la landing page y código para Landing Page responsiva</td>
  </tr>
  </table>

Tabla para poder identificarnos:

<table border="1px" align="center">
  <tr>
    <th>Username (Github)</th>
    <th>Nombre</th>
  </tr>
  <tr>
    <td>VelardeSoft</td>
    <td>Velarde Gonzales, Nestor</td>
  </tr>
  <tr>
    <td>alomsoo </td>
    <td> Muñiz Huayanca, Percy Alonso </td>
  </tr>
  <tr>
    <td>Arnold24x24 </td>
    <td> Morales Sosa, Arnold Gabriel </td>
  </tr>
  <tr>
    <td>RafaelCuya </td>
    <td>Cuya Villegas, Rafael Alberto</td>
  </tr>
  <tr>
    <td>Sebas2999 </td>
    <td> Flores Manrique, Sebastian Enrique </td>
  </tr>
</table>

Para este Sprint los integrantes trabajamos de manera colaborativa a través de commits en la herramienta GitHub.

![Image](https://github.com/user-attachments/assets/9434c4fb-b94c-43e7-8fdf-d647ad11e761)


Utilizando Github se creó una organizacion para el desarrollo del proyecto, esta fue dividida en dos repositorios, uno para el informe y el otro para la landing page.

Hemos desarrollado un total de 27 commits para la implementacion de nuestra landing page. 
![Image](https://github.com/user-attachments/assets/942c5e49-31f0-401a-a69e-967141e64e65)
![Image](https://github.com/user-attachments/assets/9d569a09-1907-44ea-8c6d-7a13f6e3b471)






