# Repositorio de SUKIGSX
Buenas a todos, en esta pagina encontraras scripts desarrollados en Bash, los cuales los voy creando para realizar procecesos que son utiles en mi dia a dia y creo que no esta de mas compartirlos para que os puedan servir como a mi. El codido es abierto y se pueden modificar y ajustar a vuestras necesisades. Lo unico que pido es que se haga una referencia al creador que en este caso soy yo.

Espero os gusten y que os sean utiles para realizar vuestras tareas y gestiones.

## CronManager
Un script interactivo en Bash que permite gestionar fácilmente el crontab del usuario, sin necesidad de recordar la sintaxis de cron.
Incluye un menú con colores, validaciones, ayuda integrada y soporte para borrar varias tareas a la vez.

[Mas informacion del script](https://github.com/sukigsx/CronManager)

## Linux User Manager

Este script en **Bash** es una herramienta interactiva para gestionar usuarios, carpetas compartidas, permisos y configuración de **Samba** en sistemas **Linux**.

Este script está diseñado para facilitar tareas comunes de administración de usuarios y compartición de archivos en redes locales.
Es especialmente útil en entornos educativos, pequeñas oficinas o para usuarios que deseen automatizar configuraciones de red local.

[Mas informacion del script](https://github.com/sukigsx/LinuxUserManager)

## BackupManager

Este script es una herramienta interactiva para gestionar copias de seguridad (backups) usando rsync, tanto locales como remotas, y con soporte opcional de notificaciones por Telegram.

[Mas informacion del script](https://github.com/sukigsx/BackupManager)

## Ejecutar Scripts

El script proporcionado es una herramienta interactiva que permite a los usuarios ejecutar scripts Bash almacenados en un directorio específico.

Tambien permite la instalacion de los script de SUKIGSX, alojados en su repositorio.

En resumen: ejecutar_scripts.sh es tu “gestor de scripts” personal con autoinstalador, auto-update y una interfaz tipo menú que simplifica copiar, ejecutar, guardar o limpiar tus utilidades Bash desde un solo punto.

[Mas informacion del script](https://github.com/sukigsx/ejecutar_scripts)

## Montar Unidades

Este script de Bash es un programa interactivo que proporciona una interfaz de usuario para configurar y gestionar el montaje automático de unidades compartidas de un servidor Samba en un sistema Linux.


[Mas informacion del script](https://github.com/sukigsx/montar_unidades)

## Instalar Software

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

## Alias Basshrc modificar este aqui el nuevo

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

## Intrusos

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

## Dispositivos Conectados

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

## Configurar Sshd

Este script en Bash es para configurar opciones específicas del servidor SSH de una manera interactiva. A continuación, se proporciona una descripción detallada de su funcionamiento:

- Realiza la conexión a Internet y, si hay conexión, verifica e instala el software necesario.
- Luego, verifica y actualiza el script si es necesario.
- Después, presenta un menú interactivo al usuario con varias opciones relacionadas con la configuración del servidor SSH.
- Las opciones del menú permiten activar o desactivar la autenticación por contraseña en el servidor SSH.
- También muestra información sobre el estado de la configuración, la conexión a Internet, la instalación del software y la actualización del script.
- El menú se ejecuta en un bucle hasta que el usuario elige salir (opción 99).

Se iran añadiendo nuevas opciones al menu

[Mas informacion del script](https://github.com/sukigsx/configurar_sshd)

## Organizador Ficheros

Este script es útil para organizar archivos por tipo de extension en diferentes carpetas dentro de un directorio de destino, facilitando la gestión y clasificación de los archivos.

Resumen funcional del script `OrganizadorFicheros`

Presentación inicial
- Muestra una pantalla con:
  - **Nombre** del script
  - **Descripción**
  - **Versión**
  - **Autoría**
  - **Estado** de conexión / actualización

Comprobaciones previas

1. Conexión a Internet
- Verifica si hay red disponible antes de continuar.

2. Actualización automática
- Si dispone de conexión, clona su propio repositorio de GitHub.
- Se reemplaza a sí mismo si detecta una versión más reciente.

3. Software imprescindible
- Comprueba que existan las siguientes herramientas: `git`, `curl`, `diff`, `ping`, `nano`, `find`.
- Si falta alguna, intenta instalarla con `apt`.

Modo de uso flexible
El script acepta **cuatro parámetros** en línea de comandos:

| Parámetro           | Descripción                                               | Ejemplo                           |
|---------------------|-----------------------------------------------------------|-----------------------------------|
| `ruta_origen`       | Carpeta a escanear                                        | `/home/usuario/Descargas`         |
| `ruta_destino`      | Carpeta donde se ordenará                                 | `/home/usuario/Ordenado`          |
| `copiar` \| `mover` | Acción sobre los archivos                                 | `mover`                           |
| `borrar_si` \| `borrar_no`| Eliminar o conservar la carpeta de origen           | `borrar_si`                       |

[Mas informacion del script](https://github.com/sukigsx/organizador_ficheros)

## Cloudflare_ddns

Actualizador dinámico de DNS (DDNS) que utiliza la API de Cloudflare para mantener actualizados los registros DNS de un dominio.

A continuación, se describe su funcionamiento:

- Variables de configuración:
    Configura credenciales de acceso a Cloudflare (AUTH_EMAIL, AUTH_KEY, etc.), el dominio, subdominios, TTL, y opciones de proxy.
    Define los datos para enviar notificaciones a Slack/Discord.

- Comprobación periódica de la IP pública. Obtiene la IP pública actual usando Cloudflare o servicios como api.ipify.org. Verifica si la IP es válida           mediante un regex. Consulta de registros DNS

- Recorre la lista de subdominios definidos en RECORD_NAMES. Obtiene el registro DNS tipo A del subdominio usando la API de Cloudflare. Si el registro no existe, informa el error.

- Actualización de registros DNS. Si la IP pública actual difiere de la IP almacenada en el registro DNS, la actualiza mediante la API de Cloudflare. Envía notificaciones a Slack o Discord sobre el estado de la actualización. Bucle infinito:

- Repite las comprobaciones y actualizaciones cada cierto tiempo, definido por TIEMPO_COMPROBAR_IPS. Este script automatiza el mantenimiento de registros DNS para conexiones con IP dinámica.

- DOCKER COMPOSE
    Este archivo de Docker Compose configura un servicio para ejecutar el script de actualización dinámica de DNS (DDNS). Explicación:
    Servicio ddns-updater:
    -build: Construye una imagen Docker usando el archivo Dockerfile ubicado en https://github.com/sukigsx/cloudflare_ddns.git. container_name: Nombra al contenedor como ddns_updater. Variables de entorno (environment):
    - Proporciona credenciales de Cloudflare (AUTH_EMAIL, AUTH_KEY, etc.). Define los subdominios (RECORD_NAMES) a actualizar, TTL, y opciones como proxy. Configura el intervalo para verificar la IP (TIEMPO_COMPROBAR_IPS) y parámetros de notificación. restart: always: Asegura que el contenedor se reinicie automáticamente si falla.

Este servicio automatiza el despliegue del actualizador DDNS en un contenedor Docker.

[Mas informacion del script](https://github.com/sukigsx/cloudflare_ddns)

## ControlAplicacionesLinux

Control de ejecución de aplicaciones en tu sistema Linux
Si tienes varios usuarios en tu equipo Linux (Debian o basado en Debian), esta herramienta te permite restringir el acceso a determinadas aplicaciones para usuarios específicos del sistema.

La diseñé para bloquear la ejecución de programas que no quiero que mis hijos puedan abrir, pero también puede usarse para gestionar permisos de ejecución en entornos multiusuario o de trabajo.

[Mas informacion del script](https://github.com/sukigsx/ControlAplicacionesLinux.git)

## Ssh-Manager

- Gestionar conexiones SSH de múltiples servidores.

- Generar y distribuir claves públicas SSH automáticamente.

- Conectarse a los servidores desde nuevas terminales.

- Revocar accesos cuando ya no se desee conectar.

- Comprobar dependencias y actualizarse automáticamente desde GitHub.

[Mas informacion del script](https://github.com/sukigsx/ssh-manager.git)

# Soporte y Contacto

Puedes ponerte en contacto en mi [Correo Electronico](mailto:scripts@mbbsistemas.es).

Dime tus sujerencias, tus criticas y tus ideas para poder mejorar.
Estare encantado de recivir vuestras ideas e intentar ponerlas en marcha.
UN SALUDO A TODOS.
