# Repositorio de SUKIGSX
Buenas a todos, en esta pagina encontraras scripts desarrollados en Bash, los cuales los voy creando para realizar procecesos que son utiles en mi dia a dia y creo que no esta de mas compartirlos para que os puedan servir como a mi. El codido es abierto y se pueden modificar y ajustar a vuestras necesisades. Lo unico que pido es que se haga una referencia al creador que en este caso soy yo.

Espero os gusten y que os sean utiles para realizar vuestras tareas y gestiones.

-----------------------

## Linux User Manager

Este script en **Bash** es una herramienta interactiva para gestionar usuarios, carpetas compartidas, permisos y configuración de **Samba** en sistemas **Linux**.

 🛠 Funcionalidad Principal

- **Nombre:** Linux User Manager
- **Propósito:** Configurar y administrar usuarios, directorios compartidos, permisos de acceso y Samba para compartir archivos en red.


 ✅ Requisitos y Verificaciones

- **Ejecutado como root:**
  Verifica si se tienen privilegios administrativos. Si no, solicita autenticación mediante `sudo`.

- **Comprobación de conexión a internet:**
  Necesaria para actualizaciones y la instalación de software requerido.

- **Verificación e instalación de software necesario:**
  Comprueba que herramientas como `git`, `diff`, `curl`, etc., estén instaladas. Si no están, las instala automáticamente.

- **Actualización automática del script desde GitHub:**
  Si hay una versión más reciente en el repositorio, la descarga y reemplaza el script actual.

 📁 Gestión de Carpeta Base

- Solicita al usuario una ruta para la carpeta base que contendrá los recursos compartidos.
- Si no existe la ruta, permite crearla automáticamente.
- Almacena esta ruta temporalmente para uso posterior en el script.


 📋 Interfaz de Menú Interactivo

Muestra un menú desde donde el usuario puede:

- Administrar usuarios del sistema.
- Gestionar carpetas compartidas.
- Asignar permisos a las carpetas compartidas.
- Configurar Samba para compartir archivos.
- Seleccionar o cambiar la carpeta base.
- Ver ayuda.
- Salir del script.


 🧹 Limpieza y Salida

- Al presionar `Ctrl+C` o elegir la opción de salir, elimina archivos temporales y muestra un mensaje de despedida.


 📝 Resumen

Este script está diseñado para facilitar tareas comunes de administración de usuarios y compartición de archivos en redes locales.
Es especialmente útil en entornos educativos, pequeñas oficinas o para usuarios que deseen automatizar configuraciones de red local.


## MEGATOOLS

Esta utilidad desarrollada en bash proporciona una forma conveniente para que el usuario interactúe con el programa.
Seleccionando opciones del menú y realizando diferentes tareas relacionadas con la gestión del sistema y la obtención de información.


[Mas informacion del script](https://github.com/sukigsx/MegaTools_gui)

## EJECUTAR SCRIPTS

El script proporcionado es una herramienta interactiva que permite a los usuarios ejecutar scripts Bash almacenados en un directorio específico.

Tambien permite la instalacion de los script de SUKIGSX, alojados en este repositorio.


[Mas informacion del script](https://github.com/sukigsx/ejecutar_scripts)

## MONTAR UNIDADES

Este script de Bash es un programa interactivo que proporciona una interfaz de usuario para configurar y gestionar el montaje automático de unidades compartidas de un servidor Samba en un sistema Linux.


[Mas informacion del script](https://github.com/sukigsx/montar_unidades)

## INSTALAR SOFTWARE

Este script esta pensado para la instalacion de software de forma automatizada.

- Actualizar el sistema en entornos gnome y plasma por apt.
- Poder instalar otras maquinas de forma remota por ssh.
- Instalacion de repositorios.
- Instalacion de una gran cantidad de software incluida en repositorios.
- Instalacion software externo a los repositorios de forma automatica.
- Buscar equipos por tu red, para poder instalar en remoto.
- Conectar a equipo de red por ssh.
- Ejecuta una terminal de comandos.
- Instalacion en equipos remotos.


[Mas informacion del script](https://github.com/sukigsx/instalar_software)

## ALIAS_BASHRC

Este script en bash proporciona varias funciones para gestionar alias en un sistema Linux. Aquí está el resumen de lo que hace cada función:

- opciones_alias
- actualizar_alias
- desistalar_alias
- listar_alias
- crear_alias
- borrar_alias
- editar fichero de alias
- menu_alias
- backup_alias
- restore_alias


[Mas informacion del script](https://github.com/sukigsx/alias_bashrc)

## ORGANIZADOR DE FICHEROS

Este script es útil para organizar archivos por tipo en diferentes carpetas dentro de un directorio de destino, facilitando la gestión y clasificación de los archivos.


[Mas informacion del script](https://github.com/sukigsx/organizador_ficheros)

## INTRUSOS

Este script en Bash es un programa que permite comprobar la red local en busca de intrusos.

Opciones del menu principal:

- Crear el fichero de IPs permitidas.
- Ver el fichero de IPs permitidas.
- Borrar el fichero de IPs permitidas.
- Editar/Añadir IPs al fichero de IPs permitidas.
- Escanear la red en busca de intrusos.
- Instalar un servicio para comprobación automática.
- Borrado de datos.
- Mostrar ayuda.
- Salir.


[Mas informacion del script](https://github.com/sukigsx/intrusos)

## DISPOSITIVOS CONECTADOS

Este script en bash es una herramienta de administración para verificar el estado de dispositivos en una red.

Opciones del Menú:

- Opción 0: Actualizar el Script Llama a la función actualizar_script que probablemente se define en algún lugar del script.

- Opción 1: Incluir Dispositivos Muestra una lista de dispositivos actuales. Solicita al usuario ingresar el nombre y la dirección IP de un dispositivo. Verifica la validez de la dirección IP y el nombre. Agrega la entrada al archivo de configuración si la información es válida.

- Opción 2: Eliminar Dispositivos Muestra una lista de dispositivos actuales. Solicita al usuario ingresar el nombre del dispositivo a eliminar (puede ser múltiple). Elimina las entradas correspondientes del archivo de configuración.

- Opción 3: Editar el Fichero de Configuración Abre el editor nano para editar el archivo de configuración.

- Opción 4: Desinstalar Pregunta al usuario si está seguro de desinstalar. Elimina el archivo de configuración y el propio script si el usuario confirma.

- Opción 5: Escanear Dispositivos Comprueba la existencia de un archivo de configuración. Realiza un escaneo de dispositivos en la red utilizando el comando ping. Muestra el estado de cada dispositivo (encendido o apagado).

- Opción 90: Ayuda No hay detalles sobre lo que hace esta opción en el script proporcionado.

- Opción 99: Salir Llama a la función ctrl_c y sale del script.


[Mas informacion del script](https://github.com/sukigsx/dispositivos_conectados)

## CONFIGURAR SSHD

Este script en Bash es para configurar opciones específicas del servidor SSH de una manera interactiva. A continuación, se proporciona una descripción detallada de su funcionamiento:

- Realiza la conexión a Internet y, si hay conexión, verifica e instala el software necesario.
- Luego, verifica y actualiza el script si es necesario.
- Después, presenta un menú interactivo al usuario con varias opciones relacionadas con la configuración del servidor SSH.
- Las opciones del menú permiten activar o desactivar la autenticación por contraseña en el servidor SSH.
- También muestra información sobre el estado de la configuración, la conexión a Internet, la instalación del software y la actualización del script.
- El menú se ejecuta en un bucle hasta que el usuario elige salir (opción 99).

Se iran añadiendo nuevas opciones al menu

[Mas informacion del script](https://github.com/sukigsx/configurar_sshd)


# Soporte y Contacto

Puedes ponerte en contacto en mi [Correo Electronico](mailto:scripts@mbbsistemas.es).

Dime tus sujerencias, tus criticas y tus ideas para poder mejorar.
Estare encantado de recivir vuestras ideas e intentar ponerlas en marcha.
UN SALUDO A TODOS.
