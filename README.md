# AngularChangeLog

Este proyecto es una prueba de demostración de generación de ChangeLog automática.

## Standard-Version

### Definición 

Esta librería me permite a traves de un comando, generarel fichero ChangeLog.

### Instalación

Hay que instalarlo con el siguiente comando:

        npm i--save-dev standard-version

Posteriormente en el fichero **package.json** se crea un nuevo npm run en la sección scripts:

        "scripts": {
            "ng": "ng",
            "start": "ng serve",
            "build": "ng build",
            "watch": "ng build --watch --configuration development",
            "test": "ng test",
            "release": "standard-version --first-release"
        }

### Ejecución

Se ejecuta el siguiente comando para generar el ChangeLog;

        npm run release

## Referencias

[NPM - Standar-Version](https://www.npmjs.com/package/standard-version)
[GitHub - Standar-Version](https://github.com/conventional-changelog/standard-version)
[Conventional Commits](https://www.conventionalcommits.org/en/v1.0.0/)