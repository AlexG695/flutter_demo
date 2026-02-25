## Despliegue validado 

### Plataforma Web (Vercel)
- URL: https://flutter-demo-gamma.vercel.app/
- Proceso: 
  1. `flutter build web --release`
  2. Conectar repo GitHub a Vercel
  3. Configurar Output Directory: `build/web`
  4. Deploy automático

### Plataforma Android
- Proceso:
  1. `flutter devices` (ver dispositivos)
  2. `flutter run -d <device_id>`
- Capturas: `/screenshots/device.png`, `/screenshots/image.png`

### Consistencia
La interfaz mantiene el mismo diseño y funcionalidad (tabs, lista, formulario) en ambos entornos.
