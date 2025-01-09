# Nginx
## Indice
1. Introducción.
2. Instalación
3. Configuración

## Introducción
Nginx es una alternativa a apache. En base es muy similar pero hay ciertas diferencias que nombraremos aquí.

## Instalación
`$sudo apt install Nginx`

## Configuración
La creación de paginas funciona igual excepto por dos cosas:
- La configuracion del ficehro /etc/nginx/sites-available/default
- La creacion de los enlaces simbolicos se hace manualmente: `ln -s /RUTA_FICHERO_DE_CONFIGURACION_EN_SITES-AVAILABLE /RUTA_SITES-ENABLED`
