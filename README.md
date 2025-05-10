# MusicRename

MusicRename es un script en Bash para renombrar archivos de música de manera automática, basándose en los metadatos de los archivos MP3, específicamente en el campo "track" para generar números antes del nombre de las canciones.

## Características

* Renombra archivos de música con formato "nn_Nombre Archivo.mp3"
* Soporte para archivos MP3 y LRC
* Opción para simular el renombrado sin aplicar cambios
* Utiliza los metadatos de los archivos MP3 para determinar el número de pista y renombrar los archivos

## Uso

1. Clona el repositorio
2. Ejecuta el script con `musicrename [-s] [directorio]`
 * `-s` para simular el renombrado sin aplicar cambios
 * `directorio` para especificar el directorio de trabajo (por defecto: actual)

## Instalación

1. Copia el script a `/usr/local/bin`: `sudo cp musicrename /usr/local/bin/musicrename`
2. Dale permisos de ejecución: `sudo chmod +x /usr/local/bin/musicrename`

## Requisitos

* Bash
* FFmpeg (incluyendo `ffprobe`)

## Ejemplos de nombres de archivos resultantes

* `01_nombreCancion1.mp3`
* `01_nombreCancion1.lrc`
*  ..
* `11_nombreCancion11.mp3`
* `11_nombreCancion11.mp3`

## Changelog

* [Ver changelog](CHANGELOG.md)

## Licencia

Este proyecto está licenciado bajo la licencia GPLv3. Ver el archivo LICENSE para más detalles.


