# SyntaxWear

Landing page responsiva para uma loja online de tênis e sneakers, criada com HTML5 e CSS3. O projeto apresenta uma vitrine visual para a marca fictícia SyntaxWear, com hero promocional, categorias de produtos, grid editorial e rodapé com newsletter e redes sociais.

## Preview

O projeto pode ser executado diretamente no navegador abrindo o arquivo `index.html`.

## Sobre o projeto

A SyntaxWear foi desenvolvida como uma interface de e-commerce moderno para calçados, com foco em:

- Apresentação visual de produtos e coleções.
- Layout responsivo para desktop, tablet e mobile.
- Organização modular dos estilos CSS.
- Navegação principal com menu adaptado para telas menores.
- Seções de categorias, destaque de produto e grade de imagens.
- Rodapé completo com links institucionais, newsletter e redes sociais.

## Tecnologias utilizadas

- HTML5
- CSS3
- Google Fonts
- SVG para ícones
- Imagens locais para banners e produtos

## Estrutura de pastas

```text
.
|-- css/
|   |-- base.css
|   |-- layout.css
|   |-- reset.css
|   |-- variables.css
|   `-- components/
|       |-- footer.css
|       |-- header.css
|       |-- hero.css
|       |-- newsletter.css
|       |-- panel.css
|       |-- product-card.css
|       |-- product-category.css
|       `-- product-grid.css
|-- docs/
|-- fonts/
|-- images/
|   |-- banners/
|   |-- icons/
|   |-- logo/
|   `-- products/
|-- js/
|-- index.html
`-- README.md
```

## Como executar

1. Clone o repositório:

```bash
git clone <url-do-repositorio>
```

2. Acesse a pasta do projeto:

```bash
cd ecommercy-syntaxwear
```

3. Abra o arquivo `index.html` no navegador.

Também é possível usar uma extensão como Live Server no VS Code para visualizar alterações em tempo real.

## Principais seções

- **Header:** logo, categorias principais, links de acesso rápido e menu mobile.
- **Hero:** banner principal da coleção Krypton One com chamadas para ação.
- **Categorias:** cards visuais para Casual, Esporte, Moderno e Futurista.
- **Grid de produtos:** composição responsiva com produtos e destaque editorial.
- **Footer:** newsletter, redes sociais e links organizados por categoria.

## Responsividade

O layout possui media queries para adaptar a experiência em diferentes larguras de tela:

- Menu lateral em telas menores.
- Hero com imagem específica para mobile.
- Grid de produtos reorganizado para duas colunas no mobile.
- Cards de categoria ajustados para ocupar a largura disponível.
- Rodapé empilhado em dispositivos menores.

## Personalização

Alguns pontos simples para adaptar o projeto:

- Trocar imagens em `images/banners/` e `images/products/`.
- Atualizar ícones em `images/icons/`.
- Alterar a logo em `images/logo/logo.svg`.
- Ajustar fonte e variáveis globais em `css/variables.css`.
- Modificar textos e links diretamente no `index.html`.

## Melhorias futuras

- Adicionar páginas internas para produtos e categorias.
- Implementar carrinho de compras com JavaScript.
- Criar filtros de produtos por gênero, categoria e preço.
- Integrar formulário de newsletter com um backend.
- Melhorar acessibilidade com estados de foco e navegação por teclado.

## Autor

Projeto desenvolvido para estudos e prática de interfaces web responsivas.
