# Henry

## Prep Checkpoint

### Fork

Primero debes **forkear** este repo, haciendo click en el botón `fork` de arriba a la derecha.

Ahora ya tenés una copia de este repo en tu cuenta de `github`.
Cloná el repo dentro de una carpeta que vos elijas en tu compu. Una vez clonado entrá a esa carpeta y ejecutá los siguentes comandos:

```bash
npm install
npm test
```
Si ves los tests fallando, estás listo para comenzar.

## Consignas

### JavaScript

En la parte práctica, te vamos a brindar los tests preparados, tu tarea es completar el código en `checkpoint.js` de tal forma que pasen la mayoría de los tests. Para ejecutar los tests, primero debes tirar el comando `npm test` dentro esta carpeta.

>Antes de npm test, deberías haber instalado las dependencias con `npm install`

## Subir tu checkpoint

Debes subir un commit a tu repo. Para hacerlo, debes ejecutar el siguente comando (parados desde esta carpeta) y seguir los pasos:

```bash
npm run submit
```

En el caso de que no funcione lo anterior:

```bash
git add .
git commit -m 'checkpoint commit'
git push origin main
```

Chequéa que veas los cambios reflejados en el repo de tu cuenta de github! (entrando a tu repo desde el browser.)

**Notas**:

* Hay cosas puntuales que tal vez no vimos específicamente en los lectures, vas a tener que investigar un poquito por tu cuenta.
* Podés buscar en internet o en cualquier otro lugar por recursos para que te ayudes.
* No podés ayudar ni preguntar a tus compañeros de clases.
* Intentá pasar la mayor cantidad de tests posibles, inclusive el extra credit!
* La cantidad de tests pasados no determina tu admisión, pero sí influye mucho.

# LEER ATENTAMENTE ANTES DE REALIZAR UNA CONSULTA POR SLACK:
#### Cualquier consulta o error que tengan, antes de publicar nada en Slack, leer la siguiente "guía". Si tu duda no aparece en este documento, revisa el canal de Slack "henry_challenge", quizás alguien más tuvo el mismo problema y ya lo pudo solucionar. En el caso de que no se cumpla lo anterior, realizar una publicación en dicho canal.

## ERRORES DE CONSOLA
#### Para identificar el error, vas a tener que leerlo en la consola!

  - __Problema al querer pushear las soluciones:__ 
    - Vas a tu repositorio en GitHub, apretas el botón `Add files`, luego en la opción `Upload files`
    - Arrastra el archivo _checkpoint.js_ de su HC al dropbox ( El que dice "Drag files here to add them to your repository" ).
    - En el primer _input_ debajo del dropbox ponen el título del commit ( El que ustedes gusten ).
    - Click en el botón verde `Commit changes`.
    - A esperar los resultados!
  - __"jest" no se reconoce como un comando externo o interno...:__
    - Instalar jest con el comando `npm install jest`.
    - Si esto no funciona, borrar la carpeta `node_modules` y el archivo `package-lock.json` e instalar nuevamente ( `npm install` ).
  - __1 failed, 1 total__:
    - Tenes un error de sintaxis. Revisa el último ejercicio que hayas hecho, seguramente falta o sobra una llave, paréntesis, punto y coma, etc.
  - __Author identity unknown. ***Please tell me who you are:__
    - Ejecutar los siguientes comandos:
      - git config --global user.name "Tu usuario de GitHub aca"
      - git config --global user.email "Tu email aca"
  - __La consola se tilda en `Runs`:__
    - Revisa tu código, tenes un bucle infinito. Tenes que checkear la condición de corte de tus bucles.

## CONSULTAS RESPECTO AL HC:
  - __¿Se puede volver a rendir el HC?:__
    - Si, el HC se puede rendir tantas veces como ustedes quieran! No hay límite de intentos.
  - __Error 404 al clickear en el link del repositorio:__
    - Loguearse en GitHub y luego clickear nuevamente en el link.
  - __Como saber si se pushearon bien sus cambios:__
    - Van al repositorio forkeado en GitHub, si ven su último commit, esta todo bien. 
  - __El repositorio aparece como privado:__
    - No se hagan problema, es privado por ser propiedad de Henry. Podemos acceder igualmente a corregirlo.
  - __¿Cuánto tiempo tengo para hacer el HC?:__
    - El que ustedes quieran, pueden estar las 28hs codeando si así lo desean. Tienen que entregar antes de las 13hs del día Sábado ( Del país que sea, a menos que se indique lo contrario ).
  - __¿Qué hago una vez entregado el HC?:__
    - A esperar! Muchos éxitos, los van a estar contactando en un plazo no mayor a una semana para confirmarles, tanto si quedaron, como si no lo hicieron!
  - __Tengo una duda con algún ejercicio:__
    - Comunicarse con el encargado del HC. Es quien mando el mensaje dando aviso de la entrega de los invite en la mañana del día Viernes.
