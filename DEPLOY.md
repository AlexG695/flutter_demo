# Proceso de despliegue de la aplicación multiplataforma

## Entornos validados

- Web: desplegado en Netlify (`https://tu-site.netlify.app`).
- Android: ejecutado con `flutter run -d <dispositivo>`.

## Pasos para despliegue web (Netlify)

1. Generar build web local:
   - `flutter build web`
2. Conectar el repositorio de GitHub a Netlify.
3. Configurar:
   - Build command: `flutter build web --release`
   - Publish directory: `build/web`
4. Guardar y desplegar. Netlify genera la URL pública.

## Pasos para validar Android

1. Conectar dispositivo o emulador.
2. Ejecutar `flutter run -d <dispositivo>`.
3. Verificar que la interfaz funciona igual que en web (navegación, lista, formulario).
