# Control Cabify — compilación de APK

Este proyecto está preparado para compilarse con Android Gradle Plugin 8.7.3, Gradle 8.9, Java 17 y Android SDK 35.

El workflow `.github/workflows/build-apk.yml` compila automáticamente una APK debug y la publica como artefacto llamado `Control-Cabify-APK`.

La aplicación funciona sin conexión y guarda los datos localmente mediante `SharedPreferences`.
