# README Projeto Axolotls

Este projeto é um website dedicado a apresentar informações e curiosidades sobre animai fascinantes como axolotes. Esse README foi feito para especificar quando os requisitos foram cumpridos.

## Requisito 1: Conter no mínimo 3 páginas diferentes
O projeto supera o requisito mínimo, apresentando quatro páginas distintas:
- Página Inicial (Axolotls)
- Curiosidades
- Galeria
- Informações

## Requisito 2: Construção Semântica do Layout
Foi aplicada uma estrutura semântica consistente em todos os arquivos HTML:
- Uso de tags semânticas como `<header>`, `<nav>`, `<main>`, `<footer>`
- Minimização do uso de tags não semânticas `<div>`
- Estruturação clara e significativa do conteúdo com a estrutura básica do HTML

## Requisito 3: Responsividade
Implementamos responsividade através de:
- Uso de Flexbox no layout
- Breakpoints do Tailwind CSS
- Media queries no CSS para ajustes em diferentes tamanhos de tela

Exemplo no `informacoes.html`:
```html
<body class="bg-gray-100 flex items-center justify-center min-h-screen">
```

## Requisito 4: Diversidade de Tipografias
Exploramos variações tipográficas em:
- `estilizacao.css`: Definições de fontes, tamanhos e pesos
- `informacoes.html`: Uso de classes Tailwind para variações de texto

Exemplo no CSS:
```css
body {
  font-family: 'Arial', sans-serif;
  background-color: #f0f0f0;
  color: #333;
  line-height: 1.6;
  padding: 20px;
  font-size: 16px;
}
```

## Requisito 5: Paleta de Cores do Tailwind
Utilizamos a paleta de cores do Tailwind no arquivo `informacoes.html:
- Tons de `pink` para cabeçalhos e elementos de destaque
- `gray-100` para fundos
- Variações de cor para estados de hover

Exemplo:
```html
<thead class="bg-pink-600 text-white">
<tr class="hover:bg-pink-50 transition-colors">
```

## Requisito 6: Pseudo-classes
Implementamos duas pseudo-classes principais:
1. `:hover` (Tailwind)
   ```html
   <tr class="hover:bg-pink-50 transition-colors">
   ```

2. `:visited` (CSS)
   ```css
   a:visited {
     color: magenta;
   }
   ```

## Requisito 7: Tabela Personalizada
Criamos uma tabela detalhada na página de Informações com:
- Estilização personalizada
- Responsividade
- Cores e hover states distintos

## Tecnologias Utilizadas
- HTML5
- CSS3
- Tailwind CSS
- Tipografias variadas

## Considerações Finais
O projeto demonstra uma abordagem direcionada no design e desenvolvimento, atendendo os requisitos propostos.