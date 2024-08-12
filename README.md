# TrunkBasedDevelopment-Hotfix 👨‍💻

Las ramas hotfix/ se utilizan para aplicar correcciones urgentes y críticas en producción. Estas ramas deben ser creadas desde main y fusionadas tan pronto como la corrección esté validada.

## Reglas de Denominación

- *Regla de Denominación*: hotfix/descripcion-corta-bug
- *Ejemplos*: 
  - hotfix/correccion-vulnerabilidad-ssl
  - hotfix/arreglo-error-login

## Flujos de Trabajo

1. *Creación de Ramas*:
   - Crea la rama desde main cuando se detecte un error crítico que necesite una corrección inmediata.

2. *Integración*:
   - Fusiona la rama en main tan pronto como se valide la corrección.
   - Considera fusionar también en otras ramas relevantes (como release/ si es aplicable).

3. *Eliminación de Ramas*:
   - Después de fusionar la rama hotfix/ en main, elimina la rama para mantener el repositorio organizado.

## Buenas Prácticas

- *Corrección Rápida*: Las ramas hotfix/ deben corregir problemas críticos de manera rápida y eficiente.
- *Validación Extensiva*: Asegúrate de que la corrección ha sido validada en un entorno de pruebas antes de fusionar.
