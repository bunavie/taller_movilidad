# taller_movilidad

Aplicación práctica en Flutter para geolocalización de parques cercanos, detección de movimiento con sensores/vibración y programación de notificaciones diarias[cite: 1, 2, 4, 5, 6].

## Estructura del proyecto

- `lib/main.dart`: punto de entrada, inicialización de notificaciones, permisos y navegación inferior[cite: 11, 21].
- `lib/theme/app_theme.dart`: tema visual con color `0xFF2E7D32` y tipografía `Roboto`[cite: 3, 26].
- `lib/services/park_service.dart`: consulta de parques públicos cercanos mediante Overpass API[cite: 1, 4, 24].
- `lib/services/notification_service.dart`: programación de resumen diario con zona horaria y vibración[cite: 5, 16, 25].
- `lib/widgets/step_counter_widget.dart`: detección de caminata con giroscopio, vibración y cálculo de distancia[cite: 6, 7, 19, 20].
- `lib/screens/map_screen.dart`: mapa interactivo con marcadores de parques[cite: 8, 9, 14, 23].
- `lib/screens/tracker_screen.dart`: monitor de caminata y selector de hora para notificaciones[cite: 10, 15, 22].

## Ejecución y compilación

1. Instala dependencias: `flutter pub get`[cite: 1].
2. Configura tu API Key de Google Maps en `android/app/src/main/AndroidManifest.xml`[cite: 2].
3. Ejecuta en dispositivo o emulador: `flutter run` (o compila con `flutter build apk`)[cite: 12].
