# angular-curso-completo
Todo sobre angular

# Pasos para crear un nuevo proyecto en angular 
- Primero instalar el cliente de angular a través del siguiente comando: npm install -g @angular/cli
2- crear una carpeta y luego posicionarse sobre ella, despues ejecutar el siguiente comando para crear un nuevo proyecto en angular: ng new nombre-proyecto

# Pasos para levantar nuestra aplicacion de angular
- Ejecutar el comando: ng serve -o , Este comando levanta un servidor web y ademas se abra nuestro navegador web de manera automatica
- Detener el servidor con las teclas: ctrl + c.

# Abrir proyecto en VS code
- Debemos abrir el programa en modo administrado o podriamos tener algunos problemas al momento de ejecutar algunos comandos si no estamos en modo administrador.
- Dar click derecho y ejecutar como administrador

# Error de Powershell 
La ejecucion de scripts esta deshabilitada en este sistema 
- Para corregirlo debemos abrir nuestro powershell como administrador y ejecutar el siguiente comando: Set-ExecutionPolicy Unrestricted, y aceptamos cualquier mensaje que nos muestre.
- Para confirmar si ya se han modificado los valores se ejecuta el comando: Get-ExecutionPolicy.


# Ejecutar nuestra app de angular cuando no tenemos la carpeta de node modules 
- Ir a vs code, abrir la carpeta del proyecto, ir a la terminal desde vs code y ejecutar el comando: npm install.

# Extenciones de vs code para trabajar con Angular
-Angular Language Service
-Angular files
-Angular Support  
-Prettier - Code Formatter
-Angular 2 TypeScript Emmet (para la creacion de codigo html).
-Bracket Pair Colorizer 2
-Bootstrap 4, Font awesome 4, Font Awesome 5 Free & Pro snippets

# Creacion de nuevos componentes usando el CLI de Angular
- ng generate component nombreComponente 
- ng g c nombreComponente (Forma simplificada)
- ng g c nombreComponente --skipTests=true (Para evitar que se cree el archivo de laboratorio)

