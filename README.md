# 🕷️ Spider-Man | Multiversos

Um projeto visual, interativo e totalmente estilizado apresentando três universos do Homem-Aranha no cinema: **Tobey Maguire**, **Andrew Garfield** e **Tom Holland**.  
Cada ator tem páginas próprias com seus respectivos filmes, galerias e um carrossel 3D interativo.

---

## 🔧 Tecnologias utilizadas

- **HTML5**
- **CSS3** (filtros de imagem, perspectiva, profundidade, efeitos 3D, responsividade)
- **JavaScript (ES6+)** — carrossel interativo, manipulação de DOM, animações
- **Fancybox 4** (galeria/lightbox)
- **SVG icons**
- **Google Fonts**

---

## ✨ Principais recursos implementados (o que foi trabalhado)

- Carrossel 3D interativo com movimento por clique e botões de controle  
- Efeitos de perspectiva e profundidade (`translateZ`, `rotateY`, `perspective`)  
- Filtros aplicados em imagens (blur, brightness, contrast, saturate)  
- Tilt effect (inclinação dos cards ao mover o mouse)  
- Hover com transições e escala do card selecionado  
- Background dinâmico (video / image) com fallback para imagem estática  
- Galeria com Fancybox para visualização em tela cheia e zoom  
- Navegação interna por ator / filme; ícone Home (SVG) para voltar ao `index.html`  

---

## 🖼️ Exemplos de código (copie para usar)

### 1) Ícone Home (HTML) — inserir na navegação das páginas internas:
```html
<li>
  <a href="../../index.html" class="home-icon" aria-label="Página inicial">
    <svg width="22" height="22" fill="white" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg" role="img" aria-hidden="true">
      <path d="M12 3l9 8h-3v10h-5V15H11v6H6V11H3z"/>
    </svg>
  </a>
</li>
```
```
/
├── index.html
├── assets/
│   ├── css/
│   │   ├── home-page-styles.css
│   │   └── internal.css
│   ├── scripts/
│   │   └── script.js
│   ├── images/
│   └── videos/
└── pages/
    ├── tobey-maguire/
    │   ├── spiderman1.html
    │   ├── spiderman2.html
    │   └── spiderman3.html
    ├── tom-holland/
    │   ├── spiderman1.html
    │   ├── spiderman2.html
    │   └── spiderman3.html
    └── andrew-garfield/
        ├── spiderman1.html
        └── spiderman2.html
```