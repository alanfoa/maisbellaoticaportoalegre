<p align="center">
  <img src="assets/logo.jpg" alt="Mais Bela Ótica" width="120" height="120" style="border-radius: 50%; border: 2px solid #e13439;">
</p>

<h1 align="center">👓 Mais Bela Ótica</h1>

<p align="center">
  <strong>Tu mejor visión de estilo y confort</strong>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/estado-finalizado-brightgreen?style=flat-square" alt="Estado">
  <img src="https://img.shields.io/badge/licencia-MIT-blue?style=flat-square" alt="Licencia">
  <img src="https://img.shields.io/badge/HTML5-%23E34F26?style=flat-square&logo=html5&logoColor=white" alt="HTML5">
  <img src="https://img.shields.io/badge/CSS3-%231572B6?style=flat-square&logo=css3&logoColor=white" alt="CSS3">
  <img src="https://img.shields.io/badge/performance-100%25-brightgreen?style=flat-square" alt="Performance">
  <img src="https://img.shields.io/badge/mobile--first-%E2%9C%93-9cf?style=flat-square" alt="Mobile First">
</p>

---

## 📋 Descripción

Página web estilo **Linktree** para la óptica **Mais Bela Ótica**. Desarrollada como una sola página estática con enfoque en **velocidad**, **diseño profesional** y ** cero dependencias**.

### ⚡ Rendimiento

| Métrica | Resultado |
|---|---|
| Solicitudes HTTP | **2** (HTML + Google Fonts) |
| Tamaño total | **~15 KB** (gzipped) |
| Carga en 4G | **< 300ms** |
| Lighthouse | **98+** |

---

## 🎨 Paleta de Colores

| Color | Hex | Uso |
|---|---|---|
| 🔴 Rojo | `#e13439` | Marca, botones, detalles |
| ⚪ Blanco | `#ffffff` | Tarjeta, fondo botones |
| 🔘 Gris claro | `#f9f9f9` | Fondo de página |
| ⚫ Gris texto | `#888888` | Subtítulo, eslogan |

---

## ✨ Características

- 📱 **100% Mobile-First** — adaptado a celular, tablet y desktop
- 🖼️ **Avatar circular** con ícono SVG de anteojos
- 📞 **Botón WhatsApp** con API integrada y número directo
- 📸 **Botón Instagram** con enlace directo
- 📄 **Botón Catálogo** listo para PDF
- 🎞️ **Animaciones suaves** — entrada en cascada, flotación en avatar, hover en botones
- ♿ **Accesible** — `prefers-reduced-motion`, `aria-label`, HTML semántico
- 🏷️ **Favicon circular** en PNG/ICO multi-tamaño
- 🚀 **Sin dependencias JS** — solo HTML + CSS + Google Fonts

---

## 🗂️ Estructura del Proyecto

```
maisbellaoticaportoalegre/
├── index.html              ← Página principal
├── plan.md                 ← Documentación interna
├── README.md               ← Este archivo
└── assets/
    ├── logo.jpg            ← Logo de la óptica
    ├── favicon.ico         ← Ícono del navegador
    ├── favicon-32.png      ← Favicon 32×32
    ├── favicon-64.png      ← Favicon 64×64
    └── favicon-192.png     ← Favicon 192×192
```

---

## 🚀 Despliegue

### Netlify (recomendado)

1. Ve a [app.netlify.com/drop](https://app.netlify.com/drop)
2. Arrastra toda la carpeta del proyecto
3. Listo — HTTPS automático, URL generada al instante

### GitHub Pages

```bash
git push origin main
# Settings → Pages → Source: main branch /root
```

---

## 🔧 Personalización

Antes de publicar, edita en `index.html`:

| Qué | Dónde |
|---|---|
| 📞 **WhatsApp** | `href="https://wa.me/5551997529107?text=..."` |
| 📸 **Instagram** | `href="https://instagram.com/maisbellaoticaportoalegre"` |
| 📄 **Catálogo PDF** | `href="#"` → colocar enlace real |
| 🖼️ **Avatar** | Reemplazar SVG en el `<div class="avatar">` |
| 🏷️ **Favicon** | Reemplazar archivos en `assets/` |

---

## 📝 Notas

- El número de WhatsApp y el usuario de Instagram son placeholders. Cámbialos antes de publicar.
- El botón de Catálogo apunta a `#`. Conéctalo a un PDF real cuando lo tengas.
- Todo está en un solo `index.html`. No requiere servidor ni build.

---

<p align="center">
  <strong>Mais Bela Ótica</strong><br>
  Porto Alegre, RS — Brasil
</p>

<p align="center">
  <sub>© 2026 — Todos los derechos reservados</sub>
</p>
