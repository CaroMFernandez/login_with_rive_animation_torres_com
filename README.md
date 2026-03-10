# 🔐 Login Screen con Animación Rive en Flutter

Este proyecto muestra una pantalla de inicio de sesión en **Flutter** integrada con una animación interactiva creada en **Rive**.  
La animación reacciona dinámicamente cuando el usuario interactúa con los campos de email y contraseña.

---

## 📌 Características

- 🎨 Animación interactiva con Rive
- 👀 El personaje mira al campo de email cuando está en foco
- 🙈 El personaje se cubre los ojos al escribir la contraseña
- 👁️ Botón para mostrar/ocultar contraseña
- ✅ Trigger de éxito al presionar el botón "Iniciar Sesión"
- 🧹 Manejo correcto de memoria con `dispose()`

---

## 📦 Dependencias

Agrega las siguientes dependencias en tu archivo `pubspec.yaml`:

```yaml
dependencies:
  flutter:
    sdk: flutter
  rive: ^0.12.0 # o la versión más reciente