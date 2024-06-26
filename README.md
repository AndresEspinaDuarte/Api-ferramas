Hola bienvenido al tutorial de como manipular las "Apis" de ferremas


=====================================================================



PASOS:


Paso 1: Ingrese dentro de la carpeta que quiera usted revisar, en este caso serían los siguientes:
===================================================================================================
- Api_provedores
- Api_productos
- Api_usuario

Ya estando dentro de la carpeta a su elección, con click derecho escoja la opción de "Abrir en vscode"


Paso 2: Estando dentro del editor Visual studio code
====================================================

Como verá dentro de la carpeta estarán los múltiples componentes que harán funcionar el servicio, dirigase a "New terminal" y abra una nueva terminal.


Dentro de esta terminal, usted escribirá este comando: "python manage.py runserver"

Paso 2: Ejecutar frontend para consumir las API's
====================================================

Primero tener instalado nodejs , con los siguientes pasos:

"installs fnm (Fast Node Manager)"
winget install Schniz.fnm

"download and install Node.js"
fnm use --install-if-missing 20

"verifies the right Node.js version is in the environment"
node -v # should print `v20.15.0`

"verifies the right NPM version is in the environment"
npm -v # should print `10.7.0`


Segundo, ingresar a la carpeta de "frontend-api-ferramas" desde la terminal, luego ejecutar "npm i" para instalar todas las dependencias de nodejs y finalmente ejecutar el comando de "npm start"
se abrira una web donde se estaran consumiendo las 3 api debe hacer scroll hacia abajo para ver el contenido.


ADVERTENCIA:
====================


Si encuentra problemas con el paso anterior, puede ejecutar el siguiente comando ".\venv\Scripts\activate", esto iniciará el ambiente virtual de Python, donde se ejecutará el proyecto.



Paso 3: 


Le aparecerá un link directo a localhost, cuando este dentro vera que abajo tendrá instrucciones para redigirse a otras páginas, para ello utilice 
este metodo para ser redirigido "http://127.0.0.1:8000/", como en el caso de ejemplo que tendrá abajo:

Api_user caso:


"http://127.0.0.1:8000/Api_user"


Luego usted será enviado al root de la api ejecutada, por favor haga click en el link en rojo que marca la página, como aparecerá en el siguiente ejemplo: 


{
    "usuario": "http://127.0.0.1:8000/Api_userusuario/" <-----
}


Con esto usted ya estará dentro de la api para poder ingresar como borrar a su gusto los datos de la base de datos. 





EXTRA:
========================

Si usted quiere ver la documentación de la api, ya estando el servidor corriendo usted tendrá que ingresar el siguiente link "http://127.0.0.1:8000/docs"
