				   Manual de Git y GitHub:

					¿Qué es Git?

Git es un software de control de versiones, pensado para mejorar la eficiencia, 
compatibilidad y mantenimiento de las diferentes versiones de una aplicación o código fuente. 
Su función es llevar un registro estructurado de los diferentes cambios que ha sufrido un objeto,
 coordinando el trabajo que varias personas han podido realizar sobre el mismo, compartiéndolo 
en un repositorio común. Sus características principales son:
1)	Es un software libre
2)	Posibilidad de mantener un historial completo de todas las versiones de un proyecto
3)	Aporta rapidez en la gestión de diferentes ramas de trabajo y el mezclado de versiones. 
Incluye las herramientas necesarias para navegar por el historial de desarrollo de forma no lineal.
4)	Ofrece una gestión distribuida, cada programador tendrá una copia del historial de todo el 
desarrollo, y todo cambio que se realice se propagará por igual por todos los repositorios locales.
Las ramas creadas podrán ser fusionadas.
5)	Permite una gestión muy eficiente de proyectos grandes, debido a la fluidez en la gestión 
de versiones de archivos.
6)	Toda versión previa implica una notificación de un cambio posterior en cualquiera de ello
a ese cambio. (Autenticación criptográfica de historial)
7)	Es compatible con GitHub y Microsoft Visual Studio Code


					¿Qué es GitHub?

Github es un portal creado para alojar el código de las aplicaciones de cualquier desarrollador. 
La plataforma está creada para que los desarrolladores suban el código de sus aplicaciones y 
herramientas, y que como usuario no sólo puedas descargarte la aplicación, sino también entrar a
su perfil para leer sobre ella o colaborar con su desarrollo. La web utiliza el sistema de control
de versiones Git. Así pues, Github es un portal para gestionar las aplicaciones que utilizan el 
sistema Git. Además de permitirte mirar el código y descargarte las diferentes versiones de una 
aplicación, la plataforma también hace las veces de red social conectando desarrolladores con usuarios 
para que estos puedan colaborar mejorando la aplicación.

					Pasos para empezar:

Para descargar e instalar git habrá que entrar a la página de Git y darle click al botón de Downloads 
for Windows. Una vez descargada, dale click al archivo con el formato Git-version.exe. Al inicio 
preguntará por permisos para ejecutar el instalador, a lo cual debemos responder que sí. Como muchos de 
los instaladores en Windows, debemos de aceptar las opciones por defecto y darle Next (siguiente) a todo 
hasta que nos salga el botón de instalar.

Para crear un repositorio de GitHub, en primer lugar habrá que crearse una cuenta en la plataforma desde 
la página principal. Una vez hecho esto, nos iremos a nuestro perfil (Arriba a la derecha) y le daremos 
a “Tus repositorios”. En esta página nos aparecerá una opción de “New”. Ahí podremos crear un nuevo 
repositorio, del cual se nos pedirán los datos necesarios.

					Principales comandos:
-Git init  (Crea un nuevo repositorio)
-Touch “Archivo” (Crea un nuevo archivo)
-Git add “Archivo” (Se añade el archivo al repositorio)
-Git commit –m “Mensaje” (Se crea un commit)
-Git branch “Nueva Rama” (Se crea una nueva rama)
-Git checkout “Nueva Rama” (Se cambia de rama a la rama que introduzcamos)
-Git log  (Se muestra un listado de los commit realizados)
-Git remote add origin “URL del repositorio remoto”  (Se realiza una 
conexión ente el repositorio local y el remoto)
-Git push –set upstream origin master   (Se crea una copia de los archivos 
hallados en el repositorio local al repositorio remoto)
-Git fetch  (Se crea una copia de los archivos del repositorio remoto al 
repositorio local)

