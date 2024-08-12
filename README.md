# TrunkBasedDevelopment-

La rama main es la rama principal de este proyecto y siempre debe estar en un estado de producción estable. Ningún cambio debe ser empujado directamente a main; todos los cambios deben ser integrados mediante pull requests después de ser revisados y aprobados.

## Reglas para main

- *Estado Estable*: main debe estar siempre en un estado que pueda desplegarse en producción.
- *Integraciones*: Todas las integraciones a main deben pasar por un proceso de revisión de código.
- *Pruebas*: Todos los cambios deben pasar pruebas automatizadas antes de fusionarse.
- *Etiquetado*: Cada vez que se libera una nueva versión, se debe crear una etiqueta (tag) en main.

## Flujos de Trabajo

1. *Fusión de Ramas*:
   - Las ramas feature/ y hotfix/ se fusionan en main mediante pull requests.
   - Se debe realizar una revisión de código y pasar todas las pruebas automatizadas antes de la fusión.

2. *Lanzamientos*:
   - Después de fusionar una rama release/ en main, se debe etiquetar la versión correspondiente.
   - Las ramas release/ deben eliminarse después de la fusión y el etiquetado.

## Buenas Prácticas

- *Revisión de Código*: Todas las integraciones deben pasar por un proceso de revisión rigurosa.
- *Pruebas Automatizadas*: Utiliza integración continua para asegurar la calidad del código antes de fusionar.
