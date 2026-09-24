# Projeto Tailwind CSS

Esta é a versão do mesmo exercício construída com Tailwind CSS. O objetivo é comparar o CSS tradicional com um framework que oferece classes utilitárias prontas para aplicar estilos diretamente no HTML.

## Objetivo

Reproduzir a estrutura do projeto CSS padrão usando classes do Tailwind para:

- cores, tipografia e espaçamento;
- bordas, sombras e arredondamentos;
- organização com Flexbox;
- responsividade com breakpoints;
- estados de interação, como `hover` e animações simples.

## Estrutura

- `index.html`: contém a estrutura e as classes utilitárias do Tailwind.
- Não há arquivo `style.css` nesta versão. O Tailwind é carregado pelo CDN no `<head>`:

```html
<script src="https://cdn.jsdelivr.net/npm/@tailwindcss/browser@4"></script>
```

A página contém 5 módulos principais e uma matriz com 20 elementos responsivos.

## Como executar

Abra `index.html` no navegador com conexão à internet. O CDN precisa ser acessado para que as classes do Tailwind sejam interpretadas.

## O que observar

No Tailwind, regras como `flex`, `flex-wrap`, `items-center`, `justify-evenly`, `gap-4`, `sm:basis-[9%]` e `hover:scale-105` são aplicadas diretamente nos elementos.

Isso permite criar e ajustar a interface rapidamente, mas o HTML fica mais carregado de classes e é necessário conhecer a convenção do framework.

## Relação com o projeto CSS padrão

A ideia estrutural é a mesma: uma área superior com 5 elementos e uma área central com 20 elementos. A diferença está na forma de escrever os estilos:

- no CSS padrão, as regras ficam em seletores no arquivo `style.css`;
- no Tailwind, as regras são compostas por classes utilitárias no próprio HTML.
