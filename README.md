# electiva2

Repositorio público para las prácticas de la asignatura Electiva II.

## Práctica 1: repositorio y ramas

La estructura de trabajo está compuesta por:

- `main`: rama principal y estable.
- `dev`: rama de desarrollo e integración de cambios.

Los cambios deben prepararse en `dev` y pasar a `main` mediante pull requests cuando estén listos.

## Práctica 2: planificación Kanban

El trabajo del proyecto se administra mediante GitHub Issues y el tablero:

- [Planificación Kanban – electiva2](https://github.com/users/Brlamafia/projects/1)
- [Incidencias del repositorio](https://github.com/Brlamafia/electiva2/issues)

## Práctica 3: automatización web con GitHub Pages

La página “Hola Mundo” se despliega automáticamente mediante GitHub Actions cada vez que se integran cambios en `main`.

- Repositorio: https://github.com/Brlamafia/electiva2
- Página publicada: https://brlamafia.github.io/electiva2/
- Workflow: [Deploy GitHub Pages](https://github.com/Brlamafia/electiva2/actions/workflows/deploy-pages.yml)

## Práctica 4: integración continua y alertas

El programa [`hello.js`](hello.js) imprime “¡Hola, mundo desde JavaScript!”. El workflow [`alerta.yml`](.github/workflows/alerta.yml) se ejecuta en cada push a `main` y envía el resultado a:

- Canal ntfy: https://ntfy.sh/devops-itla
- Ejecuciones: https://github.com/Brlamafia/electiva2/actions/workflows/alerta.yml

## Desarrollo local

- Página web: abre `index.html` directamente en el navegador.
- Programa JavaScript: ejecuta `node hello.js`.
