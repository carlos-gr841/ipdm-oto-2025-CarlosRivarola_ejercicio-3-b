# ipdm-oto-2025-CarlosRivarola_ejercicio-3-b

---

### 📁 `ipdm-oto-2025-CarlosRivarola_ejercicio-3-b`

```markdown
# Ejercicio 3-b - Cuadrante de Compose

Esta app muestra una pantalla dividida en cuatro cuadrantes iguales, cada uno con una descripción sobre funciones composables de Jetpack Compose.

## 💡 Descripción

Cada cuadrante está diseñado con un fondo de color distinto, un título en negrita y un párrafo explicativo. El contenido está alineado vertical y horizontalmente al centro.

## 🖼️ Captura de pantalla

> ![Captura de pantalla](screenshots/c0c70117bbd3b5b5.png)

_(Ubicá esta imagen en la carpeta `screenshots` del repositorio)_

## ⚙️ Tecnologías usadas

- Kotlin
- Jetpack Compose
- Android Studio

## 📁 Estructura

- La pantalla se divide en dos `Row`, cada una conteniendo dos `Column` con `Modifier.weight()`.
- Cada cuadrante contiene:
  - Un título en negrita con padding inferior.
  - Un texto descriptivo.
  - Fondo de color único.

## 📦 Recursos usados

### 🎨 Colores

- `#EADDFF`
- `#D0BCFF`
- `#B69DF8`
- `#F6EDFF`

### 📄 Strings

- **Text composable**: Displays text and follows the recommended Material Design guidelines.
- **Image composable**: Creates a composable that lays out and draws a given Painter class object.
- **Row composable**: A layout composable that places its children in a horizontal sequence.
- **Column composable**: A layout composable that places its children in a vertical sequence.

## 📱 Requisitos

- Android Studio Giraffe o superior
- Emulador configurado (API 26 en adelante)
