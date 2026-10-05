# Gestor Supermercado — Android

Aplicación Android que envuelve la PWA de Gestor Supermercado en una WebView.

## URL de la aplicación

https://ansu-nex.github.io/Gestor-NEX/

## Requisitos

- Android Studio reciente
- JDK 17
- Android SDK 36

## Compilar

Desde la carpeta del proyecto:

```bash
gradle :app:assembleDebug
```

El APK queda en:

```text
app/build/outputs/apk/debug/app-debug.apk
```

También hay un workflow de GitHub Actions para generar el APK desde GitHub:
Actions → Build APK → Run workflow.

## Nota

La aplicación carga la versión publicada en GitHub Pages. Los datos del gestor se mantienen en el almacenamiento local de la WebView del dispositivo.