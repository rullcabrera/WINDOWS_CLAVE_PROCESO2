author: Raúl Cabrera Garcia
summary: Guía Rápida Recuperación Contraseña Windows (Deshabilitar utilman)
id: WINDOWS_CLAVE_PROCESO2
categories: codelab,markdown
environments: Web
status: Published
feedback link: Enlace github para los issue

# Guía Rápida Rec. contraseña en Windows (Deshabilitar Utilman)

## Página 1
Duration: 00:02:00

### Lo que haremos será reforzar uno de los *“trucos”*, que aún tenemos disponible en Windows. Cuando no sabemos la clave de usuario y queremos cambiarla. A través de la modificación de la utilidad *“Utilman.exe”*.

* Primero arrancamos con un *CD instalación de Windows*, podríamos también crear un *“USB arrancable”* o con un *“LiveCD Linux”*.
    * Arrancamos y nos dirigimos a *Reparar equipo* → *Solucionar problemas* → ***Símbolo del sistema***. Nos abre un terminal.

![Foto5_WClave2](img/foto5.jpg)

* En la Terminal, tenemos que irnos a la carpeta *“System32”*. Aquí están las herramientas de **Accesibilidad**; entre ellas ***“Utilman.exe”***. Cambiamos de unidad donde tengamos instalado *Windows*. En mi caso es la unidad **D:** Casi siempre será **C:**

Positive
: **cd Windows\System32**

![Foto6_WClave2](img/foto6.jpg)

* Buscaremos el archivo ***“Utilman.exe”***.
Si queremos conservarlo para habilitarlo de nuevo en el futuro. Le pondremos un nombre que nos lo haga recordar, sino simplemente renombramos por cualquier cosa. Que deje también de ser un ***“.exe”***. Nos quedaría algo así.

![Foto7_WClave2](img/foto7.jpg)

Positive
: Reiniciamos el equipo y comprobaremos si, efectivamente. Ya no se ejecuta el fichero al darle a la opción de **“Accesibilidad”**.

[Enlace al video-demostracion de la resolucion](https://vimeo.com/648339815)

Negative
: Como añadido, en mi caso con este único paso me ha funcionado correctamente. Pero si no fuese así. Habría que gestionar los permisos del archivo ***“Utilman.exe”***. En *Propiedades* → *seguridad* → *Denegar todo*.
Ya no podrán **“ejecutar”** dicho archivo.
