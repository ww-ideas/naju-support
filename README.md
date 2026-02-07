# Naju Support

Documentación legal y soporte para la aplicación Naju.

## Contenido

- **terms_of_use.md** – Términos de uso (Terms of Use).
- **privacy_policy.md** – Política de privacidad (Privacy Policy).

## Uso en la app Naju

La aplicación Naju carga estos documentos desde:

- https://ww-ideas.github.io/naju-support/terms_of_use.md  
- https://ww-ideas.github.io/naju-support/privacy_policy.md  

Si GitHub Pages sirve HTML en lugar de Markdown, la app usa como respaldo las URLs raw de GitHub (`raw.githubusercontent.com/ww-ideas/naju-support/main/...`).

Al editar los `.md`, los cambios se reflejan en la app tras publicar en GitHub (y, si aplica, tras el despliegue de GitHub Pages). No es necesario actualizar la app para cambiar el texto legal.

## Rama por defecto

Las URLs raw usan la rama `main`. Si la rama por defecto del repositorio cambia, hay que actualizar las constantes en la app (p. ej. en `lib/screens/terms_screen.dart`).
