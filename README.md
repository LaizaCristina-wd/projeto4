# 🛋️ B.BRAND — Catálogo de Móveis

Catálogo online de móveis premium da marca **B.BRAND**, desenvolvido com HTML e CSS puro.

---

## 📸 Visão Geral

Página de catálogo com navegação centralizada, badge animado "FREE", seção de filtros e grid de produtos.

---

## 🗂️ Estrutura do Projeto

```
📁 projeto4/
├── Dockerfile
├── docker-compose.yml
├── README.md
└── src/
    ├── index.html
    ├── style.css
    └── img/
        ├── category.png
        ├── 3d-shapes.png
        ├── shopping-bag.png
        ├── explosion.png
        ├── blank-picture-frame-by-pink-velvet-armchair.jpg
        ├── download.jpeg
        └── pink-armchair-modern-living-room_23-2151988662.avif
```

---

## 🚀 Como Usar

1. Clone ou baixe o repositório
2. Abra o arquivo `index.html` no navegador

Não requer instalação, build ou dependências locais.

---

## 🐳 Docker

O projeto está dockerizado e pode ser rodado sem precisar de servidor local.

**Subir com Docker Compose:**

```bash
docker-compose up
```

**Ou manualmente com Docker:**

```bash
docker build -t bbrand-catalogo .
docker run -p 8080:80 bbrand-catalogo
```

Acesse em: [http://localhost:8080](http://localhost:8080)

---

## 🛠️ Tecnologias

- **HTML5** — estrutura semântica
- **CSS3** — layout, animações e responsividade
- **Docker** — containerização e deploy
- [Bootstrap Icons](https://icons.getbootstrap.com/) — ícone do botão de play
- [Google Fonts](https://fonts.google.com/) — fonte Quicksand

---

## ✨ Funcionalidades

- Badge **FREE** animado centralizado sobre o ícone
- Navegação centralizada no header
- Layout responsivo com CSS Grid
- Animações com `@keyframes` (entrada + pulso suave)
- Variáveis CSS (`--color-*`) para fácil customização de tema

---

## 🎨 Customização

As cores e fontes estão centralizadas em variáveis no `:root` do `style.css`:

```css
:root {
  --color-bg: rgb(27, 27, 27);
  --color-text: #ffd7d7;
  --color-accent: #ffd7d7;
  --color-accent-hover: #ffb3b3;
}
```

---

## 📄 Licença

Projeto de uso pessoal / estudo. © 2026 B.BRAND.