# heyamigo-web

Landing page de **Hey Amigo**, la plataforma para migrantes. Web de presentación
en https://heyamigo.eu con botones que llevan a la app en https://heyamigo.io

Trilingüe (español, inglés, francés), un solo archivo `index.html`, sin frameworks.

## Uso

Abre `index.html` en el navegador (doble clic). El idioma se detecta solo y se
puede cambiar con el selector de arriba a la derecha.

## Estructura

- `index.html` — toda la web (HTML + CSS + JS en un archivo).
- Las traducciones están en el objeto `I18N` dentro del `<script>` final.

## Despliegue

Se publica en el VPS de Infomaniak subiendo `index.html` a la carpeta web del
dominio heyamigo.eu. (Pasos concretos se añadirán al configurar el VPS.)
