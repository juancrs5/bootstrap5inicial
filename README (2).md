## Pasos iniciais
**npm init -y** para iniciar o package.json automáticamente sen ter que introducir valores.
**npm i --save-dev parcel**
**npm i --save bootstrap @popperjs/core** para importar bootstrap.

## Atallos de teclado para a terminal
**mkdir {src,src/js,src/scss}**
**touch src/index.html src/js/main.js src/scss/styles.scss**

En 'package.json' creamos  **"start": "parcel serve src/index.html --public-url / --dist-dir dist",** para logo dar a orde na terminal **npm run start** e o servidor empece a executarse.

## Importar Bootstrap
Importar Bootstrap a Parcel require dúas importacións, unha no styles.css e outra no main.js.
**@import "~bootstrap/scss/bootstrap"** dentro do 'styles.scss'
**import * as bootstrap from 'bootstrap';** dentro do 'main.js'

## Enlaces de interese 
https://www.bootstrapdash.com/blog/building-a-simple-web-page-with-bootstrap-5
https://getbootstrap.com/