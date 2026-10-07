# Medidor de anillo (APK)

App en Vue 3.4.21 empaquetada con Capacitor 6. Vue va incluido en www/, así que funciona sin internet.

## Obtener el APK sin instalar nada (GitHub Actions)
1. Crea un repositorio en GitHub y sube todo el contenido de esta carpeta (incluida .github).
2. Entra a la pestaña Actions y espera a que termine "Build APK" (unos 5 minutos).
3. Abre la ejecución, baja a Artifacts y descarga medidor-anillo-apk.
4. Descomprime, pasa app-debug.apk al celular y ábrelo (permite instalar apps de origen desconocido).

## Obtenerlo en tu computador (Android Studio)
1. Instala Node 20, JDK 17 y Android Studio.
2. En esta carpeta: npm install, npx cap add android, npx cap sync android.
3. npx cap open android, y en Android Studio: Build > Build APK(s).
