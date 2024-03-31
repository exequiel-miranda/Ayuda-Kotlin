# Repositorio para aprender Kotlin
Este repositorio se actualizará todos los dias con el contenido visto en clase, si faltó a una clase o quiere encontrar el contenido en un solo lugar, puede visitar este repositorio, se subirán documentos, videos, noticias, guias, presentaciones, etc. Al igual que en el canal de Teams </br></br></br>

> Tabla de contenidos que veremos en el módulo:
> 1. ¿Qué es Kotlin?
> 2. ¿Qué es Android Studio y como instalarlo?
> 3. Partes de Android Studio
> 4. Carpetas de un proyecto
> 5. Creación de emuladores, HAXM
> 6. Stuff: como llevar el proyecto en USB, como usar git, etc
> 7. Activitys
> 8. Modificar y crear Activitys
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
## 1' ¿Qué es Kotlin?
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

## 4' Carpetas de un proyecto

![image](https://github.com/exequiel-miranda/Ayuda-Kotlin/assets/94820436/b0036f14-42ef-4b03-9e9a-99f17803bfbf)







