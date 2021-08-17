### Taller de Introducción a Heroku

Un párrafo de la descripción del proyecto va aquí

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

## Implementación

Agregue notas adicionales sobre cómo implementar esto en un sistema en vivo

## Construido con

* [Java]: Tecnología que se usa para el desarrollo de aplicaciones que convierten a la Web en un elemento más interesante y útil.
* [IntelliJ]: Es un entorno de desarrollo integrado (IDE) para el desarrollo de programas informáticos.
* [Git]: Herramienta que realiza una función del control de versiones de código de forma distribuida
* [Maven](https://maven.apache.org/) - Dependency Management
* [![Heroku] (https://www.herokucdn.com/deploy/button.svg)](https://dashboard.heroku.com/apps/desolate-bayou-20514)

## Autor

*Ana Maria Salazar Bohorquez -  Trabajo inicial - (https://github.com/anamariasalazar/Heroku-Ana-Salazar)

## Licencia

**©️** Ana Maria Salazar Bohorquez etudiante de Ingeniería de Sistemas de la Escuela Colombiana de Ingeniería Julio Garavito

Licencia bajo la [GNU General Public License](/LICENSE.txt)



