# Deriva — Landing Page de Loja de Pranchas

Projeto de estudo de front-end: landing page para uma marca fictícia de pranchas de surf shapeadas sob encomenda, com layout inspirado em padrões de sites de destaque (hero em tela cheia, seções alternadas de imagem/texto, scroll storytelling).

Marca, modelos e fichas técnicas são fictícios — sem afiliação com fabricantes reais de pranchas. Todo o conteúdo (textos, estrutura, código) é original.

## Stack
- HTML5, CSS3 (sem framework), JavaScript puro
- Fontes: [Bricolage Grotesque](https://fonts.google.com/specimen/Bricolage+Grotesque), [Space Grotesk](https://fonts.google.com/specimen/Space+Grotesk) e [IBM Plex Mono](https://fonts.google.com/specimen/IBM+Plex+Mono) (Google Fonts)
- Fotografias: [Unsplash](https://unsplash.com) (uso livre, sem necessidade de atribuição — créditos listados no rodapé do site por boa prática)

## Estrutura
```
deriva-surfboards/
├── index.html
├── css/style.css
└── js/script.js
```

## Rodando localmente
Basta abrir `index.html` no navegador, ou servir a pasta com qualquer servidor estático:
```bash
npx serve .
```

## O que este projeto pratica
- Layout responsivo com CSS Grid e Flexbox
- "Ficha técnica" de produto estilizada como etiqueta de shaper (`<dl>` semântico)
- Galeria horizontal arrastável (drag-to-scroll)
- Scroll reveal via `IntersectionObserver`
- Acessibilidade básica: `prefers-reduced-motion`, foco visível, texto alternativo em imagens
