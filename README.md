# springboot-angular4
Proyecto base para Spring Boot and Angular 4.

El proyecto está separado en dos:
* springboot
* angular4

El proyecto **springboot** funciona como contenedor del proyecto **angular4**.
El proyecto **angular4** se puede ejecutar de manera independiente a **springboot**.

Se puede implementar en dos arquitecturas:
* Proyectos separados (se aplica en éste prototipo)
* En el mismo proyecto

## Requerimientos
* Java 1.8
* Maven 3.3.9
* Spring Tool Suite: 3.9.0.RELEASE
* Spring Boot: 1.5.6 RELEASE
* Angular 4
* Node.js: 6.11.1

## Ambientación de entorno de desarrollo
1. Se asume tener instalado JDK 1.8
1. Instalar Node.js para Angular
   * Linux: [Instalación de Node.js](https://www.digitalocean.com/community/tutorials/how-to-install-node-js-on-ubuntu-16-04)
   * Windows: Descargar el instalador y ejecutar: [nodejs.org/es/download](https://nodejs.org/es/download/)
   1. Verificar en una consola: `node -v & npm -v`
1. Instalar Angular-CLI
   1. Ejecutar el comando: `npm install -g @angular/cli`
   1. Verificar la instalación de Angular-CLI: `ng -v`

## Ejecución de las aplicaciones
1. Para ejecutar el proyecto **anguar4**, entrar a la carpeta del proyecto y ejecutar: `npm start`
1. Para ejecutar **springboot**, entrat a la carpeta del proyecto y ejecutar:
   1. Construir: `mvn clean install`
   1. Ejecutar: `mvn spring-boot:run`


## Referencia
[How to integrate Angular 4 with SpringBoot RestApi using SpringToolSuite](http://javasampleapproach.com/java-integration/integrate-angular-4-springboot-web-app-springtoolsuite)


