# TrunkBasedDevelopment- Feature 😎

Las ramas feature/ se utilizan para desarrollar nuevas funcionalidades o mejoras dentro del proyecto. Estas ramas son de corta duración y deben integrarse frecuentemente en main.

## Reglas de Denominación

- *Regla de Denominación*: feature/nombre-corto-descriptivo
- *Ejemplos*: 
  - feature/agregar-autenticacion
  - feature/mejorar-UI-dashboard

## Flujos de Trabajo

1. *Creación de Ramas*:
   - Crea la rama desde main.
   - Asegúrate de que el nombre de la rama sea descriptivo y siga la convención establecida.

2. *Integración*:
   - Integra frecuentemente los cambios a main para evitar grandes divergencias.
   - Realiza pull requests para fusionar la rama en main después de completar el desarrollo.

3. *Eliminación de Ramas*:
   - Después de fusionar la rama en main, elimina la rama feature/ para mantener el repositorio limpio.

## Buenas Prácticas

- *Integraciones Frecuentes*: No acumules muchos cambios en la rama feature/. Integra pequeñas mejoras continuamente.
- *Pruebas Automatizadas*: Asegúrate de que todos los cambios en la rama feature/ pasen por pruebas antes de la integración.
