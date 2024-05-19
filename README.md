# Repositorio para aprender Kotlin
Este repositorio se actualizará todos los dias con el contenido visto en clase, si faltó a una clase o quiere encontrar el contenido en un solo lugar, puede visitar este repositorio, se subirán documentos, videos, noticias, guias, presentaciones, etc. Al igual que en el canal de Teams </br></br></br>
<br>
> Tabla de contenidos que veremos en el módulo:
> [1. ¿Qué es Kotlin?](#que-es-kolin)
> 2. ¿Qué es Android Studio y como instalarlo?
> 3. Partes de Android Studio
> 4. Creación de emuladores
> 5. Carpetas de un proyecto
> 6. Stuff: como llevar el proyecto en USB, como usar git, etc
> 7. Creación de un proyecto
> 8. Crear Activitys
> 9. Código inicial de una Activity
> 10. POO en Kotlin
> 11. Navegación entre pantallas
> 12. Elementos visuales con XML
> 13. Uso de Layouts
> 14. Uso camara, microfono y perifericos
> 15. Fragments
> 16. Navigation Drawer
> 17. Bottom Navigation
> 18. RecyclerView
> 19. Gradle
> 20. Conexión a Bases de datos en Oracle
> 21. Agregar datos
> 22. Mostrar datos
> 23. Eliminar datos
> 24. Actualizar datos
> 25. Conexión con Firebase
> 26. Corrutinas
> 27. Envío de correos eléctronicos
> 28. Notificaciones a tiempo real
> 29. Mapas y ubicación a tiempo real
> 30. ViewBinding
> 31. Inyección de dependencias con Dagger Hilt
> 32. Publicación de la aplicación en la Play Store
> 33. Testing
> 34. Agregar anuncios con Google Ads
> 35. Consumo de APIS con Retrofit
> 36. Arquitectura de software MvvM
> 37. Errores comunes


</br></br></br>
## ¿Qué es Kotlin?
![Kotlin_Icon](https://github.com/exequiel-miranda/Ayuda-Kotlin/assets/94820436/2f5cee5f-68e2-4526-9b9e-c319490ed405) </br>
Kotlin es un lenguaje de programación de código abierto creado por JetBrains que se ha popularizado gracias a que se puede utilizar para programar aplicaciones Android.
Este lenguaje es de tipado estático, es totalmente interoperable con código Java, o sea que en un mismo proyecto puedo tener código Kotlin y Java, lo que permite migrar de una forma gradual los proyectos de Java.

Historia de Kotlin </br>
La historia de Kotlin empieza en 2010, cuando JetBrains, la famosa empresa creadora de varios de los IDE más usados, como IntelliJ o WebStorm entre otros, publicó la primera versión de este lenguaje de programación.
En 2012 pasó a ser de código abierto, por lo que es un sistema de programación relativamente reciente.
De hecho, no tuvo mucha popularidad en sus cinco primeros años de vida, y hasta 2017, al anunciar que Google daría soporte a Kotlin, fue cuando finalmente empezó a ganar popularidad entre los desarrolladores de aplicaciones. Desde entonces, ha llegado a ser la opción preferida del 72 % de los programadores a la hora de desarrollar para Android. </br></br>

## 2' ¿Qué es Android Studio?
![Android_Studio_icon_(2023) svg (1)](https://github.com/exequiel-miranda/Ayuda-Kotlin/assets/94820436/86583ca7-abfc-4831-86c1-a7b89632321d)
Android Studio es el entorno de desarrollo integrado (IDE) oficial para el sistema operativo Android, creado por Google. Está diseñado específicamente para el desarrollo de aplicaciones Android y se basa en el software IntelliJ IDEA de JetBrains. </br>
Android Studio permite: </br>
<ul>
-Escribir código Kotlin y Java para las aplicaciones Android </br>
-Diseñar la interfaz de usuario </br>
-Crear y ejecutar emuladores Android </br>
-Depurar y probar tus aplicaciones en dispositivos reales o emuladores </br>
</ul>
<strong><h3>Versión actual</h3></strong>

Android Studio coloca el nombre de sus actualizaciones por orden alfabético y con un animal, actualmente (30 de marzo 2024) nos encontramos en la versión "Iguana",
Notas de la versión desde la página oficial: https://developer.android.com/studio/releases?hl=es-419 

</br>
 
<strong><h3>Versiónes anteriores de Android Studio</h3></strong>
<table>
    <tr>
      <th>Nombre</th>
      <th>Numero de versión</th>
    </tr>
    <tr>
      <td>Arctic Fox</td>
      <td>2020.3.1</td>
    </tr>
    <tr>
      <td>Bumblebee</td>
      <td>2021.1.1</td>
    </tr>
    <tr>
      <td>Chipmunk</td>
      <td>2021.2.1</td>
    </tr>
    <tr>
      <td>Dolphin</td>
      <td>2021.3.1</td>
    </tr>
    <tr>
      <td>Electric Eel</td>
      <td>2022.1.1</td>
    </tr>
    <tr>
      <td>Flamingo</td>
      <td>2022.2.1</td>
    </tr>
    <tr>
      <td>Giraffe</td>
      <td>2022.3.1</td>
    </tr>
    <tr>
      <td>Hedgehog</td>
      <td>2023.1.1</td>
    </tr>
    <tr>
      <td style="background-color: #cfc;">Versión actual: Iguana</td>
      <td style="background-color: #cfc;">2023.2.1</td>
    </tr>
    <tr>
      <td style="background-color: #fffacd;">Versión siguiente: Jellyfish (Medusa)</td>
      <td style="background-color: #fffacd;">2023.3.1</td>
    </tr>
  </table>
  <p>Avisaré en el canal de Teams salga esta nueva versión🫣</p>

 
PEQUEÑO PARENTESIS: para el sistema operativo Android, las versiones tambien están ordenadas alfabeticamente pero en lugar de animales usan golosinas:

  <h2>Versiones de Android (Sistema operativo para teléfonos)</h2>
  <table>
    <tr>
      <th>Nombre</th>
      <th>Número de versión</th>
      <th>Fecha de lanzamiento</th>
    </tr>
    <tr>
      <td>Android Beta</td>
      <td>-</td>
      <td>2007</td>
    </tr>
    <tr>
      <td>Android 1.0 Apple Pie</td>
      <td>1.0</td>
      <td>23 de septiembre de 2008</td>
    </tr>
    <tr>
      <td>Android 1.1 Banana Bread (Petit Four)</td>
      <td>1.1</td>
      <td>9 de febrero de 2009</td>
    </tr>
    <tr>
      <td>Android 1.5 Cupcake</td>
      <td>1.5</td>
      <td>27 de abril de 2009</td>
    </tr>
    <tr>
      <td>Android 1.6 Donut</td>
      <td>1.6</td>
      <td>15 de septiembre de 2009</td>
    </tr>
    <tr>
      <td>Android 2.0 Eclair</td>
      <td>2.0</td>
      <td>26 de octubre de 2009</td>
    </tr>
    <tr>
      <td>Android 2.2 Froyo</td>
      <td>2.2</td>
      <td>20 de mayo de 2010</td>
    </tr>
    <tr>
      <td>Android 2.3 Gingerbread</td>
      <td>2.3</td>
      <td>6 de diciembre de 2010</td>
    </tr>
    <tr>
      <td>Android 3.0 Honeycomb</td>
      <td>3.0</td>
      <td>22 de febrero de 2011</td>
    </tr>
    <tr>
      <td>Android 4.0 Ice Cream Sandwich</td>
      <td>4.0</td>
      <td>18 de octubre de 2011</td>
    </tr>
    <tr>
      <td>Android 4.1 Jelly Bean</td>
      <td>4.1</td>
      <td>9 de julio de 2012</td>
    </tr>
    <tr>
      <td>Android 4.4 KitKat</td>
      <td>4.4</td>
      <td>31 de octubre de 2013</td>
    </tr>
    <tr>
      <td>Android 5.0 Lollipop</td>
      <td>5.0</td>
      <td>12 de noviembre de 2014</td>
    </tr>
    <tr>
      <td>Android 6.0 Marshmallow</td>
      <td>6.0</td>
      <td>5 de octubre de 2015</td>
    </tr>
    <tr>
      <td>Android 7.0 Nougat</td>
      <td>7.0</td>
      <td>22 de agosto de 2016</td>
    </tr>
    <tr>
      <td>Android 8.0 Oreo</td>
      <td>8.0</td>
      <td>21 de agosto de 2017</td>
    </tr>
    <tr>
      <td>Android 8.1 Oreo</td>
      <td>8.1</td>
      <td>5 de diciembre de 2017</td>
    </tr>
    <tr>
      <td>Android 9 Pie</td>
      <td>9</td>
      <td>6 de agosto de 2018</td>
    </tr>
    <tr>
      <td>Android 10 "Q" </td>
      <td>10</td>
      <td>3 de septiembre de 2019</td>
    </tr>
    <tr>
      <td>Android 11 Red Velvet Cake (No oficial) o solamente “R”</td>
      <td>11</td>
      <td>8 de septiembre de 2020</td>
    </tr>
    <tr>
      <td>Android 12 Snow Cone (No oficial) o solamente “S”</td>
      <td>12</td>
      <td>4 de octubre de 2021</td>
    </tr>
    <tr>
      <td>Android 13 Tiramisu</td>
      <td>13</td>
      <td>15 de agosto de 2022</td>
    </tr>
    <tr>
      <td>Android 14 UpsideDown Cake</td>
      <td>14</td>
      <td>4 de octubre de 2023</td>
    </tr>
   <tr>
      <td>Android 15 VanillaIceCream</td>
      <td>15</td>
      <td>Aun no sale, está planeado para abril-mayo de 2024</td>
    </tr>
  </table>
<Strong><h2>¿Cómo instalar Android Studio?</h2></Strong></br>
Para instalarlo debemos descargar el ejecutable desde la página oficial:</br>
https://developer.android.com/studio?hl=es-419  </br>
Luego, clic en Descargar Android Studio </br>

![image](https://github.com/exequiel-miranda/Ayuda-Kotlin/assets/94820436/43c81044-866a-4c2a-8821-5be6c652ea22) </br>
 
Video de como instalarlo: </br>
Aunque solo es dar clic en "Siguiente" "Siguiente" "Finalizar" </br>
 

https://github.com/exequiel-miranda/Ayuda-Kotlin/assets/94820436/69a4e76e-f3a7-493f-a04c-cf835cecd687


Documentación oficial de como instalar Android Studio paso a paso:
https://developer.android.com/codelabs/basic-android-kotlin-compose-install-android-studio?hl=es-419#2

## 3' Partes de Android Studio

https://github.com/exequiel-miranda/Ayuda-Kotlin/assets/94820436/5c580be5-22f2-4ca7-9ed3-b9932d2d99c5

</br>

https://github.com/exequiel-miranda/Ayuda-Kotlin/assets/94820436/21278fbc-3fd0-4ffb-a368-46cc532b271f

</br>

https://github.com/exequiel-miranda/Ayuda-Kotlin/assets/94820436/fde4040c-8431-48ca-b6ae-e3f908048053

</br>

https://github.com/exequiel-miranda/Ayuda-Kotlin/assets/94820436/ccaedd4f-2a73-4296-bec6-6d8f0041ec93

</br>

https://github.com/exequiel-miranda/Ayuda-Kotlin/assets/94820436/baaa13bc-25cd-45eb-81b7-78854343b328

</br>

https://github.com/exequiel-miranda/Ayuda-Kotlin/assets/94820436/c605bd48-1cde-4ae2-acf9-bda35e3b92a5

## 4' Creación de emuladores
1- Para crear un emulador y ejecutar las aplicaciones que diseñemos debemos dar clic en la opción "Device manager": </br>
![option](https://github.com/exequiel-miranda/Ayuda-Kotlin/assets/94820436/83bfead4-76bc-4006-ab31-02b2e6fbfbfe)
 </br>
Aqui encontraremos los emuladores o el telefono fisico si lo tenemos conectado. </br>
![image](https://github.com/exequiel-miranda/Ayuda-Kotlin/assets/94820436/4003f4bb-cfa5-4c2a-b572-3e0d8930f7f2) </br></br>
2- Clic en Create virtual device </br>
![add](https://github.com/exequiel-miranda/Ayuda-Kotlin/assets/94820436/901246b6-7d83-487b-a16f-8bf53e7a2f1f)
 </br>
3- Luego, debemos completar los pasos para crear el emulador, primero, seleccionamos que teléfono queremos (Recomiendo el Pixel 6):  </br>
![image](https://github.com/exequiel-miranda/Ayuda-Kotlin/assets/94820436/b5f714a6-2876-4d48-ab68-86654bdcae01) </br>
Seleccionamos la versión de sistema operativo Android para nuestro emulador (Recomiendo R o si no, S):  </br>
![image](https://github.com/exequiel-miranda/Ayuda-Kotlin/assets/94820436/5b2802ea-58b9-48a3-8d83-e7206eb4b5a2) </br>
Le colocamos un nombre (Podemos dejar el nombre por defecto: </br>
![image](https://github.com/exequiel-miranda/Ayuda-Kotlin/assets/94820436/6795b522-9faa-45b1-9661-93f70627ef52)</br>
Y luego clic en Finalizar



### 4.1' ¿Qué hacer si no funciona el emulador en mi computadora?
Los emuladores Android están optimizados para procesadores Intel, en algunos casos, los procesadores AMD no permiten emular o virtualizar teléfonos Android. También puede pasar que aunque tengamos procesadores Intel no podamos instalar emuladores debido a una mala configuración de la computadora.

Como primer sugerencia, si el emulador no funciona en nuestra computadora, podemos conectar nuestro telefono personal Android a nuestra computadora por cable (teniendo habilitada la depuración por USB) y podremos instalar las aplicaciones en neustro teléfono personal sin necesidad de emuladores. Para habilitar la depuración por USB en nuestro teléfono lo veremos más adelante en este repositorio, cuando vayamos a instalar una aplicación.

Cosas que realizar si no funciona el emulador en mi computadora (Intel o AMD) </br>
![image](https://github.com/exequiel-miranda/Ayuda-Kotlin/assets/94820436/2fc6efe4-6459-43d7-bdfb-49d41e54f871)
 </br> Esta advertencia aparece cuando damos clic en Ejecutar, y nos muestra la alerta que no podemos ejecutar el emulador por que nuestra computadora no tiene el driver HAXM, damos clic en <strong>OK</strong> y se empezará a descargar automaticamente.
Pero, en muchos casos tendremos el siguiente error:</br>
![image](https://github.com/exequiel-miranda/Ayuda-Kotlin/assets/94820436/cadf7470-4475-4af6-8b24-bdf71d95968a) </br>
Esto es por que nuestra maquina no acepta este driver. </br>
Paso 1: Entrar al panel de control </br>
![image](https://github.com/exequiel-miranda/Ayuda-Kotlin/assets/94820436/a23e4b19-efdf-4e99-a809-d22e272e1639) </br>
Luego, en Desinstalar un programa </br>
![image](https://github.com/exequiel-miranda/Ayuda-Kotlin/assets/94820436/39576661-1431-4404-b222-f5c274a01655) </br>
Y en el panel de la izquierda, seleccionamos "Activar o desactivar las caracteristicas de Windows" </br>
![image](https://github.com/exequiel-miranda/Ayuda-Kotlin/assets/94820436/139ac833-6e23-4b42-b706-74532680bb51) </br>
Y nos aseguramos de tener habilitado "Hyper V" y "Plataforma del hipervisor Windows" </br>
![image](https://github.com/exequiel-miranda/Ayuda-Kotlin/assets/94820436/48f266f7-691c-4012-8612-de3a0765c4b5)
![image](https://github.com/exequiel-miranda/Ayuda-Kotlin/assets/94820436/32aa122f-14e8-424c-8a72-a77ae5501b44) </br>
Reiniciamos el equipo y realizarmos una prueba del emulador</br></br>

Paso 2: Si lo anterior no funciona, vamos a realizar otra configuración, dentro de Android Studio vamos a la configuración, y luego en SDK Manager, el SDK es "System Developed Kit" o Kit de Desarrollo de Software en español, es un kit de desarrollo que nos proporciona Android para poder programar aplicaciones.
Vamos a configurarlo.</br>
![image](https://github.com/exequiel-miranda/Ayuda-Kotlin/assets/94820436/fa3c01c3-965b-4840-a61b-5677bae9a2ef) </br>
Clic en la pestaña SDK Tools </br>
![Screenshot 2024-04-01 095553](https://github.com/exequiel-miranda/Ayuda-Kotlin/assets/94820436/f084cc70-4542-4361-b8a9-7073696c969a)
 </br>
Y nos aseguramos de tener el instalador de HAXM </br>
Si no está, lo marcamos, y precionamos en Aceptar, esto hará que se descargue y se instale
![image](https://github.com/exequiel-miranda/Ayuda-Kotlin/assets/94820436/68f8f654-aec7-4f47-a28b-1a14c71682cb) </br></br>

Si lo anterior no funciona, existe una ultima alternativa, habilitar la Tecnologia de virtualización de Intel desde el BIOS, pero, cada marca de computadoras tiene una BIOS diferente, hay muchas diferentes versiones de BIOS, asi que, les sugiero buscar en YouTube "¿Cómo habilitar la tecnologia de virtualización de Intel en mi computadora ______" 
Antes de entrar a la BIOS (Por que es peligroso y podemos arruinar nuestra computadora si tocamos algo que no debemos en la BIOS) primero verifiquemos si tenemos esta tecnologia de virtualización desactivada, lo podemos ver desde el Administrador de Tareas en el apartado de "Rendimiento".</br>
![image](https://github.com/exequiel-miranda/Ayuda-Kotlin/assets/94820436/67fc5d6c-feb0-4061-b15c-39dfa02e22e7)
</br></br>

## 5' Carpetas de un proyecto
En el modo de vista "Android" encontramos la siguiente estructura de carpetas que conforman nuestro proyecto: </br>
![image](https://github.com/exequiel-miranda/Ayuda-Kotlin/assets/94820436/c8574002-8f2f-40c5-838c-db5d5aa56c8f) </br>
El proyecto o módulo principal que contiene a toda nuestra aplicación se llama "app".
Dentro de este módulo principal encontramos a las carpetas:
- manifest
- kotlin + java
- res

1. La carpeta <strong>manifest</strong> solamente contiene el archivo <strong>AndroidManifest.xml</strong> no contiene ni va a xontener nada más, solo este archivo: </br>
![image](https://github.com/exequiel-miranda/Ayuda-Kotlin/assets/94820436/2968d99d-7795-493c-bffb-763d00474de2) </br>
AndroidManifest.xml: Este fichero describe la aplicación Android y sus configuraciones externas. Se define su nombre, paquete, icóno, estilos, etc. Se indican las Activitys, los servicios y los proveedores de contenido de la aplicación. También se declaran los permisos que requerirá la aplicación. </br>
Ejemplo de como es el AndroidManifest.xml:</br>
![image](https://github.com/exequiel-miranda/Ayuda-Kotlin/assets/94820436/75f6f161-b2e0-4e8d-9892-eaa96bfa8a09) </br>


2. La carpeta <strong>kotlin + java</strong> en versiones anteriores llamada solamente <strong>java</strong> contiene toda la parte de programción de nuestra aplicación. Por ejemplo, si quiero programar la conexión a la base de datos, pues ese código estará en esta carpeta (Especificamente, dentro de la carpeta o "paquete" que definimos al crear nuestra aplicación). Para llevar un orden, este paquete debe llevar nuestro nombre seguido del nombre de la aplicación, todo separado por puntos).
Al creear una nueva aplicación, viene por defecto el código de la MainActivity o pantalla inicial, además, podemos ver dos carpetas en verde que sirven para hacer testeos de nuestra aplicación: </br>
![image](https://github.com/exequiel-miranda/Ayuda-Kotlin/assets/94820436/38a646d5-ca98-456c-ad0b-70913046997d)
</br>Si tenemos 10 pantallas, aqui encontraremos los archivos de código de esas 10 pantallas.</br>

3. La carpeta <strong>res</strong> que su nombre completo sería <strong>resources</strong> contiene los recursos visuales de nuestra aplicación.
   Esta carpeta se divide en más carpetas para organizar estos recursos visuales de nuestra app.
   - drawable
   - layout
   - mipmap
   - values
   - xml
  
  ![image](https://github.com/exequiel-miranda/Ayuda-Kotlin/assets/94820436/f379f22f-63c6-4edd-9338-0b39fcb4bd7f)</br>

  Que se explican a continuación:</br>
  - <strong>drawable:</strong> Contiene todas las imágenes, iconos, videos de nuestra aplicación, por ejemplo, el logo de la empresa, la imagénes de los productos, etc.
  - <strong>layout:</strong> Contiene las Activitys o pantallas de nuestra aplicación, por ejemplo, la pantalla del login, pantalla de productos, etc. Esta carpeta es muy importante, y siempre la tendremos abierta para tener a mano el diseño de nuetras pantallas.
  - <strong>mipmap:</strong> Contiene el icóno de la aplicación, y también se puede utilizar para guardar iconos de extensiones .svg o .xml.
  - <strong>values:</strong> Contiene ficheros XML de recursos de la aplicación, estos recursos los escribimos aqui, y luego solo los mandamos a llamar, como por ejemplo cadenas de texto (strings.xml), estilos (styles.xml), colores (colors.xml), esto simplifica la creación de aplicaciones por que los definimos al inicio de la aplicación y ya no tenemos que estar recondando el eslogan o los colores que usamos repetidas veces en nuestra aplicación.
  - <strong>xml:</strong> Contiene otros ficheros XML de datos utilizados por la aplicación.


Entonces, las carpetas mas importantes y que siempre tendremos abiertas serán: </br>
<strong>1. kotlin + java -> nuestro paquete</strong> Para el código de programación de las pantallas</br>
<strong>2. res -> layout</strong>  Para el diseño de las pantallas
</br>
![image](https://github.com/exequiel-miranda/Ayuda-Kotlin/assets/94820436/35c60898-db30-4a03-808d-70503f92f3d9) </br>

## 6' Stuff: como llevar el proyecto en USB, como usar git, etc
### Como iniciar git en un proyecto
1. Damos clic derecho en la carpeta 'app' </br>
![image](https://github.com/exequiel-miranda/Ayuda-Kotlin/assets/94820436/3752a78e-230e-450e-b593-f3f9cb6b22eb) </br>
Luego en Open In... y en "Explorer"</br>
![image](https://github.com/exequiel-miranda/Ayuda-Kotlin/assets/94820436/37be7463-63cd-445c-b7f4-0ebf639b995e)</br>
Y nos abre la carpeta que contiene el proyecto, ahi podemos dar clic derecho, "Open Git Bash Here"</br>
![image](https://github.com/exequiel-miranda/Ayuda-Kotlin/assets/94820436/0055088c-1069-429b-8648-2f7a2aeb300b)</br>

### Como llevarse el proyecto en una USB
Seguimos los pasos anteriores y llegamos a la carpeta del proyecto, solamente retrocedemos una carpeta atrás</br>
![image](https://github.com/exequiel-miranda/Ayuda-Kotlin/assets/94820436/5ee3776c-319c-4716-b26f-88fed3300fd5)</br>
Y ya nos podemos llevar la carpeta completa en su USB copiando y pegando toda la carpeta:</br>
![mod screenshot 2024-04-21 124823](https://github.com/exequiel-miranda/Ayuda-Kotlin/assets/94820436/4fa5e1e0-bff4-46de-85d8-e2e1d6223d51)</br>

### ¿Cómo habilitar la New UI en Android Studio?
En versiones anteriores, Android Studio tenia una versión diferente a la que vemos en el laboratorio:</br>
![image](https://github.com/exequiel-miranda/Ayuda-Kotlin/assets/94820436/7696326e-daa9-461f-a763-d35c46d4fda5) </br>
Pero, en la versión Hedgehog (Una versión anterior a Iguana) se actualizó a una interfaz mucho más intuitiva, y con menos iconos y funciones innecesarias en pantalla:</br>
![image](https://github.com/exequiel-miranda/Ayuda-Kotlin/assets/94820436/32379ea7-9b42-41ed-818a-eb5b6bdb46b2)
Es por eso que algunos tutoriales de hace algunos meses aun tienen la interfaz anterior.</br>
Pero, si usted quiere habilitar esta nueva interfaz, debe seguir estos pasos:</br>
Clic en File -> Settings
![Untitled](https://github.com/exequiel-miranda/Ayuda-Kotlin/assets/94820436/cb4a96a9-faef-4797-95ff-e90b3aa7f43d)
Luego, clic en la primer categoria de Apariencia, seleccionar New UI y habilitarla:</br>
![image](https://github.com/exequiel-miranda/Ayuda-Kotlin/assets/94820436/7979c1d2-89f2-4cfd-830d-2007d6524ec9)</br>
Pedirá que reiniciemos Android Studio y listo


## 7' Creación de un nuevo proyecto

Damos clic en el menú principal </br>
![Menu](https://github.com/exequiel-miranda/Ayuda-Kotlin/assets/94820436/0ffb6f7b-4523-4e1e-bc23-099ca45873ea)  </br>
Luego en File -> New -> New project </br>
![new](https://github.com/exequiel-miranda/Ayuda-Kotlin/assets/94820436/ec07303c-f11f-4091-9096-bdbb7a84b2e7) </br>
Y podremos ver las plantillas de aplicaciones que podemos crear </br>
![image](https://github.com/exequiel-miranda/Ayuda-Kotlin/assets/94820436/157bdbdc-f073-434a-80ef-f32ba0b46696) </br>
Por el momento, crearemos aplicaciones usando la plantilla Empty Views Activity, luego utilizaremos todas. </br>
Precionamos clic en "Next"

Luego, tendremos que configurar nuestra aplicación llenando estos campos: </br>
![image](https://github.com/exequiel-miranda/Ayuda-Kotlin/assets/94820436/b45de4d8-1d76-4a46-be2d-10b0febf38bb) </br>

- <strong>Name:</strong> le colocamos el nombre a nuestra aplicación (Se sugiere no utilizar la letra ñ ni simbolos).
- <strong>Package name:</strong> el nombre del paquete, un paquete es como una carpeta, aqui se almacenará el código de programación de nuestra aplicación y sirve también como identificador de nuestra aplicación, por ejemplo, no pueden haber dos aplicaciones en la Play Store con el mismo nombre de paquete.
- <strong>Save location:</strong> Ubicación donde se guardará el proyecto (Debe ser en una carpeta vacia, no se recomienda solamente seleccionar la USB, por ejemplo <strong>D:/</strong> por que se pondrán varias carpetas esparcidas en la usb, la manera correcta sería <strong>D:/carpeta/</strong> y guradarlo dentro de esta carpeta vacia).
- <strong>Language:</strong> Si bien podemos programar aplicaciones con Kotlin y con Java, nosotros solamente utilizaremos Kotlin.
- <strong>Minimum SDK:</strong> La versión minima en la que se podrá instalar la aplicación, si elejimos "Android 8" la aplicación se podrá instalar en teléfonos con Android 8 o superior. NOTA: No es recomendable irnos a la primer versión (4.1.1), por que, aunque podríamos instalar en todos los telefonos, perdemos funcionalidades que se han agregado en versiones recientes. Tampoco se recomienda seleccionar la versión más reciente de android (14.0) por que, aunque tengamos todas las nuevas funcionalidades, no hay muchos telefonos con esta versión, la mayoria de teléfonos actuales tienen versiones menores (11, 12, 13), entonces, un punto medio y que recomiendo elegir es Android 8.
- <strong>Build configuration language:</strong> Gradle (Que es lo que nos ayuda a compilar y agregar librerias a mi proyecto) tiene dos formas de crearse, usando Groovy (versión anterior) o usando Kotlin (versión nueva), nosotros dejaremos la nueva versión de Kotlin (que ya viene por defecto).
  
Entonces, al crear una aplicación, nos quedará asi: </br>
![image](https://github.com/exequiel-miranda/Ayuda-Kotlin/assets/94820436/b45de4d8-1d76-4a46-be2d-10b0febf38bb)</br>



## 8' Crear Activitys
Una activity es una pantalla de nuestra aplicación. </br>
Para crear una Activity nueva, debemos dar clic derecho en la carpeta Layout</br>
![image](https://github.com/exequiel-miranda/Ayuda-Kotlin/assets/94820436/bef6f6f3-09db-4f79-b547-6ccfb6e2bb5e)</br>
Luego, clic en New - Activity - elegimos una plantilla (En este caso Empty View Activity)</br>
![crearactivity](https://github.com/exequiel-miranda/Ayuda-Kotlin/assets/94820436/3d44d9ad-09f7-46ea-b091-be5b5c920268)</br>
Y le colocamos un nombre (Se aconseja que empiecen con "activity_" </br>
![image](https://github.com/exequiel-miranda/Ayuda-Kotlin/assets/94820436/af03f97f-8d17-4a50-85b2-3a07ec95888e)</br>


## 9' Código inicial de una Activity

Es el código que viene por defecto para cada pantalla, por ejemplo, si usted crea la pantalla "Login" esa pantalla tendrá un archivo de código Kotlin para programar los botones, animaciones, funciones, etc.

Ejemplo:
  ~~~kotlin
1 package com.example.mi_aplicacion
2
3 import android.os.Bundle
4 import android.widget.Button
5 import android.widget.TextView
6 
7 class MainActivity : AppCompatActivity() {
8
9    override fun onCreate(savedInstanceState: Bundle?) {
10       super.onCreate(savedInstanceState)
11       setContentView(R.layout.activity_main)
12    }
13 }
~~~

Y es apartir de este código que agregaremos funcionalidad a la pantalla.
Antes de eso, explicaré linea a linea que hace este código:
Este es el paquete en el que se encuentra el código, el paquete es la carpeta principal que definimos su nombre al crear la aplicación. </br>
  ~~~kotlin
 1 package com.example.mi_aplicacion
~~~
</br>
Luego, tenemos el apartado de los imports, que importa las librerias, por ejemplo, al conectarnos a una base de datos Oracle necesitamos una libreria, entonces, aqui es donde se manda llamar. Tambien se manda a llamar las librerias de los boones, editText y demás elementos de manera automatica.

  ~~~kotlin
3 import android.os.Bundle
4 import android.widget.Button
5 import android.widget.TextView
~~~
</br>
Luego, encontramos la clase principal, que extiende de la clase AppCompatActivity, sabemos que una clase extiende de otra por los dos puntos.


![clasemod](https://github.com/exequiel-miranda/Ayuda-Kotlin/assets/94820436/cd2c7252-28ec-43a9-a0d0-7aa8d3c3bc68)
 </br> </br>
Luego, Dentro de la clase principal, encontramos el método onCreate, este método es el que se ejecuta cuando iniciamos la aplicación.

  ~~~kotlin
9    override fun onCreate(savedInstanceState: Bundle?) {
10       super.onCreate(savedInstanceState)
11       setContentView(R.layout.activity_main)
12    }
~~~
<h2>Explicación linea a linea del método onCreate:</h2>
Esta línea define el método onCreate, el cual es un método de ciclo de vida obligatorio que se llama cuando se crea la actividad por primera vez. La palabra clave override indica que se está sobrescribiendo esta función.

savedInstanceState: Este parámetro es un objeto Bundle que contiene el estado de la actividad guardado en una instancia previa. Puede ser null si la actividad se está creando por primera vez o si no se ha guardado ningún estado.
  ~~~kotlin
9    override fun onCreate(savedInstanceState: Bundle?) {
~~~
Luego,
  ~~~kotlin
10       super.onCreate(savedInstanceState)
~~~
El propósito de llamar a super.onCreate es realizar las tareas iniciales que son comunes a todas las actividades, como inicializar los componentes de la actividad y configurar los oyentes de eventos. Al llamar a super.onCreate antes de escribir nuestro código en el método onCreate, nos aseguramos que todas las tareas básicas se realicen correctamente antes de continuar con la lógica específica de la activity.
La palabra clave super se utiliza para acceder a los métodos de la clase base. En este caso, super se refiere a la clase Activity.
El parámetro savedInstanceState es un objeto Bundle que contiene el estado de la actividad guardado en una instancia previa. Si la actividad se está creando por primera vez, este parámetro será null, si no, como su nombre lo indica, guarda el estado de la instancia.

  ~~~kotlin
11       setContentView(R.layout.activity_main)
~~~
Esta línea establece el diseño de la interfaz de usuario de la actividad. El parámetro R.layout.activity_main hace referencia al archivo de diseño XML activity_main.xml que define la interfaz de usuario de la actividad principal.








