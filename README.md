# Lab: Agregando alt a un img

## Objetivos
- Agregar el atributo alt al elemento `img`

## Introducción 
Hemos aprendido que el atributo `alt`, que significa texto `alt`ernativo, aporta significado a las imágenes de nuestros sitios.
El atributo `alt` se puede agregar a la etiqueta de la imagen al igual que el atributo `src`.


## Funcionalidad del Código
En este lab añadiremos un alt a las imagenes que previamente se añadieron al documento html

## Instrucciones
Bifurca (fork) y clona (clone) este lab en tu entorno local. Navega a su directorio en la terminal, luego ejecuta el comando `code .` para abrir sus archivos en Visual Studio Code. 

1. Agrega un atributo `alt` a las imágenes de tu archivo html, asegúrate de incluir un nombre descriptivo de la imagen.

```
<div class="html-img" >
    <img src="html-img.png" alt="codigo html IMG">
</div> 
```

2. Agrega un id “flappy-bird” al elemento `<img>` de la imagen de flappy bird. Asegurate de haber agregado un atributo alt con un nombre descriptivo de la imágen.

```
<div class="flappy-js">
   <img id="flappy-bird" src="flappy-bird.png" alt="Flappy bird IMG">
</div>

```

3. Guarda tus cambios (Archivo > Guardar)

4. Abre tu archivo html en el navegador y verifica que puedas ver el contenido de tu archivo.  Agregar un atributo `alt` aparentemente no cambia lo que se ve en el navegador. Sin embargo, si quieres ver el texto que agregaste en `alt` en acción en el navegador, simplemente cambia el valor del `src` de la imagen. Esto hará que el navegador no pueda encontrar la imagen deseada y te mostrará el texto que escribiste dentro del atributo `alt` en vez de la imagen.

5. Sube tus cambios a Github y envía por Canvas el enlace a tu repositorio.