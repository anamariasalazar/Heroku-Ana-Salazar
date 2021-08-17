### Taller de Introducción a Heroku

Un párrafo de la descripción del proyecto va aquí

## Empezando

Estas instrucciones le proporcionarán una copia del proyecto en funcionamiento en su máquina local con fines de desarrollo y prueba. Consulte la implementación para obtener notas sobre cómo implementar el proyecto en un sistema en vivo.

### Requisitos previos

* Tener maven instalado
* Tener git instalado
* Versión de Java 7 o Java 8

### Instalación

1. Para hacer uso de este proyecto debe clonarlo de este repositorio a su computadora desde cmd usando el siguiente comando:
   
   ```
   git clone https://github.com/anamariasalazar/Heroku-Ana-Salazar
   ```

2. Antes de ejecutarlo debe compilar el proyecto, para esto haga uso del siguiente comando:

    ```
    mvn package
    ```
3.  * Si se encuentra desde linux en el archivo procfile y reemplace el contenido por el siguiente texto:
    
    ```
    web: java $JAVA_OPTS -cp 'target/classes:target/dependency/*' edu.escuelaing.arem.App
    
    ```
    * Si se encuentra desde windows en el archivo procfile y reemplace el contenido por el siguiente texto:
    
    ```
    web: java -cp target/classes;target/dependency/* edu.escuelaing.arem.App
    ```


## Ejecutando las pruebas

Explicar cómo ejecutar las pruebas automatizadas para este sistema.

### Desglosar en pruebas de extremo a extremo

Explique qué prueban estas pruebas y por qué

''
Dar un ejemplo
''

### Y pruebas de estilo de codificación

Explique qué prueban estas pruebas y por qué

''
Dar un ejemplo
''

## Implementación

Agregue notas adicionales sobre cómo implementar esto en un sistema en vivo

## Construido con

* [Dropwizard] (http://www.dropwizard.io/1.0.2/docs/): el marco web utilizado
* [Maven] (https://maven.apache.org/) - Gestión de dependencias
* [ROME] (https://rometools.github.io/rome/): se utiliza para generar fuentes RSS

## Contribuyendo

Lea [CONTRIBUTING.md] (https://gist.github.com/PurpleBooth/b24679402957c63ec426) para obtener detalles sobre nuestro código de conducta y el proceso para enviarnos solicitudes de extracción.

## Control de versiones

Usamos [SemVer] (http://semver.org/) para el control de versiones. Para conocer las versiones disponibles, consulte las [etiquetas de este repositorio] (https://github.com/your/project/tags).

## Autores

* ** Billie Thompson ** - * Trabajo inicial * - [PurpleBooth] (https://github.com/PurpleBooth)

Consulte también la lista de [contribuyentes] (https://github.com/your/project/contributors) que participaron en este proyecto.

## Licencia

Este proyecto tiene la licencia MIT. Consulte el archivo [LICENSE.md] (LICENSE.md) para obtener más detalles.

## Agradecimientos

* Sugerencia de sombrero para cualquier persona cuyo código se haya utilizado
* Inspiración
* etc
  

