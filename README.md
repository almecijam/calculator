# calculator
Java + Gradle repository to learn Jenkins

### Se crean los ficheros:

- Jenkinsfile para el apartado 1.

- Jenkinsfile2 para el apartado 2.


## Apartado 1

En el 'Panel de Control' se selecciona la opción `Nueva Tarea`

A esta nueva tarea le añadimos un nombre, por ejemplo 'Apartado1' y a continuación seleccionamos `Pipeline` y pulsamos `ok`

En la configuración 'General' de 'Apartado1':

Seleccionamos:
- Definition: Pipeline script from SCM
- SCM: Git
- Repository URL: https://github.com/almecijam/calculator.git
- Branches to build > Branch Specifier (blank for 'any'): */main
- Script Path: Jenkinsfile

Pulsamos `Guardar`

Por último en el menú de 'Apartado1' pulsamos `Construir ahora`

## Apartado 2

Instalamos los plugins `Docker` y `Docker Pipeline` en el Panel de Control navegando a través del mismo del siguiente modo:
`Administrar Jenkins` > `Administrar Plugins` > `Available plugins`

Una vez instalados los plugins, en el 'Panel de Control' se selecciona la opción `Nueva Tarea`

A esta nueva tarea le añadimos un nombre, por ejemplo 'Apartado2' y a continuación seleccionamos `Pipeline` y pulsamos `ok`

En la configuración 'General' de 'Apartado2':

Seleccionamos:
- Definition: Pipeline script from SCM
- SCM: Git
- Repository URL: https://github.com/almecijam/calculator.git
- Branches to build > Branch Specifier (blank for 'any'): */main
- Script Path: Jenkinsfile2

Pulsamos `Guardar`

Por último en el menú de 'Apartado2' pulsamos `Construir ahora`