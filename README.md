# 🚍 UNIGO – Aplicación de Movilidad para Acceder al Campus de Álava

**UNIGO** es una aplicación Android diseñada para facilitar el acceso al campus universitario de Álava desde cualquier punto de Vitoria-Gasteiz. Integra distintos medios de transporte público y sostenible para mejorar la movilidad del estudiantado y otros usuarios.

---

## 🎯 Objetivo

Desarrollar una app intuitiva y funcional que permita a los usuarios:

- Planificar rutas al campus desde su ubicación actual
- Elegir entre distintos medios de transporte disponibles:
  - 🚶 Caminata a pie
  - 🚲 Bicicleta (usando datos de carriles bici - bidegorris)
  - 🚌 Autobús urbano (datos abiertos de Tuvisa

La aplicación también contempla funcionalidades extra como:

- Registro e inicio de sesión
- Gestión de perfil de usuario
- Alarmas para salidas de transporte
- Widgets para cuenta atrás hasta la llegada del autobús

---

## 📱 Tecnologías Utilizadas

- **Lenguaje:** Java
- **Plataforma:** Android Studio
- **Mapas:** Google Maps SDK 
- **Datos abiertos:** 
  - API de Tuvisa (autobuses)
  - Datos GIS de bidegorris

---

## 🧪 Funcionalidades Implementadas

- Mapa interactivo con ubicación del usuario
- Cálculo de rutas peatonales
- Integración de rutas en bicicleta
- Consulta en tiempo real de líneas de autobús
- Alarma para salidas de transporte público
- Diseño centrado en experiencia del usuario



🚀 Cómo lanzar el proyecto en Android Studio
🧱 Requisitos previos

    Android Studio Giraffe | 2022.3.1 o superior

    Android SDK API 29 (Android 10) o superior

    Gradle compatible (normalmente configurado en el proyecto)

    Java JDK 8 o superior

📥 Clonar el repositorio

git clone (https://github.com/aitorGonzalo/CampusGo)


🛠 Abrir en Android Studio

    Abre Android Studio

    Selecciona "Open an existing project"

    Navega a la carpeta del proyecto (donde está build.gradle) y ábrela

    Espera a que Gradle sincronice los archivos y descargue las dependencias

▶️ Ejecutar la aplicación

    Conecta un dispositivo Android físico (o crea un emulador)

    Pulsa el botón Run (▶️) en Android Studio

    La app se compilará y ejecutará automáticamente en el dispositivo

📦 Generar APK

Para generar el .apk manualmente:

    Ve a Build > Build Bundle(s) / APK(s) > Build APK(s)

    Una vez completado, Android Studio mostrará el enlace para abrir la carpeta donde se guarda el .apk
