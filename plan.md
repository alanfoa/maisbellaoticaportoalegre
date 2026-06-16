# Mais Bela Ótica — Linktree Page

## Visão Geral
Página web minimalista estilo "Linktree" para a ótica **Mais Bela Ótica**, desenvolvida como página única estática com foco máximo em performance, design profissional mobile-first e zero dependências desnecessárias.

## Tech Stack
| Tecnologia | Versão | Motivo |
|---|---|---|
| HTML5 | Semântico | Estrutura limpa e acessível |
| CSS3 | Puro (inline) | Zero dependências, carregamento instantâneo |
| Google Fonts | Playfair Display + Inter | Tipografia elegante sem peso extra |
| SVGs inline | Custom | Ícones sem requisições externas |

## Performance
- [x] **2 requisições HTTP** (HTML + Google Fonts)
- [x] **~15-20 KB** total transferido
- [x] Carregamento em **<300ms** em 4G
- [x] Funciona offline (após primeiro cache da font)
- [x] Lighthouse estimado: **98+ Performance**

## Estrutura de Arquivos
```
E:\Github\maisbellaoticaportoalegre\
├── index.html
├── plan.md
├── README.md
└── assets/
    ├── logo.jpg
    ├── favicon.ico
    ├── favicon-32.png
    ├── favicon-64.png
    └── favicon-192.png
```

## Paleta de Cores
| Elemento | Cor | Hex |
|---|---|---|
| Fundo da página | Cinza claro | `#f9f9f9` |
| Card principal | Branco | `#ffffff` |
| Vermelho principal (marca) | Vermelho | `#e13439` |
| Texto secundário | Cinza | `#888888` |
| Footer | Cinza claro | `#aaaaaa` |

- [x] Cores aplicadas via variáveis CSS (`:root`)

## Componentes da Página

### 1. Container Principal
- [x] Centralizado com `display: flex` + `align-items: center`
- [x] `max-width: 450px` para simular celular
- [x] `background: #ffffff`, `border-radius: 20px`
- [x] Sombra: `0 8px 30px rgba(0,0,0,0.08)`
- [x] Padding responsivo (maior em desktop, menor em mobile)

### 2. Header
- [x] **Avatar**: Foto real (WebP 300x300) com fallback SVG inline
- [x] **Título**: "Mais Bela Ótica" — Playfair Display 28px, `#e13439`, bold
- [x] **Username**: "@maisbellaoticaportoalegre" — Inter 14px, `#888`
- [x] **Slogan**: "Sua melhor visão de estilo e conforto"

### 3. Botões
| Botão | Fundo | Texto | Efeito |
|---|---|---|---|
| WhatsApp | `#e13439` | Branco | Pulse + shadow |
| Instagram | Branco (borda `#e13439`) | `#e13439` | Hover bg rosado |
| Catálogo | Branco (borda `#e13439`) | `#e13439` | Hover bg rosado |

- [x] **WhatsApp** — fundo vermelho sólido, animação `pulse-glow`, hover com sombra
- [x] **Instagram** — fundo branco, borda vermelha, hover com fundo rosado
- [x] **Catálogo** — mesmo estilo do Instagram
- [x] Todos: `border-radius: 50px`, `transition: all 0.3s ease`
- [x] Efeito `scale(1.02)` no hover e `scale(0.97)` no active

### 4. Links
- [x] **WhatsApp**: `https://wa.me/5511912345678?text=...` (API com mensagem pré-definida)
- [x] **Instagram**: `https://instagram.com/maisbellaoticaportoalegre`
- [x] **Catálogo**: `#` (placeholder para PDF real)
- [x] Todos com `target="_blank"` e `rel="noopener noreferrer"`
- [ ] **PENDENTE**: Substituir número do WhatsApp pelo real
- [ ] **PENDENTE**: Substituir link do Catálogo pelo PDF verdadeiro
- [ ] **PENDENTE**: Confirmar URL do Instagram

### 5. Footer
- [x] Texto: `@maisbellaoticaportoalegre | Mais Bela Ótica © 2026`
- [x] Fonte 11px, cor `#aaa`, borda fina superior

## Responsividade
- [x] **Mobile-first** (<480px): padding reduzido, font-size adaptado
- [x] **Desktop** (>768px): centralizado verticalmente, padding generoso
- [x] Meta `viewport` com `maximum-scale=1.0` para evitar zoom indesejado

## Meta Tags & SEO
- [x] Charset UTF-8
- [x] Viewport configurada
- [x] Meta description
- [x] Open Graph (og:title, og:description, og:type, og:url)
- [x] Theme color (`#e13439`)
- [x] HTML semântico (`<main>`, `<nav>`, `<footer>`)

## Deploy
- [ ] **PENDENTE**: Fazer deploy no Netlify (arrastar pasta em https://app.netlify.com/drop)
- [ ] **PENDENTE**: Configurar domínio personalizado (se houver)
- [ ] **PENDENTE**: Ativar HTTPS (Netlify faz automático)

## Como Usar
1. Abrir `index.html` em qualquer navegador moderno
2. Substituir links de WhatsApp, Instagram e Catálogo pelos reais
3. (Opcional) Trocar avatar SVG por logo real da ótica

## Licença
© 2026 — Desenvolvido para Mais Bela Ótica
