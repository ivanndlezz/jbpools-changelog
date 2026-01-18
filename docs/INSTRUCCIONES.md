# Instrucciones para el Changelog Manager

## Descripción

Este documento describe cómo utilizar el Changelog Manager para documentar y gestionar los cambios en el proyecto.

## Flujo de Trabajo

### 1. Documentar Cambios

1. **Crear un archivo de instrucciones**: Este archivo (`INSTRUCCIONES.md`) contiene las pautas para documentar los cambios.
2. **Crear una plantilla**: Utiliza la plantilla `PLANTILLA_CHANGELOG.md` para registrar los cambios en un formato estructurado.
3. **Registrar cambios**: Completa la plantilla con los cambios realizados en el proyecto.

### 2. Procesar Cambios

1. **Analizar documentos**: La IA analizará los documentos generados y reorganizará la información en el formato adecuado para el changelog.
2. **Generar changelog**: La IA generará un archivo `CHANGELOG.md` con los cambios estructurados y listos para ser publicados.

## Ejemplo de Uso

1. **Documentar cambios**: Completa la plantilla `PLANTILLA_CHANGELOG.md` con los cambios realizados.
2. **Procesar cambios**: La IA analizará la plantilla y generará el changelog final.

## Instrucciones para GitHub

Para documentar los cambios en GitHub, sigue estos pasos:

1. **Realiza un commit por cada cambio**: Utiliza mensajes de commit descriptivos y sigue el formato convencional:
   - `feat`: Para nuevas funcionalidades.
   - `fix`: Para correcciones de errores.
   - `docs`: Para cambios en la documentación.
   - `style`: Para cambios de estilo o formato.
   - `refactor`: Para refactorizaciones de código.
   - `perf`: Para mejoras de rendimiento.
   - `test`: Para cambios en pruebas.
   - `chore`: Para tareas de mantenimiento.

2. **Ejemplos de commits**:
   ```bash
   git commit -m "feat: nueva funcionalidad de login"
   git commit -m "fix: corregido error en formulario"
   git commit -m "docs: actualizada documentación"
   ```

## Notas Adicionales

- Asegúrate de seguir el formato indicado en la plantilla para facilitar el procesamiento.
- Los cambios deben ser descriptivos y claros para que la IA pueda interpretarlos correctamente.

## Contacto

Si tienes dudas o necesitas ayuda, no dudes en contactar al equipo de desarrollo.
