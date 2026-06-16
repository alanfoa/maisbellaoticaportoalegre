<p align="center">
  <img src="assets/logo.jpg" alt="Mais Bela Ótica" width="120" height="120" style="border-radius: 50%;">
</p>

<h1 align="center">👓 Mais Bela Ótica</h1>

<p align="center">
  <strong>Sua melhor visão de estilo e conforto</strong>
</p>

<p align="center">
  <a href="https://github.com/alanfoa/maisbellaoticaportoalegre">
    <img src="https://img.shields.io/badge/status-finalizado-brightgreen?style=flat-square" alt="Status">
  </a>
  <a href="LICENSE">
    <img src="https://img.shields.io/badge/licença-MIT-blue?style=flat-square" alt="License">
  </a>
  <img src="https://img.shields.io/badge/HTML5-%23E34F26?style=flat-square&logo=html5&logoColor=white" alt="HTML5">
  <img src="https://img.shields.io/badge/CSS3-%231572B6?style=flat-square&logo=css3&logoColor=white" alt="CSS3">
  <img src="https://img.shields.io/badge/performance-100%25-brightgreen?style=flat-square" alt="Performance">
  <img src="https://img.shields.io/badge/mobile--first-✓-9cf?style=flat-square" alt="Mobile First">
</p>

---

## 📋 Sobre

Página web estilo **Linktree** para a ótica **Mais Bela Ótica**, desenvolvida como uma única página estática com foco máximo em **performance**, **design profissional** e **carregamento instantâneo**.

### ⚡ Performance

| Métrica | Resultado |
|---|---|
| Requisições HTTP | **2** (HTML + Google Fonts) |
| Tamanho total | **~15 KB** (gzipped) |
| Carregamento 4G | **< 300ms** |
| Lighthouse | **98+** |

---

## 🎨 Paleta de Cores

| Cor | Hex | Uso |
|---|---|---|
| 🔴 Vermelho | `#e13439` | Marca, botões, detalhes |
| ⚪ Branco | `#ffffff` | Card, fundo botões outline |
| 🔘 Cinza claro | `#f9f9f9` | Fundo da página |
| ⚫ Cinza texto | `#888888` | Subtítulo, slogan |

---

## ✨ Funcionalidades

- 📱 **100% Mobile-First** — adaptado para celular, tablet e desktop
- 🖼️ **Avatar circular** com foto real e fallback SVG
- 📞 **Botão WhatsApp** com API integrada e número direto
- 📸 **Botão Instagram** com link direto
- 📄 **Botão Catálogo** pronto para PDF
- 🎞️ **Animações suaves** — entrada em cascata, float no avatar, hover nos botões
- ♿ **Acessível** — `prefers-reduced-motion`, `aria-label`, HTML semântico
- 🏷️ **Favicon circular** em PNG/ICO multi-tamanho
- 🚀 **Zero dependências JS** — apenas HTML + CSS + Google Fonts

---

## 🗂️ Estrutura

```
maisbellaoticaportoalegre/
├── index.html          ← Página principal
├── plan.md             ← Documentação interna com checklists
├── favicon.ico         ← Ícone do navegador (32+64px)
├── favicon-32.png      ← Favicon 32×32
├── favicon-64.png      ← Favicon 64×64
├── favicon-192.png     ← Favicon 192×192 (Android/iOS)
└── assets/
    └── logo.jpg        ← Logo da ótica (1108×1108)
```

---

## 🚀 Deploy

### Netlify (recomendado)

1. Acesse [app.netlify.com/drop](https://app.netlify.com/drop)
2. Arraste a pasta do projeto
3. Pronto — HTTPS automático, URL gerada instantaneamente

### GitHub Pages

```bash
git push origin main
# Settings → Pages → Source: main branch /root
```

---

## 🔧 Personalização

Antes de publicar, edite no `index.html`:

| O que | Onde |
|---|---|
| 📞 **WhatsApp** | `href="https://wa.me/5551997529107?text=..."` |
| 📸 **Instagram** | `href="https://instagram.com/maisbellaoticaportoalegre"` |
| 📄 **Catálogo PDF** | `href="#"` → colocar link real |
| 🖼️ **Avatar** | `src="assets/logo.jpg"` → trocar pela logo real |
| 🏷️ **Favicon** | `favicon.ico` / `favicon-*.png` |

---

## 🧑‍💻 Desenvolvido para

<p align="center">
  <strong>Mais Bela Ótica</strong><br>
  Porto Alegre, RS — Brasil
</p>

<p align="center">
  <sub>© 2026 — Todos os direitos reservados</sub>
</p>
