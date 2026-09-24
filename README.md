# Aula: CSS padrão x Tailwind CSS

Este repositório apresenta o mesmo exercício de layout desenvolvido de duas formas. A proposta é entender como o CSS funciona e comparar a escrita de estilos tradicionais com o uso de um framework CSS.

## Projetos

### CSS padrão

Em [aula-23-09-framework-css/css_padrao](aula-23-09-framework-css/css_padrao), o HTML utiliza classes próprias e importa o arquivo `style.css` externamente com a tag `<link>`.

Nesta versão, os estilos são escritos manualmente, incluindo:

- cores, fontes, bordas, margens e preenchimentos;
- modelo de caixa, com `content`, `padding`, `border` e `margin`;
- organização dos elementos com propriedades Flexbox;
- responsividade com `@media`.

Leia o [README do CSS padrão](aula-23-09-framework-css/css_padrao/README.md) para mais detalhes.

### Tailwind CSS

Em [aula-23-09-framework-css/tailwind_css](aula-23-09-framework-css/tailwind_css), o mesmo layout é construído usando classes utilitárias do Tailwind CSS.

Nesta versão, as classes aplicadas diretamente no HTML controlam espaçamento, cores, tipografia, bordas, Flexbox, responsividade, sombras e estados de interação.

Leia o [README do Tailwind CSS](aula-23-09-framework-css/tailwind_css/README.md) para mais detalhes.

## Como executar

Abra qualquer um dos arquivos `index.html` no navegador. A versão Tailwind precisa de conexão com a internet porque carrega o framework pelo CDN:

```html
<script src="https://cdn.jsdelivr.net/npm/@tailwindcss/browser@4"></script>
```

## Comparação principal

| CSS padrão | Tailwind CSS |
| --- | --- |
| Regras escritas em um arquivo `.css` | Classes utilitárias aplicadas no HTML |
| Separação clara entre estrutura e estilo | Desenvolvimento visual mais direto |
| Maior controle sobre nomes e abstrações | Muitas classes prontas para acelerar a construção |
| Exige criar e manter seletores próprios | Exige conhecer a convenção das classes |

Os dois projetos produzem a mesma ideia visual: uma área superior com 5 elementos e uma matriz central com 20 elementos organizados de forma responsiva.
