# Markdown Links

## Índice

* [1. Preámbulo](#1-preámbulo)
* [2. Resumen del proyecto](#2-resumen-del-proyecto)
* [3. Diagrama de Flujo](#3-Diagrama-de-Flujo)
* [4. Guîa de Instalaciòn](#4-Guìa-de-Instalaciòn)
* [5. Manual de Usuario](#5-Manual-de-Usuario)
* [6. Links de Referencias](#6-Links-de-Referencias)
***

## 1. Preámbulo

[Markdown](https://es.wikipedia.org/wiki/Markdown) es un lenguaje de marcado que facilita la aplicación de formato a un texto empleando una serie de caracteres de una forma especial. En principio, fue pensado para elaborar textos cuyo destino iba a ser la web con más rapidez y sencillez que si estuviésemos empleando directamente HTML. Y si bien ese suele ser el mejor uso que podemos darle, también podemos emplearlo para cualquier tipo de texto, independientemente de cual vaya a ser su destino.

## 2. Resumen del proyecto

Este proyecto se Centra en la creaciòn de una herramienta de línea de comando (CLI) así como supropia librería (o biblioteca - library) en JavaScript.

En esta oportunidad bajo el nombre de md-Links se crea una librería que facilita la lecturay análisis de los archivos con formato Markdown, nos alejamos un poco del navegador para construir un programa que se ejecute usando Node.js. como su nombre lo indica su ejecuciòn es a travès de lineas de comandos que nos premiten verificar los enlaces (Links) que se encuentran dentro de directorios y archivos con extension .md, generando estadisticas sobre el total de los mismo, si estos son vâlidos, ùnicos y Rotos.

## 3. Diagrama de Flujo

Para el desarollo de este proyecto se diseño un [Diagrama de flujo](https://github.com/HicoTico/DEV005-md-links/blob/main/_Diagrama%20de%20flujo-mdlinks.png), el cual se ejecutò paso a paso mediante mètodo SCRUM.

## 4. Guîa de Instalaciòn

Ingresando el siguiente comando en la terminal de su Proyecto, podrà llevar esta Libreria a ejecuciòn
```sh
npm i blablabla
```
## 5. Manual de Usuario
Luego de instalada la libreria, a travès de la terminal (GitBash recomendado) ingresando las siguientes instrucciones, podràs acceder a los resultados de CLI:

Ingrese `mdLinks <path-to-file>`
 
```sh
$ mdLinks ./Directory/example.md 
[{
    href: 'https://amExample.com/install',
    text: 'am a example',
    pathMd: 'C:\\Users\\Dell\\Desktop\\Directory\\example.md'
  }]
```
Ingrese `mdLinks <path-to-file> --validate`
 
```sh
[{
    href: 'https://amExample.com/install',
    text: 'am a example',
    pathMd: 'C:\\Users\\Dell\\Desktop\\Directory\\example.md',
    code: 200,
    status: 'OK'
  }]
```
Ingrese `mdLinks <path-to-file> --stats`
```sh
{ total: 30, unique: 28 }
```
Ingrese `mdLinks <path-to-file> --stats --validate`
```sh
{ total: 30, unique: 28, broken: 7 }
```
## 6. Links de Referencias

* [Acerca de Node.js - Documentación oficial](https://nodejs.org/es/about/)
* [Que es markdown](https://nodejs.org/api/fs.html](https://www.genbeta.com/guia-de-inicio/que-es-markdown-para-que-sirve-y-como-usarlo)
* [Node.js http.get - Documentación oficial](https://nodejs.org/api/http.html#http_http_get_options_callback)
* [Expresiones Regulares](https://regexr.com/)
* [Aprende como aplicar Jest Mock](https://developero.io/blog/jest-mock-module-function-class-promises-axios-y-mas)
* [Publicar packpage](https://docs.npmjs.com/getting-started/publishing-npm-packages)
* [Crear módulos en Node.js](https://docs.npmjs.com/getting-started/publishing-npm-packages)
* [Leer un archivo](https://nodejs.org/api/fs.html#fs_fs_readfile_path_options_callback)
* [Leer un directorio](https://nodejs.org/api/fs.html#fs_fs_readdir_path_options_callback)
* [Path](https://nodejs.org/api/path.html)
* [Linea de comando CLI](https://medium.com/netscape/a-guide-to-create-a-nodejs-command-line-package-c2166ad0452e)


<center>*La Fuerza esta Contigo*</center>
