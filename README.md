# Meu Site Bootstrap

Site didático construído com HTML, CSS e Bootstrap 5 como introdução à biblioteca. Projeto desenvolvido a partir de um roteiro de aula.

**Demo ao vivo:** https://vitorviblen.github.io/meu-site-bootstrap/

## Páginas

- **`index.html`** — Carrossel de imagens + galeria de fotos com efeito hover
- **`produtos.html`** — Tabela responsiva com listras e destaque ao passar o mouse
- **`contato.html`** — Formulário com inputs, select, textarea e checkbox

## Tecnologias

- HTML5
- CSS3 (gradientes, sombras, transições, media queries)
- [Bootstrap 5.3.3](https://getbootstrap.com/) via CDN
- Fonte [Inter](https://fonts.google.com/specimen/Inter) via Google Fonts
- Imagens placeholder via [picsum.photos](https://picsum.photos)

## Como rodar localmente

Abra `index.html` direto no navegador (duplo clique) ou suba um servidor simples:

```bash
python3 -m http.server 8000
```

Depois acesse [http://localhost:8000](http://localhost:8000).

## Estrutura

```
meu-site-bootstrap/
├── index.html
├── produtos.html
├── contato.html
├── css/
│   └── style.css
└── README.md
```

## Conceitos abordados

- Grid system do Bootstrap (`container`, `row`, `col-*`)
- Componentes interativos (navbar, carousel, table, form)
- Combinação de classes do Bootstrap com CSS próprio
- Layout responsivo com breakpoints
