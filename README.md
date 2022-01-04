# **404 Page Not Found**

Página 404 personalizada. El texto se mueve conforme a los movimientos del ratón.

La idea fue sacada de [Mr. Web Designer](https://www.youtube.com/watch?v=zI1EjEywGG4&t=301s), adaptando el proyecto a SCSS.

## Resultado final del proyecto

![](resources/404-page-not-found.gif)

### Enlace a la página

https://esdjl-404-page-not-found.netlify.app/

### Tecnologías utilizadas

- HTML5
- SCSS
- JavaScript

## Cómo realizar modificaciones

### Requisitos

Antes de hacer modificaciones al proyecto, ten en cuenta que debes tener instalado _sass_ en tu equipo, de no tenerlo, sigue los siguientes pasos:

1. Asegurate que tienes instalado [Nodejs](https://nodejs.org/es/download/). Escribe el siguiente comando en la terminal, si arroja un error, significa que no está instalado, procede a instalarlo:

```
node -v
```

2. A continuación instala _sass_ de forma global en tu equipo:

```
npm install -g sass
```

### Modificar el proyecto

1. Clonar el repositorio:

```
git clone https://github.com/ESaulDJLaguna/estudio-404PageNotFoundHoverTrees.git
```

2. Accede a la carpeta que se creo al clonar el repositorio:

```
cd estudio-404PageNotFoundHoverTrees/
```

1. Transpila el código _SCSS_, y mantente en modo observador para capturar todos los cambios que se hagan:

```
sass -w SCSS/styles.scss CSS/styles.css
```

4. Abre _index.html_ en tu navegador.
