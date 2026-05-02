# 🐱 Las Alas del Gato — POS Domicilios

Sistema POS instalable como aplicación (PWA) para domicilios de alitas.

---

## 📁 Archivos del proyecto

```
index.html     ← App principal (móvil + escritorio)
manifest.json  ← Configuración PWA (nombre, íconos, colores)
sw.js          ← Service Worker (funciona sin internet)
icon-192.png   ← Ícono de la app (192×192 px) — DEBES AGREGARLO
icon-512.png   ← Ícono de la app (512×512 px) — DEBES AGREGARLO
README.md      ← Este archivo
```

---

## 🚀 Cómo publicar en GitHub Pages (instalable desde el celular)

### Paso 1 — Crear repositorio en GitHub
1. Ve a [github.com](https://github.com) e inicia sesión
2. Clic en **New repository** (botón verde arriba a la derecha)
3. Nombre: `gato-pos` (o el que quieras)
4. Marcalo como **Public**
5. Clic en **Create repository**

### Paso 2 — Subir los archivos
En la página del repositorio vacío:
1. Clic en **uploading an existing file**
2. Arrastra todos los archivos: `index.html`, `manifest.json`, `sw.js`, `icon-192.png`, `icon-512.png`
3. Clic en **Commit changes**

### Paso 3 — Activar GitHub Pages
1. Ve a **Settings** (pestaña del repositorio)
2. En el menú izquierdo busca **Pages**
3. En "Source" selecciona **Deploy from a branch**
4. Branch: **main**, carpeta: **/ (root)**
5. Clic en **Save**
6. Espera 1-2 minutos y aparecerá tu URL:
   ```
   https://TU_USUARIO.github.io/gato-pos/
   ```

---

## 📱 Cómo instalar la app en el celular

### Android (Chrome):
1. Abre la URL de GitHub Pages en Chrome
2. Aparece un banner **"Agregar a pantalla de inicio"** — toca **Instalar**
3. O usa el menú (⋮) → **"Instalar aplicación"**
4. La app queda en tu pantalla de inicio como cualquier otra app

### iPhone (Safari):
1. Abre la URL en Safari
2. Toca el botón **Compartir** (□↑)
3. Selecciona **"Añadir a pantalla de inicio"**
4. Toca **Agregar**

---

## 🖼️ Íconos (IMPORTANTE)

Debes agregar dos imágenes PNG con el logo del restaurante:
- `icon-192.png` → 192 × 192 píxeles
- `icon-512.png` → 512 × 512 píxeles

Puedes usar [pwa-image-generator.firebaseapp.com](https://pwa-image-generator.firebaseapp.com) para generarlos fácilmente desde tu logo.

---

## 🌐 Funciona sin internet
Una vez instalada, la app funciona **completamente offline** gracias al Service Worker. Todos los datos se guardan en el dispositivo.

---

## 🔐 Acceso al sistema
- **Usuario:** `gato`
- **Contraseña:** `alas2025`

---

*Powered by MULTIMANT SAS*
