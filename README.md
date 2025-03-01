<h1 align="center">Jarvis</h1>

<div align="center">
  <img src="img/jarvis_logo_resized.png" alt="Logo de Jarvis" width="300">
</div>

**Jarvis** es un asistente basado en la terminal, diseñado para automatizar tareas repetitivas en los computadores de Campuslands. 🚀

---

## ✨ Funcionalidades

- 🧹 **Limpieza**: Elimina archivos de usuarios anteriores.
- 🌐 **Navegador predeterminado**: Configura automáticamente el navegador basado en la última elección del usuario.
- 🔑 **Sincronización GitHub**: Conecta GitHub mediante una llave SSH.
- 📦 **Instalación de Node.js**.
- 🎨 **Personalización**: Modifica la estética de la terminal a tu gusto.
- 🖼 **Cambio de fondo**: Ajusta el fondo de pantalla del computador.
- 🤖 **Calificación automática**: Evalúa clases de Software Skills y Ser.
- 📝 **Obsidian**: Descarga e inicia la aplicación (*ideal para apuntes en Markdown*).
- 🗑 **Limpieza total**: Borra archivos, sesiones y rastros del usuario.
- ⏳ **Apagado automático** del computador.

---

## 🚀 Instalación y Configuración

### 1️⃣ Configurar variables
Al descargar Jarvis, verás en las primeras líneas del código variables globales:

![Ejemplo de variables](img/variables_ejemplo.png)

Completa estas variables con la información requerida para personalizar Jarvis a tu gusto.

### 2️⃣ Dar permisos de ejecución
Ejecuta el siguiente comando en la terminal:
```bash
chmod +x jarvis.sh
```

---

## ⚙️ Protocolos disponibles

### 🔹 **Protocolo de bienvenida**
📌 Comando:
```bash
./jarvis.sh hello
```
✅ Funciones:
- 🧹 Limpia la carpeta de descargas.
- 🖼 Cambia el fondo de pantalla.
- 🎨 Personaliza la terminal.
- 🧑‍💻 Limpia VS Code (elimina extensiones y configuraciones previas).
- 🌐 Configura Google Chrome como navegador predeterminado.
- 🔑 Modifica `~/.gitconfig` con tus datos.
- 🔗 Vincula GitHub mediante SSH.
- 📦 Instala Node.js.

---

### 📝 **Protocolo Obsidian**
📌 Comando:
```bash
./jarvis.sh obsidian
```
✅ Funciones:
- 📥 Descarga la aplicación Obsidian.
- 🚀 Abre Obsidian automáticamente.

---

### 😃 **Jarvis Happy Mode**
📌 Comando:
```bash
./jarvis.sh happy
```
✅ Funciones:
- 😃 Califica automáticamente las clases de Software Skills y Ser con caritas felices.

---

### 🔻 **Protocolo de despedida**
📌 Comando:
```bash
./jarvis.sh bye
```
✅ Funciones:
- ❌ Elimina la llave SSH vinculada en el protocolo de bienvenida.
- 🚪 Cierra sesión en VS Code.
- 🔍 Borra datos de sesión en navegadores Firefox y Chrome.
- 🗑 Elimina todos los archivos en la carpeta Descargas.
- 🧑‍💻 Borra la información de `~/.gitconfig`.
- 📜 Elimina el historial de comandos de la terminal.
- ⏳ Programa el apagado del computador en 10 segundos.
- 💣 **Jarvis se autodestruye.**

---

¡Disfruta la automatización con Jarvis! 😎🔥