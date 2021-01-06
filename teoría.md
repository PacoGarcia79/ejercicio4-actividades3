1. Introducción
Los desarrolladores necesitan gestionar el código de los proyectos en los cuales están trabajando.
Nos encontramos ante una realidad con escenarios en los que muchos profesionales incorporan código al
proyecto, un código vivo, que puede cambiar una vez dado por finalizado o bien por peticiones de los clientes,
adaptación al mercado, corrección de errores… Con estos cambios se van creando versiones, pero ¿cómo
podemos gestionarlos para trabajar de la manera más óptima posible y almacenando los cambios por si
tuviéramos que recuperar alguna instrucción o dato? Aquí es donde entra en juego el control de versiones.
El control de versiones es la capacidad de recordar todos los cambios que se realizan tanto en la
estructura de directorios como en el contenido de los archivos. Permitiendo las siguientes acciones
generalmente:
Recuperar un documento, una carpeta, o un proyecto en un momento concreto de su desarrollo.
Mantener un cierto control de los cambios que se realizan sobre documentos, archivos o proyectos
que comparten varias personas o un equipo de trabajo, por lo que es útil cuando se hace necesario
saber qué cambios se hacen, quién los hace y cuándo se realizan.
2. Terminología
Existen una serie de términos que se utilizan y son comunes para la mayoría de las herramientas de
control de versiones
• Repositorio: Lugar donde se almacenan todos los datos y los cambios.
• Revisión o versión: Una revisión es una versión concreta de los datos almacenados.
• Tag: Cuando se crea una versión concreta en un momento determinado del desarrollo de un proyecto
se le pone una etiqueta, de forma que se pueda localizar y recuperar en cualquier momento.
• Tronco (trunk): Línea principal de desarrollo de un proyecto.
• Rama o ramificar (branch): Las ramas son copias de archivos , carpetas o proyectos. Cuando se crea
una rama se crea una bifurcación del proyecto y se crean dos líneas de desarrollo.
• Checkout: Crear una copia de trabajo del proyecto, o de archivos y carpetas del repositorio en el
equipo local. Por defecto se obtiene la última versión, aunque también se puede indicar una versión
concreta.
• Commit o checkin: Se realiza commit cuando se confirman los cambios realizados en local para
integrarlos al repositorio.
• Merge: Una fusión consiste en unir los cambios realizados sobre uno o varios archivos en una única
revisión.
• Conflicto: Ocurre en situaciones en la que el sistema no es capaz de fusionar los cambios (por
ejemplo, dos usuarios han cambiado la misma línea en el mismo momento). Este usuario deberá́
resolver el conflicto combinando los cambios o eligiendo uno de ellos.
3. GIT
Git es un sistema de control de versiones distribuido que tiene como objetivo mejorar la
velocidad de desarrollo de los proyectos, facilitar el trabajo en equipo y llevar el control de cambios,
todo ello con un diseño simple.
En Git, la forma que se almacena los datos recibe el nombre de snapshot o instantánea. Cada
instantánea almacena el estado del código en un momento determinado.
