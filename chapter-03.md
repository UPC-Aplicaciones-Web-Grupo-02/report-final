# Capítulo III: Requirements Specification

## 3.1. To-Be Scenario Mapping.
*Segmento 1: Owner*
![MAPPING OWNER](https://github.com/user-attachments/assets/dbbce90d-d08c-4f56-baa5-a19c9c843267)
*Segmento 2: User*
![MAPPING USER](https://github.com/user-attachments/assets/8d3669b7-3ecf-4167-890c-ce2dbc0c7f79)

## 3.2. User Stories.

Los user Stories (historias de ususario) son descripciones cortas que nos ayuda a identificar las funcionalidades desde la perspectiva del usuario final y como desarrollador. Acontinuación, listaremos los user stories necesarias para nuestro Startup. 

<table border="1px">
  <tr>
    <th>Epic / Story ID</th>
    <th>Título</th>
    <th>Descripción</th>
  </tr>
  <tr>
    <td>EP01</td>
    <td>Landing page de Movix</td>
    <td>Cómo Estudiante/Usuario Quiero ingresar una landing page Para entender rápidamente los beneficios y cómo puedo obtener un Scooter adecuado.</td>
  </tr>
  <tr>
    <td>EP02</td>
    <td>Gestión de cuenta de usuario</td>
    <td>Como Estudiante/Usuario de Movix Quiero crear, visualizar, eliminar y editar mi cuenta Para tener mis datos actualizados y comenzar a hacer uso de la aplicación correctamente.</td>
  </tr>
  <tr>
    <td>EP03</td>
    <td>Gestión de Scooters</td>
    <td>Como desarrollador de Movix Quiero agregar y gestionar mis scooters Para asegurarme que estén disponibles y en buen estado para el alquiler a los usuarios interesados.</td>
  </tr>
  <tr>
    <td>EP04</td>
    <td>Gestión de reservas</td>
    <td>Como Estudiante/Usuario de Movix Quiero gestionar mis reservas y el uso de scooters Para planificar y controlar mis alquileres.</td>
  </tr>
  <tr>
    <td>EP05</td>
    <td>Gestionar historial de reservas</td>
    <td>Cómo Estudiante/Usuario de Movix Quiero poder ver el historial completo de las reservas realizadas Para acceder a la información de estos de manera sencilla y tener un control de mi historial.</td>
  </tr>
  <tr>
    <td>EP06</td>
    <td>Gestión de planes</td>
    <td>Cómo Estudiante/Usuario de Movix Quiero tener una gestión y control de mi plan Para poder adquirirlo y cancelarlo cuando lo requiera.</td>
  </tr>
  <tr>
    <td>EP07</td>
    <td>Desarrollo de la aplicación web</td>
    <td>Cómo desarrollador de MoviRent Quiero hacer consultas desde los endpoints de la api rest Para poder probar las respuestas del servicio de la aplicación.</td>
  </tr>
</table>

<table border="1px">
    <tr>
        <th>Epic / Story ID</th>
        <th>Título</th>
        <th>Descripción</th>
        <th>Criterios de Aceptación</th>
        <th>Relacionado con (Epic ID)</th>
    </tr>
    <tr>
        <td>US01</td>
        <td>Implementación de la sección Inicio de la Landing Page</td>
        <td><b>Como</b> visitante de la landing page
        <b>Quiero</b> visualizar la sección "Inicio"
        <b>Para</b> tener una primera vista del producto</td>
        <td>
            <b>Scenario 1: Visualizar sección Inicio</b> <br/>
            <b>Dado que</b> el visitante ingresa a la página<br/>
            <b>Cuando</b> la página cargue <br/>
            <b>Entonces</b> se muestra una sección llamativa que anime al usuario a usar la aplicación.<br/>
            <br>
            <b>Scenario 2: Error en el sistema </b> <br/>
            <b>Dado que</b> el visitante se encuentre dentro de la landing page<br/>
            <b>Cuando</b> ocurra algún problema con el sistema <br/>
            <b>Entonces</b> no se muestra la sección Home<br/>
            <b>Y</b> se muestra un mensaje de error [404]<br/>
        <td>EP01</td>
    </tr>
    <tr>
        <td>US02</td>
        <td>Implementación de la sección "Sobre Nosotros" de la Landing Page</td>
        <td><b>Como</b> visitante de la landing page
        <b>Quiero</b> visualizar la sección "Sobre Nosotros"
        <b>Para</b> tener información de la startup CiberMach.</td>
        <td>
            <b>Scenario 1: Acceder a la sección "Sobre Nosotros"</b> <br/>
            <b>Dado que</b> el visitante se encuentre dentro de la landing page <br/>
            <b>Cuando</b> navegue hasta la sección “Sobre Nosotros” <br/>
            <b>Entonces</b> se muestra información importante sobre la startup. <br/>
            <br>
            <b>Scenario 2: Error en el sistema </b> <br/>
            <b>Dado que</b> el visitante se encuentre dentro de la landing page<br/>
            <b>Cuando</b> ocurra algún problema con el sistema <br/>
            <b>Entonces</b> no se muestra la sección Home<br/>
            <b>Y</b> se muestra un mensaje de error.<br/>
        <td>EP01</td>
    </tr>
    <tr>
        <td>US03</td>
        <td>Implementación de la sección "Servicios" de la Landing Page</td>
        <td><b>Como</b> visitante de la landing page
        <b>Quiero</b> visualizar la sección "Servicios"
        <b>Para</b> tener información de los servicios ofrecidos por la aplicación</td>
        <td>
            <b>Scenario 1: Acceder a la sección "Servicios"</b> <br/>
            <b>Dado que</b> el visitante se encuentre dentro de la landing page<br/>
            <b>Cuando</b> navegue hasta la sección “Servicios” <br/>
            <b>Entonces</b> se muestra información sobre los servicios que ofrece Movix<br/>
            <br>
            <b>Scenario 2: Error en el sistema </b> <br/>
            <b>Dado que</b> el visitante se encuentre dentro de la landing page<br/>
            <b>Cuando</b> ocurra algún problema con el sistema <br/>
            <b>Entonces</b> no se muestra la sección Home<br/>
            <b>Y</b> se muestra un mensaje de error.<br/>
        <td>EP01</td>
    </tr>
    <tr>
        <td>US04</td>
        <td>Implementación de la sección "Planes" de la Landing Page</td>
        <td><b>Como</b> visitante de la landing page
        <b>Quiero</b> visualizar la sección "Planes"
        <b>Para</b> tener información de las membresías de la aplicación</td>
        <td>
            <b>Scenario 1: Acceder a la sección "Planes"</b> <br/>
            <b>Dado que</b> el visitante se encuentre dentro de la landing page<br/>
            <b>Cuando</b> navegue hasta la sección “Planes” <br/>
            <b>Entonces</b> se muestra la información relacionada a los planes de pago que se ofrecen y cuáles son los beneficios de cada uno de estos.<br/>
            <br>
            <b>Scenario 2: Error en el sistema </b> <br/>
            <b>Dado que</b> el visitante se encuentre dentro de la landing page<br/>
            <b>Cuando</b> ocurra algún problema con el sistema <br/>
            <b>Entonces</b> no se muestra la sección Home<br/>
            <b>Y</b> se muestra un mensaje de error.<br/>
        <td>EP01</td>
    </tr>
    <tr>
        <td>US05</td>
        <td>Implementación de la sección "About the Team" de la Landing Page</td>
        <td><b>Como</b> visitante de la landing page
        <b>Quiero</b> visualizar la sección "About the Team"
        <b>Para</b> tener información de los miembros que conforman la startup.</td>
        <td>
            <b>Scenario 1: Conocer al equipo en "About the Team"</b> <br/>
            <b>Dado que</b> el visitante se encuentre dentro de la landing page <br/>
            <b>Cuando</b> navegue hasta la sección “About the Team”<br/>
            <b>Entonces</b> se muestra la información correspondiente a los videos about the project y about the team, además de la información de cada uno de los miembros.<br/>
            <br>
            <b>Scenario 2: Error en el sistema </b> <br/>
            <b>Dado que</b> el visitante se encuentre dentro de la landing page<br/>
            <b>Cuando</b> ocurra algún problema con el sistema <br/>
            <b>Entonces</b> no se muestra la sección Home<br/>
            <b>Y</b> se muestra un mensaje de error.<br/>
        <td>EP01</td>
    </tr>
    <tr>
        <td>US06</td>
        <td> Landing Page Responsiva a diferentes tamaños de pantalla </td>
        <td><b>Como</b> visitante interesado 
        <b>Quiero</b> que la landing page tenga un diseño responsivo
        <b>Para</b> acceder a ella desde cualquier dispositivo.</td>
        <td>
            <b>Scenario 1: Acceder a la landing page desde un ordenador</b> <br/>
            <b>Dado que</b> el visitante se encuentre usando un ordenador de escritorio <br/>
            <b>Cuando</b> ingrese a la landing page <br/>
            <b>Entonces</b> se muestra la landing page adaptada correctamente a la pantalla del ordenador. <br/>
            <br>
            <b>Scenario 2: Acceder a la landing page desde un dispositivo móvil</b> <br/>
            <b>Dado que</b> el visitante se encuentre usando un dispositivo móvil <br/>
            <b>Cuando</b> ingrese a la landing page <br/>
            <b>Entonces</b> se muestra la landing page adaptada correctamente a la pantalla del dispositivo móvil. <br/>
        <td>EP01</td>
    </tr>
    <tr>
        <td>US07</td>
        <td>Acceder a la aplicación desde la landing page </td>
        <td><b>Como</b> visitante de la landing page 
        <b>Quiero</b> poder acceder a la aplicación Movix desde la landing page
        <b>Para</b> comenzar a utilizar las funcionalidades ofrecidas</td>
        <td>
            <b>Scenario 1: Usuario ingresa a aplicación</b> <br/>
            <b>Dado que</b> el visitante se encuentra en la landing page <br/>
            <b>Cuando</b> seleccione la opción 'Get Started' que permite el acceso a la aplicación web<br/>
            <b>Entonces</b> es redirigido a la aplicación web desplegada<br/>
            <br>
            <b>Scenario 2: Fallo en el acceso a la aplicación</b> <br/>
            <b>Dado que</b> el visitante se encuentre en la landing page <br/>
            <b>Cuando</b> seleccione la opción que permite el acceso al software elaborado y ocurra un error en el proceso de redirección<br/>
            <b>Entonces</b> el usuario obtiene un mensaje de error.<br/>
        <td>EP01</td>
    </tr>
    <tr>
        <td>US08</td>
        <td>Registrar usuario</td>
        <td><b>Como</b> visitante de la aplicación web de Movix
        <b>Quiero</b> poder crear una cuenta personal
        <b>Para</b> comenzar a hacer uso de la aplicación como Estudiante/Usuario</td>
        <td>
            <b>Scenario 1: Usuario ingresa credenciales válidas.</b> <br/>
            <b>Dado que</b> el visitante desee crear una cuenta personal en la aplicación Movix <br/>
            <b>Cuando</b> ingrese las credenciales de una cuenta inexistente en la base de datos Movix, una contraseña que cumple con todos los requisitos de seguridad, su DNI real y acepte los términos y condiciones de uso <br/>
            <b>Entonces</b> se creará la cuenta de usuario.<br/>
            <br>
            <b>Scenario 2: Usuario ingresa credenciales incorrectas.</b> <br/>
            <b>Dado que</b> Usuario ingresa credenciales incorrectas. <br/>
            <b>Cuando</b> ingrese una dirección de correo electrónico o contraseña o DNI que no cumplen con los requisitos especificados<br/>
            <b>Entonces</b> se le denegará la operación<br/>
        <td>EP02</td>
    </tr>
    <tr>
        <td>US09</td>
        <td>Iniciar sesión</td>
        <td><b>Como</b> Estudiante/Usuario de Movix 
        <b>Quiero</b> iniciar sesión
        <b>Para</b> acceder a los beneficios que ofrece la aplicación.</td>
        <td>
            <b>Scenario 1: Usuario ingresa credenciales válidas </b> <br/>
            <b>Dado que</b> el usuario posee una cuenta en la aplicación Movix <br><b>Y</b> desee iniciar sesión <br/>
            <b>Cuando</b> ingrese las credenciales necesarias correctamente<br/>
            <b>Entonces</b> el sistema permitirá el acceso a la aplicación<br/>
            <br>
            <b>Scenario 2: Usuario ingresa credenciales incorrectas</b> <br/>
            <b>Dado que</b> el usuario posee una cuenta en la aplicación Movix <br><b>Y</b> desea iniciar sesión <br/>
            <b>Cuando</b> ingrese alguna credencial de manera incorrecta <br/>
            <b>Entonces</b> el sistema denegará la solicitud<br/>
        <td>EP02</td>
    </tr>
    <tr>
        <td>US10</td>
        <td>Visualizar perfil de usuario</td>
        <td><b>Como</b> Estudiante/Usuario de Movix 
        <b>Quiero</b> visualizar mi perfil personal 
        <b>Para</b> visualizar mis datos actuales</td>
        <td>
            <b>Scenario 1: Acceder al perfil personal</b> <br/>
            <b>Dado que</b> el usuario desee visualizar su información personal <br/>
            <b>Cuando</b>  ingrese a su perfil <br/>
            <b>Entonces</b> obtendrá toda la información que registró previamente<br/>
            <br>
            <b>Scenario 2: Problema al acceder al perfil personal </b> <br/>
            <b>Dado que</b> el usuario desee visualizar su información personal  <br/>
            <b>Cuando</b> intente ingresar a su perfil <br><b>Y</b> experimente un error de conexión o de servidor <br/>
            <b>Entonces</b> no se visualizarán los datos del perfil <br/>
        <td>EP02</td>
    </tr>
    <tr>
        <td>US11</td>
        <td>Cambiar datos personales </td>
        <td><b>Como</b> Estudiante/Usuario de Movix 
        <b>Quiero</b> cambiar los datos asociados a mi perfil
        <b>Para</b> actualizar la información</td>
        <td>
            <b>Scenario 1: Cambiar contraseña</b> <br/>
            <b>Dado que</b> el usuario quiera cambiar su contraseña <br/>
            <b>Cuando</b> ingrese la nueva contraseña, esta sea validada por el sistema <br><b>Y</b> el usuario confirme su intención de proceder con el cambio<br/>
            <b>Entonces</b> la nueva clave será guardada y la información actualizada.<br/>
            <br>
            <b>Scenario 2: Cambiar nombre</b> <br/>
            <b>Dado que</b> el usuario quiera cambiar su nombre<br/>
            <b>Cuando</b> ingrese el nuevo nombre, esta sea validada por el usuario <br><b>Y</b> confirme su intención de proceder con el cambio <br/>
            <b>Entonces</b> el nuevo nombre será guardado y la información actualizada<br/>
            <br>
            <b>Scenario 3: Cambiar foto</b> <br/>
            <b>Dado que</b> el usuario quiera cambiar su foto <br/>
            <b>Cuando</b> ingrese la nueva foto, esta sea validada por el usuario <br><b>Y</b> confirme su intención de proceder con el cambio<br/>
            <b>Entonces</b> la nueva foto será guardada y la información actualizada<br/>
            <br>
            <b>Scenario 4: Cambiar número de celular</b> <br/>
            <b>Dado que</b> el usuario quiera cambiar su número de celular <br/>
            <b>Cuando</b> ingrese el nuevo número, esta sea validada por el sistema <br><b>Y</b> el usuario confirme su intención de proceder con el cambio <br/>
            <b>Entonces</b> el nuevo número será guardado y la información actualizada<br/>
            <br>
            <b>Scenario 5: Ingreso de datos inválidos</b> <br/>
            <b>Dado que</b> el usuario quiera cambiar su información <br/>
            <b>Cuando</b> ingrese datos inválidos<br/>
            <b>Entonces</b> se mostrará un mensaje de dato no válido<br/>
            <br>
            <b>Scenario 6: No cambiar información</b> <br/>
            <b>Dado que</b> el usuario no quiera cambiar su información <br/>
            <b>Cuando</b> aparezca el pop up para confirmar el cambio <br><b>Y</b> seleccione la opción para cancelar cambio<br/>
            <b>Entonces</b> el pop up desaparecerá y el cambio no se realizará<br/>
        <td>EP02</td>
    </tr>
    <tr>
        <td>US12</td>
        <td>Eliminar cuenta de usuario</td>
        <td><b>Como</b> Estudiante/Usuario de Movix 
        <b>Quiero</b> eliminar mi cuenta de usuario
        <b>Para</b> dejar de usar los servicios de la aplicación</td>
        <td>
            <b>Scenario 1: Estudiante/Usuario elimina cuenta de usuario </b> <br/>
            <b>Dado que</b> el Estudiante/Usuario desee eliminar su cuenta de usuario <br/>
            <b>Cuando</b> seleccione la opción de eliminar cuenta en su perfil <br><b>Y</b> confirme su intención para proceder con la operación<br/>
            <b>Entonces</b> el sistema eliminará la cuenta y todos los datos almacenados. <br/>
            <br>
            <b>Scenario 2: Estudiante/Usuario no elimina cuenta de usuario</b> <br/>
            <b>Dado que</b> el Estudiante/Usuario desee eliminar su cuenta de usuario <br/>
            <b>Cuando</b> niegue su intención para proceder con la operación<br/>
            <b>Entonces</b> el sistema regresará a la vista de su cuenta sin eliminar los datos.<br/>
        <td>EP02</td>
    </tr>
    <tr>
        <td>US13</td>
        <td>Publicar scooter en alquiler</td>
        <td><b>Como</b> Owner de un scooter eléctrico  
        <b>Quiero</b> crear publicaciones con la información y especificaciones de mi scooter
        <b>Para</b> que pueda ser alquilado por un cliente</td>
        <td>
            <b>Scenario 1: Owner publica su scooter en Movix </b> <br/>
            <b>Dado que</b> el Owner cuente con una cuenta en nuestra aplicación <br><b>Y</b> se encuentre el la opción de “Publicar scooter” <br/>
            <b>Cuando</b> llene todas las casillas obligatorias para publicar su scooter <br><b>Y</b> le de al botón “Publicar”<br/>
            <b>Entonces</b> el sistema le muestra un aviso de que su scooter ha sido publicado. <br/>
            <br>
           <b>Scenario 2: Owner cancela la publicación de su scooter en Movix</b> <br/>
            <b>Dado que</b> el Owner cuente con una cuenta en nuestra aplicación <br><b>Y</b> se encuentre el la opción de “Publicar scooter”  <br/>
            <b>Cuando</b> le de al botón de “Cancelar”<br/>
            <b>Entonces</b> el sistema le muestra un aviso de que se ha cancelado la publicación.<br/>
            <br>
           <b>Scenario 3: Owner no publica su scooter en Movix </b> <br/>
            <b>Dado que</b> el Owner cuente con una cuenta en nuestra aplicación <br><b>Y</b> se encuentre el la opción de “Publicar scooter” <br/>
            <b>Cuando</b> no llene todas las casillas obligatorias para publicar su scooter <br><b>Y</b> le de al botón “Publicar”<br/>
            <b>Entonces</b> el sistema le muestra un aviso de que se no ha completado la información requerida <br><b>Y</b> no se publica su scooter<br/>
        <td>EP03</td>
    </tr>
    <tr>
        <td>US14</td>
        <td>Visualizar un scooter en alquiler</td>
        <td><b>Como</b> Owner de un scooter eléctrico 
        <b>Quiero</b> visualizar las publicaciones con la información y especificaciones de mi scooter
        <b>Para</b> verificar que toda la información ingresada es correcta y actualizada.</td>
        <td>
            <b>Scenario 1: Owner visualiza su scooter en MoviTech </b> <br/>
            <b>Dado que</b> el Owner se encuentre en la aplicación de MoviRent <br/>
            <b>Cuando</b> se dirija a la opción de “Ver mis scooters”<br/>
            <b>Entonces</b> el sistema le mostrará la información de los scooters publicados.<br/>
            <br>
            <b>Scenario 2: Owner cancela la visualización de su scooter en MoviRent </b> <br/>
            <b>Dado que</b> el Owner se encuentre en la aplicación de MoviRent<br/>
            <b>Cuando</b> se dirija a la opción de “Ver mis scooters” <br><b>Y</b> le de al botón de “Salir” <br/>
            <b>Entonces</b> el sistema lo sacará de la ventana de “Ver mis scooters”<br/>
        <td>EP03</td>
    </tr>
    <tr>
        <td>US15</td>
        <td>Editar Scooter en alquiler</td>
        <td><b>Como</b> Owner de un scooter eléctrico 
        <b>Quiero</b> editar la publicación de mi scooter
        <b>Para</b> que la información proporcionada a los clientes esté siempre actualizada.</td>
        <td>
            <b>Scenario 1: Owner edita la publicación de su scooter en MoviRent</b> <br/>
            <b>Dado que</b> el Owner se encuentra en el apartado de “Mis scooters” <br><b>Y</b> le de al botón “Editar” de una publicación. <br/>
            <b>Cuando</b> actualice correctamente la información<br/>
            <b>Entonces</b> el sistema le muestra un aviso de que su scooter ha sido actualizado<br/>
            <br>
            <b>Scenario 2: Owner cancela la edición de la publicación de su scooter en MoviRent</b> <br/>
            <b>Dado que</b> el Owner se encuentra en el apartado de “Mis scooters” <br><b>Y</b> le de al botón “Editar” de una publicación. <br/>
            <b>Cuando</b> le de al botón de “Cancelar”<br/>
            <b>Entonces</b> el sistema cierra la ventana de edición de publicación<br/>
            <br>
            <b>Scenario 3: Owner no edita la publicación de su scooter en MoviRent</b> <br/>
            <b>Dado que</b> el Owner se encuentra en el apartado de “Mis scooters” <br><b>Y</b> le de al botón “Editar” de una publicación. <br/>
            <b>Cuando</b> ingrese incorrectamente la información <br><b>Y</b> le de al botón de “Aceptar”<br/>
            <b>Entonces</b> el sistema le muestra un aviso de que su scooter no ha sido actualizado.<br/>
        <td>EP03</td>
    </tr>
    <tr>
        <td>US16</td>
        <td>Eliminar scooter en alquiler</td>
        <td><b>Como</b> Owner 
        <b>Quiero</b> eliminar un scooter en alquiler
        <b>Para</b> mantener la integridad de la información almacenada.</td>
        <td>
            <b>Scenario 1: Owner borra scooter en alquiler</b> <br/>
            <b>Dado que</b> el Owner se encuentra en el apartado de “Mis scooters” <br><b>Y</b> le de al botón “Eliminar” de una publicación. <br/>
            <b>Cuando</b> confirme su intención de borrar los datos<br/>
            <b>Entonces</b> el sistema eliminará de la base de datos toda la información almacenada de ese scooter<br/>
            <br>
            <b>Scenario 2: Owner decide no borrar scooter </b> <br/>
            <b>Dado que</b> el Owner se encuentra en el apartado de “Mis scooters” <br><b>Y</b> le de al botón “Eliminar” de una publicación.<br/>
            <b>Cuando</b> o niegue su intención de borrar los datos <br/>
            <b>Entonces</b> el sistema no eliminará la información del scooter. <br/>
        <td>EP03</td>
    </tr>
    <tr>
        <td>US17</td>
        <td>Búsqueda de scooters cercano</td>
        <td><b>Como</b> cliente de Movix
        <b>Quiero</b> poder buscar scooters disponibles en mi distrito
        <b>Para</b> facilitar mi desplazamiento.</td>
        <td>
            <b>Scenario 1: Búsqueda de scooters cercanos</b> <br/>
            <b>Dado que</b> se encuentre en la sección de búsqueda de scooters <br/>
            <b>Cuando</b> el usuario use un filtro por distrito <br>
            <b>Entonces</b> se mostrará en una lista al usuario los scooters cercanos<br/>
            <br>
            <b>Scenario 2: No encuentra disponibilidad</b> <br/>
            <b>Dado que</b> el usuario use un filtro por distrito <br><b>Y</b> no hay scooters disponibles en esa zona <br/>
            <b>Cuando</b> el usuario realiza la búsqueda <br/>
            <b>Entonces</b> se muestra un mensaje indicando que no hay scooters disponibles en la zona seleccionada en este momento.<br/>
        <td>EP04</td>
    </tr>
    <tr>
        <td>US18</td>
        <td>Alquiler Scooter</td>
        <td><b>Como</b> Cliente de Movix
        <b>Quiero</b> alquilar un scooter
        <b>Para</b> llegar rápido a mi destino.</td>
        <td>
            <b>Scenario 1: Owner alquila un scooter en Movix</b> <br/>
            <b>Dado que</b> el Cliente se encuentra en el apartado de “Scooters” <br><b>Y</b> le de al botón “Ver detalles” de una publicación. <br><b>Y</b> se dé al botón de “Alquilar” <br/>
            <b>Cuando</b> el sistema le muestre la ventana de pago <br><b>Y</b> se complete la información requerida <br/>
            <b>Entonces</b> el sistema le mostrará un aviso de que el scooter ha sido alquilado con éxito y que puede ir a recogerlo para su uso.<br/>
            <br>
            <b>Scenario 2: Owner cancela el alquiler de un scooter en Movix </b> <br/>
            <b>Dado que</b> el Cliente se encuentra en el apartado de “Scooters” <br><b>Y</b> le de al botón “Ver detalles”de una publicación <br><b>Y</b> se dé al botón de “Alquilar” <br/>
            <b>Cuando</b> el sistema le muestre la ventana de pago <br><b>Y</b> le de al botón de “Cancelar” <br/>
            <b>Entonces</b> el sistema le mostrará un aviso de que se ha cancelado la operación<br/>
            <br>
            <b>Scenario 3: Owner no alquila un scooter en Movix</b> <br/>
            <b>Dado que</b> el Cliente se encuentra en el apartado de “Scooters” <br><b>Y</b> le de al botón “Ver detalles” de una publicación <br><b>Y</b> se dé al botón de “Alquilar”<br/>
            <b>Cuando</b> el sistema le muestre la ventana de pago <br><b>Y</b> no se complete la información requerida<br/>
            <b>Entonces</b> el sistema le mostrará un aviso de que no se ha podido proceder con el pago.<br/>
        <td>EP04</td>
    </tr>
    <tr>
        <td>US19</td>
        <td>Calificación y reseñas</td>
        <td><b>Como</b> cliente de Movix
        <b>Quiero</b> poder calificar y dejar reseñas sobre mi experiencia con scooters utilizados y la zona donde los tomé
        <b>Para</b> ayudar a otros usuarios a tomar decisiones informadas.</td>
        <td>
            <b>Scenario 1: Calificación y reseñas </b> <br/>
            <b>Dado que</b> el usuario tenga una cuenta registrada en la página web <br><b>Y</b> haya utilizado un vehículo recientemente <br/>
            <b>Cuando</b> el usuario acceda a la opción de dejar reseña <br><b>Y</b> seleccione la zona o tipo de scooter donde quiera dejar su reseña <br><b>Y</b> escriba su reseña <br><b>Y</b> haga clic en publicar <br/>
            <b>Entonces</b> se creará la reseña del usuario <br><b>Y</b> será visible para otros usuarios. <br/>
            <br>
            <b>Scenario 2: Ver reseñas de otros clientes </b> <br/>
            <b>Dado que</b> el usuario esté viendo las reseñas de otros usuarios sobre un scooter o una zona específica<br/>
            <b>Cuando</b> el usuario busque reseñas <br/>
            <b>Entonces</b> se mostrarán las calificaciones promedio y las reseñas de otros usuarios para ayudar al usuario a tomar una decisión informada sobre su experiencia. <br/>
        <td>EP04</td>
    </tr>
    <tr>
        <td>US20</td>
        <td>Visualizar historial de scooters alquilados</td>
        <td><b>Como</b> Cliente de Movix
        <b>Quiero</b> visualizar mi historial de scooters alquilados
        <b>Para</b> acceder fácilmente a su información</td>
        <td>
            <b>Scenario 1: Cliente visualiza su historial de scooters alquilados </b> <br/>
            <b>Dado que</b> el Cliente se encuentre en la aplicación de Movix <br><b>Y</b> ya ha alquilado scooters anteriormente<br/>
            <b>Cuando</b> se dirija a la opción de “Ver historial”<br/>
            <b>Entonces</b> el sistema le mostrará la información de los scooters que alquiló anteriormente.<br/>
            <br>
            <b>Scenario 2: Cliente no visualiza su historial de scooters alquilados</b> <br/>
            <b>Dado que</b> el Cliente se encuentre en la aplicación de Movix <br><b>Y</b> no ha alquilado scooters anteriormente <br/>
            <b>Cuando</b> se dirija a la opción de “Ver historial”<br/>
            <b>Entonces</b> el sistema mostrará un mensaje de que aún no ha alquilado ningún scooter. <br/>
        <td>EP05</td>
    </tr>
    <tr>
        <td>US21</td>
        <td>Borrar historial de scooters alquilados</td>
        <td><b>Como</b> Cliente de Movix
        <b>Quiero</b> o borrar mi historial de scooters alquilados
        <b>Para</b> ya no tener información que considere innecesaria. </td>
        <td>
            <b>Scenario 1: Cliente elimina su historial de scooters alquilados</b> <br/>
            <b>Dado que</b> el Cliente se encuentre en la aplicación de Movix <br><b>Y</b> ya ha alquilado scooters anteriormente <br/>
            <b>Cuando</b> se dirija a la opción de “Ver historial” <br><b>Y</b> le de al botón de “Borrar historial” <br><b>Y</b> confirme la acción<br/>
            <b>Entonces</b> el sistema le mostrará un mensaje de que su historial ha sido borrado <br><b>Y</b> ya no mostrará la información del historial<br/>
            <br>
            <b>Scenario 2: Cliente no elimina su historial de scooters alquilados</b> <br/>
            <b>Dado que</b> el Cliente se encuentre en la aplicación de Movix <br><b>Y</b> ya ha alquilado scooters anteriormente <br/>
            <b>Cuando</b> se dirija a la opción de “Ver historial” <br><b>Y</b> le de al botón de “Borrar historial” <br><b>Y</b> cancele la acción. <br/>
            <b>Entonces</b> el sistema le mostrará un mensaje de que su historial no ha sido borrado <br><b>Y</b> seguirá mostrando la información del historial.<br/>
        <td>EP05</td>
    </tr>
    <tr>
        <td>US22</td>
        <td>Adquirir plan</td>
        <td><b>Como</b> Cliente de Movix 
        <b>Quiero</b> Comprar un plan
        <b>Para</b> acceder a sus beneficios al usar la aplicación. </td>
        <td>
            <b>Scenario 1: Cliente compra una membresía en MoviTech </b> <br/>
            <b>Dado que</b> el Cliente se encuentra en el apartado de “Membresía” <br><b>Y</b> el Cliente no cuente con una membresía <br><b>Y</b> le de al botón “Subscribe” de una membresía. <br/>
            <b>Cuando</b> el sistema le muestre la ventana de pago <br><b>Y</b> se complete la información requerida <br/>
            <b>Entonces</b> el sistema le mostrará un aviso de que la membresía se ha comprado con éxito. <br/>
            <br>
            <b>Scenario 2: Cliente cancela compra una membresía en Movix </b> <br/>
            <b>Dado que</b> el Cliente se encuentra en el apartado de “Membresía” <br><b>Y</b> el Cliente no cuente con una membresía <br><b>Y</b> le de al botón “Subscribe” de una membresía. <br/>
            <b>Cuando</b> el sistema le muestre la ventana de pago <br><b>Y</b> se dé al botón de cancelar<br/>
            <b>Entonces</b> el sistema le mostrará un aviso de que se ha cancelado la compra de la membresía<br/>
            <br>
            <b>Scenario 3: Cliente no compra una membresía en Movix</b> <br/>
            <b>Dado que</b> el Cliente se encuentra en el apartado de “Membresía” Y le de al botón “Subscribe” de una membresía <br><b>Y</b> el Cliente no cuente con una membresía <br/>
            <b>Cuando</b> el sistema le muestre la ventana de pago <br><b>Y</b> no se complete la información requerida <br/>
            <b>Entonces</b> el sistema le mostrará un aviso de que la membresía no se ha adquirido<br/>
            <br>
            <b>Scenario 4: Cliente cambia de membresía en Movix</b> <br/>
            <b>Dado que</b> el Cliente se encuentra en el apartado de “Membresía” <br><b>Y</b> el Cliente cuente con una membresía <br><b>Y</b> le de al botón “Subscribe” de una membresía <br><b>Y</b> seleccione otra membresia diferente <br/>
            <b>Cuando</b> el sistema le muestre la ventana de pago <br><b>Y</b> se complete la información requerida<br/>
            <b>Entonces</b> el sistema le mostrará un aviso de que la membresía se ha comprado con éxito<br/>
        <td>EP06</td>
    </tr>
    <tr>
        <td>US23</td>
        <td>Cancelar suscripción </td>
        <td><b>Como</b> Cliente de Movix
        <b>Quiero</b> cancelar mi suscripción
        <b>Para</b> ya no seguir teniendo cobros de esta. </td>
        <td>
            <b>Scenario 1: Cliente cancela una membresía en Movix</b> <br/>
            <b>Dado que</b> el Cliente se encuentra en el apartado de “Membresía” <br><b>Y</b> el Cliente cuente con una membresía <br><b>Y</b> le de al botón “Cancelar Membresía” de una membresía. <br/>
            <b>Cuando</b> el sistema le muestre la ventana de cancelación <br><b>Y</b> se confirme la acción<br/>
            <b>Entonces</b> el sistema le mostrará un aviso de que la membresía se ha cancelado con éxito.<br/>
            <br>
            <b>Scenario 2: Cliente no cancela una membresía en MoviTech</b> <br/>
            <b>Dado que</b> el Cliente se encuentra en el apartado de “Membresía” <br><b>Y</b> el Cliente cuente con una membresía <br><b>Y</b> le de al botón “Cancelar Membresía” de una membresía.<br/>
            <b>Cuando</b> el sistema le muestre la ventana de cancelación <br><b>Y</b> no confirme la acción<br/>
            <b>Entonces</b> el sistema le mostrará un aviso de que la membresía no se ha cancelado.<br/>
        <td>EP06</td>
    </tr>
    <tr>
        <td>TS01</td>
        <td>Endpoint User </td>
        <td><b>Como</b> desarrollador de Movix
        <b>Quiero</b> hacer uso del endpoint /user
        <b>Para</b> gestionar los datos de los usuarios
        <td>
            <b>Scenario 1: Solicitud GET exitosa</b> <br/>
            <b>Dado que</b> el desarrollador hace una solicitud GET al endpoint /user<br>
            <b>Cuando</b> existan registros de usuarios disponibles<br/>
            <b>Entonces</b> el desarrollador recibe una respuesta 200 OK con una lista de usuarios.<br/>
            <br>
            <b>Scenario 2: Solicitud POST exitosa</b> <br/>
            <b>Dado que</b> el desarrollador quiere crear un nuevo usuario<br>
            <b>Cuando</b> los datos del usuario sean válidos y completos<br/>
            <b>Entonces</b> el desarrollador recibe una respuesta 201 Created con los detalles del usuario creado<br/>
            <br>
            <b>Scenario 3: Solicitud PUT exitosa</b> <br/>
            <b>Dado que</b> el desarrollador quiera actualizar un usuario existente <br>
            <b>Cuando</b> el usuario con el ID proporcionado exista<br/>
            <b>Entonces</b> el desarrollador recibe una respuesta 200 OK con los detalles del usuario actualizado.<br/>
            <br>
            <b>Scenario 4: Solicitud DELETE exitosa</b> <br/>
            <b>Dado que</b> el desarrollador quiera eliminar un usuario<br>
            <b>Cuando</b> el usuario con el ID proporcionado exista<br/>
            <b>Entonces</b> el desarrollador recibe una respuesta 200 OK confirmando la eliminación.<br/>
            <br>
            <b>Scenario 5: Solicitud GET fallida</b> <br/>
            <b>Dado que</b> el desarrollador hace una solicitud GET al endpoint /users<br>
            <b>Cuando</b> no existan registros de usuarios<br/>
            <b>Entonces</b> el desarrollador recibe una respuesta 404 Not Found.<br/>
            <br>
            <b>Scenario 6: Solicitud POST fallida</b> <br/>
            <b>Dado que</b> el desarrollador quiere crear un nuevo usuario<br>
            <b>Cuando</b> los datos del usuario estén incompletos o no sean válidos<br/>
            <b>Entonces</b> el desarrollador recibe una respuesta 400 Bad Request.<br/>
            <br>
            <b>Scenario 7: Solicitud PUT fallida</b> <br/>
            <b>Dado que</b> el desarrollador quiera actualizar un usuario <br>
            <b>Cuando</b> el usuario con el ID proporcionado no exista<br/>
            <b>Entonces</b> el desarrollador recibe una respuesta 404 Not Found.<br/>
            <br>
            <b>Scenario 8: Solicitud DELETE fallida</b> <br/>
            <b>Dado que</b> el desarrollador quiera eliminar un usuario<br>
            <b>Cuando</b> el usuario con el ID proporcionado no exista<br/>
            <b>Entonces</b> el desarrollador recibe una respuesta 404 Not Found.<br/>
            <br>
        <td>EP07</td>
    </tr>
    <tr>
        <td>TS02</td>
        <td>Endpoint Scooter </td>
        <td><b>Como</b> desarrollador de Movix
        <b>Quiero</b> hacer uso del endpoint /scooter
        <b>Para</b> gestionar los datos de los scooters
        <td>
            <b>Scenario 1: Solicitud GET exitosa</b> <br/>
            <b>Dado que</b> desarrollador hace una solicitud GET al endpoint /scooter<br>
            <b>Cuando</b> existan registros de scooters disponibles<br/>
            <b>Entonces</b> el desarrollador recibe una respuesta 200 OK con una lista de scooters<br/>
            <br>
            <b>Scenario 2: Solicitud POST exitosa</b> <br/>
            <b>Dado que</b> el desarrollador quiere crear un nuevo scooter<br>
            <b>Cuando</b> los datos del scooter sean válidos y completos<br/>
            <b>Entonces</b> el desarrollador recibe una respuesta 201 Created con los detalles del scooter creado<br/>
            <br>
            <b>Scenario 3: Solicitud PUT exitosa</b> <br/>
            <b>Dado que</b> el desarrollador quiera actualizar un scooter existente <br>
            <b>Cuando</b> el scooter con el ID proporcionado exista<br/>
            <b>Entonces</b> el desarrollador recibe una respuesta 200 OK con los detalles del scooter actualizado.<br/>
            <br>
            <b>Scenario 4: Solicitud DELETE exitosa</b> <br/>
            <b>Dado que</b> el desarrollador quiera eliminar un scooter<br>
            <b>Cuando</b> el scooter con el ID proporcionado exista<br/>
            <b>Entonces</b> el desarrollador recibe una respuesta 200 OK confirmando la eliminación.<br/>
            <br>
            <b>Scenario 5: Solicitud GET fallida</b> <br/>
            <b>Dado que</b> el desarrollador hace una solicitud GET al endpoint /scooter<br>
            <b>Cuando</b> no existan registros de scooter<br/>
            <b>Entonces</b> el desarrollador recibe una respuesta 404 Not Found.<br/>
            <br>
            <b>Scenario 6: Solicitud POST fallida</b> <br/>
            <b>Dado que</b> el desarrollador quiere crear un nuevo scooter<br>
            <b>Cuando</b> los datos del scooter estén incompletos o no sean válidos<br/>
            <b>Entonces</b> el desarrollador recibe una respuesta 400 Bad Request.<br/>
            <br>
            <b>Scenario 7: Solicitud PUT fallida</b> <br/>
            <b>Dado que</b> el desarrollador quiera actualizar un scooter <br>
            <b>Cuando</b> el scooter con el ID proporcionado no exista<br/>
            <b>Entonces</b> el desarrollador recibe una respuesta 404 Not Found.<br/>
            <br>
            <b>Scenario 8: Solicitud DELETE fallida</b> <br/>
            <b>Dado que</b> el desarrollador quiera eliminar un scooter<br>
            <b>Cuando</b> el scooter con el ID proporcionado no exista<br/>
            <b>Entonces</b> el desarrollador recibe una respuesta 404 Not Found.<br/>
            <br>
        <td>EP07</td>
    </tr>
    <tr>
        <td>TS03</td>
        <td>Endpoint Suscription </td>
        <td><b>Cómo</b> desarrollador de Movix
        <b>Quiero</b> hacer uso del endpoint /suscription
        <b>Para</b> gestionar los datos de los planes de suscripción
        <td>
            <b>Scenario 1: Solicitud GET exitosa</b> <br/>
            <b>Dado que</b> el desarrollador hace una solicitud GET al endpoint /suscription<br>
            <b>Cuando</b> existan registros de suscripciones disponibles<br/>
            <b>Entonces</b> el desarrollador recibe una respuesta 200 OK con una lista de planes.<br/>
            <br>
            <b>Scenario 2: Solicitud GET fallida</b> <br/>
            <b>Dado que</b> el desarrollador hace una solicitud GET al endpoint /suscriptión<br>
            <b>Cuando</b> no existan registros de suscripciones disponibles<br/>
            <b>Entonces</b> el desarrollador recibe una respuesta 404 Not Found.<br/>
            <br>
        <td>EP07</td>
    </tr>
    <tr>
        <td>TS04</td>
        <td>Endpoint Historial </td>
        <td><b>Como</b> desarrollador de Movix
        <b>Quiero</b> hacer uso del endpoint /historial
        <b>Para</b> gestionar los datos del historial de un usuario
        <td>
            <b>Scenario 1: Solicitud GET exitosa</b> <br/>
            <b>Dado que</b> desarrollador hace una solicitud GET al endpoint /historial<br>
            <b>Cuando</b> existan registros en el historial del usuario<br/>
            <b>Entonces</b> el desarrollador recibe una respuesta 200 OK con el historial<br/>
            <br>
            <b>Scenario 2: Solicitud DELETE exitosa</b> <br/>
            <b>Dado que</b> el desarrollador quiera eliminar un historial<br>
            <b>Cuando</b> el historial exista<br/>
            <b>Entonces</b> el desarrollador recibe una respuesta 200 OK confirmando la eliminación.<br/>
            <br>
            <b>Scenario 3: Solicitud GET fallida</b> <br/>
            <b>Dado que</b> el desarrollador hace una solicitud GET al endpoint /historial<br>
            <b>Cuando</b> no existan registros en el historial<br/>
            <b>Entonces</b> el desarrollador recibe una respuesta 404 Not Found.<br/>
            <br>
            <b>Scenario 4: Solicitud DELETE fallida</b> <br/>
            <b>Dado que</b> el desarrollador quiera eliminar un historial<br>
            <b>Cuando</b> el historial no exista<br/>
            <b>Entonces</b> el desarrollador recibe una respuesta 404 Not Found.<br/>
            <br>
        <td>EP07</td>
    </tr>
  <tr>
        <td>TS05</td>
        <td>Endpoint Reviews </td>
        <td><b>Como</b> desarrollador de Movix
        <b>Quiero</b> hacer uso del endpoint /reviews
        <b>Para</b> gestionar los datos de las reseñas
        <td>
            <b>Scenario 1: Solicitud GET exitosa</b> <br/>
            <b>Dado que</b> desarrollador hace una solicitud GET al endpoint /reviews<br>
            <b>Cuando</b> existan registros de reseñas disponibles<br/>
            <b>Entonces</b> el desarrollador recibe una respuesta 200 OK con una lista de reseñas<br/>
            <br>
            <b>Scenario 2: Solicitud POST exitosa</b> <br/>
            <b>Dado que</b> el desarrollador quiere crear una nueva reseña<br>
            <b>Cuando</b> los datos de la reseña sean válidos y completos<br/>
            <b>Entonces</b> el desarrollador recibe una respuesta 201 Created con los detalles de la reseña creada<br/>
            <br>
            <b>Scenario 3: Solicitud GET fallida</b> <br/>
            <b>Dado que</b> el desarrollador hace una solicitud GET al endpoint /reviews<br>
            <b>Cuando</b> no existan registros de reseñas<br/>
            <b>Entonces</b> el desarrollador recibe una respuesta 404 Not Found.<br/>
            <br>
            <b>Scenario 4: Solicitud POST fallida</b> <br/>
            <b>Dado que</b> el desarrollador quiere crear una nueva reseña<br>
            <b>Cuando</b> los datos de la reseña estén incompletos o no sean válidos<br/>
            <b>Entonces</b> el desarrollador recibe una respuesta 400 Bad Request.<br/>
        <td>EP07</td>
    </tr>
</table>


## 3.3. Impact Mapping.

## 3.4. Product Backlog.

<table border="1px">
  <tr>
    <th>#Orden</th>
    <th>User Story Id</th>
    <th>Título</th>
    <th>Descripción</th>
    <th>StoryPoints (1/2/3/5/8)</th>
  </tr>
  <tr>
    <td>01</td>
    <td>US01</td>
    <td>Implementación de la sección "Inicio" de la Landing Page</td>
    <td>Como visitante de la landing page Quiero visualizar la sección "Inicio" Para tener una primera vista del producto.</td>
    <td>3</td>
  </tr>
  <tr>
    <td>02</td>
    <td>US02</td>
    <td>Implementación de la sección "Sobre nosotros" de la Landing Page</td>
    <td>Como visitante de la landing page Quiero visualizar la sección "Sobre nosotros" Para tener información de la startup CiberMach.</td>
    <td>1</td>
  </tr>
  <tr>
    <td>03</td>
    <td>US03</td>
    <td>Implementación de la sección "Servicios" de la Landing Page</td>
    <td>Como visitante de la landing page Quiero visualizar la sección "Servicios" Para tener información de los servicios ofrecidos por la aplicación.</td>
    <td>3</td>
  </tr>
  <tr>
    <td>04</td>
    <td>US04</td>
    <td>Implementación de la sección "Planes" de la Landing Page</td>
    <td>Como visitante de la landing page Quiero visualizar la sección "Planes" Para tener información de las membresías de la aplicación</td>
    <td>3</td>
  </tr>
  <tr>
    <td>05</td>
    <td>US05</td>
    <td>Implementación de la sección "About the Team" de la Landing Page</td>
    <td>Como visitante de la landing page Quiero visualizar la sección "About the Team" Para tener información de los miembros que conforman la startup.</td>
    <td>3</td>
  </tr>
  <tr>
    <td>06</td>
    <td>US06</td>
    <td>Landing Page Responsiva a diferentes tamaños de pantalla</td>
    <td>Como visitante interesado Quiero que la landing page tenga un diseño responsivo Para acceder a ella desde cualquier dispositivo.</td>
    <td>5</td>
  </tr>
  <tr>
  <td>07</td>
  <td>US07</td>
  <td>Acceder a la aplicación desde la landing page</td>
  <td>Como visitante de la landing page Quiero poder acceder a la aplicación MoviRent desde la landing page Para comenzar a utilizar las funcionalidades ofrecidas</td>
  <td>3</td>
</tr>
<tr>
  <td>08</td>
  <td>US08</td>
  <td>Registrar usuario</td>
  <td>Como visitante de la aplicación web de MoviRent Quiero poder crear una cuenta personal Para comenzar a hacer uso de la aplicación como Owner/Cliente.</td>
  <td>3</td>
</tr>
<tr>
  <td>09</td>
  <td>US09</td>
  <td>Iniciar sesión</td>
  <td>Como Owner/Cliente de Movix Quiero iniciar sesión Para acceder a los beneficios que ofrece la aplicación.</td>
  <td>5</td>
</tr>
<tr>
  <td>10</td>
  <td>US10</td>
  <td>Visualizar perfil de usuario</td>
  <td>Como Owner/Cliente de Movix Quiero visualizar mi perfil personal Para visualizar mis datos actuales.</td>
  <td>5</td>
</tr>
<tr>
  <td>11</td>
  <td>US11</td>
  <td>Cambiar datos personales</td>
  <td>Como Owner/Cliente de Movix Quiero cambiar los datos asociados a mi perfil Para actualizar la información.</td>
  <td>3</td>
</tr>
<tr>
  <td>12</td>
  <td>US12</td>
  <td>Eliminar cuenta de usuario</td>
  <td>Como Owner/Cliente de Movix Quiero eliminar mi cuenta de usuario Para dejar de usar los servicios de la aplicación.</td>
  <td>3</td>
</tr>
<tr>
  <td>13</td>
  <td>US13</td>
  <td>Publicar scooter en alquiler</td>
  <td>Como Owner de un scooter eléctrico Quiero crear publicaciones con la información y especificaciones de mi scooter Para que pueda ser alquilado por un cliente.</td>
  <td>5</td>
</tr>
<tr>
  <td>14</td>
  <td>US14</td>
  <td>Visualizar un scooter en alquiler</td>
  <td>Como Owner de un scooter eléctrico Quiero visualizar las publicaciones con la información y especificaciones de mi scooter Para verificar que toda la información ingresada es correcta y actualizada.</td>
  <td>3</td>
</tr>
<tr>
  <td>15</td>
  <td>US15</td>
  <td>Editar Scooter en alquiler</td>
  <td>Como Owner de un scooter eléctrico Quiero editar la publicación de mi scooter Para que la información proporcionada a los clientes esté siempre actualizada.</td>
  <td>3</td>
</tr>
<tr>
  <td>16</td>
  <td>US16</td>
  <td>Eliminar scooter en alquiler</td>
  <td>Como Owner Quiero eliminar un scooter en alquiler Para mantener la integridad de la información almacenada.</td>
  <td>3</td>
</tr>
<tr>
  <td>17</td>
  <td>US17</td>
  <td>Búsqueda de scooters cercano</td>
  <td>Como cliente de Movix Quiero poder buscar scooters disponibles en mi distrito Para facilitar mi desplazamiento.</td>
  <td>8</td>
</tr>
<tr>
  <td>18</td>
  <td>US18</td>
  <td>Alquiler Scooter</td>
  <td>Como Cliente de Movix Quiero alquilar un scooter Para llegar rápido a mi destino.</td>
  <td>5</td>
</tr>
<tr>
  <td>19</td>
  <td>US19</td>
  <td>Calificación y reseñas</td>
  <td>Como cliente de Movix Quiero poder calificar y dejar reseñas sobre mi experiencia con scooters utilizados y la zona donde los tomé Para ayudar a otros usuarios a tomar decisiones informadas.</td>
  <td>3</td>
</tr>
<tr>
  <td>20</td>
  <td>US20</td>
  <td>Visualizar historial de scooters alquilados</td>
  <td>Como Cliente de Movix Quiero visualizar mi historial de scooters alquilados Para acceder fácilmente a su información.</td>
  <td>5</td>
</tr>
<tr>
  <td>21</td>
  <td>US21</td>
  <td>Borrar historial de scooters alquilados</td>
  <td>Como Cliente de Movix Quiero borrar mi historial de scooters alquilados Para ya no tener información que considere innecesaria.</td>
  <td>3</td>
</tr>
<tr>
  <td>22</td>
  <td>US22</td>
  <td>Adquirir plan</td>
  <td>Como Cliente de Movix Quiero comprar un plan Para acceder a sus beneficios al usar la aplicación.</td>
  <td>5</td>
</tr>
<tr>
  <td>23</td>
  <td>US23</td>
  <td>Cancelar suscripción</td>
  <td>Como Cliente de Movix Quiero cancelar mi suscripción Para ya no seguir teniendo cobros de esta.</td>
  <td>3</td>
</tr>
<tr>
  <td>24</td>
  <td>TS01</td>
  <td>Endpoint User</td>
  <td>Como desarrollador de Movix Quiero hacer uso del endpoint /user Para gestionar los datos de los usuarios.</td>
  <td>8</td>
</tr>
<tr>
  <td>25</td>
  <td>TS02</td>
  <td>Endpoint Scooter</td>
  <td>Como desarrollador de Movix Quiero hacer uso del endpoint /scooter Para gestionar los datos de los scooters</td>
  <td>8</td>
</tr>
<tr>
  <td>26</td>
  <td>TS03</td>
  <td>Endpoint Suscription</td>
  <td>Como desarrollador de Movix Quiero hacer uso del endpoint /suscription Para gestionar los datos de las suscripciones.</td>
  <td>8</td>
</tr>
<tr>
  <td>27</td>
  <td>TS04</td>
  <td>Endpoint Historial</td>
  <td>Como desarrollador de Movix Quiero hacer uso del endpoint /historial Para gestionar los datos de los historiales.</td>
  <td>8</td>
</tr>
<tr>
  <td>28</td>
  <td>TS05</td>
  <td>Endpoint Review</td>
  <td>Como desarrollador de Movix Quiero hacer uso del endpoint /reviews Para gestionar los datos de las reseñas</td>
  <td>8</td>
</tr>
</table>

<div style="page-break-before: always;"></div>

