# Projeto CSS padrão

Esta é a versão do exercício construída com CSS tradicional. O objetivo é observar como a aparência e o comportamento dos elementos são definidos manualmente em um arquivo de estilos externo.

## Objetivo

Praticar os fundamentos do CSS e compreender a relação entre HTML e CSS, especialmente:

- seletores e classes;
- cores, fontes e tamanhos;
- modelo de caixa;
- propriedades de `margin`, `border`, `padding` e conteúdo;
- organização com Flexbox;
- adaptação para telas menores com media queries.

## Estrutura

- `index.html`: cria a estrutura da página, o título, a seção superior com 5 caixas e a seção central com 20 caixas.
- `style.css`: contém todos os estilos da página e é importado externamente pelo HTML:

```html
<link rel="stylesheet" href="style.css">
```

## Flexbox utilizado

As seções usam propriedades como `display: flex`, `flex-direction`, `flex-wrap`, `justify-content`, `align-items`, `align-content`, `gap` e `flex-basis` para organizar os elementos.

A regra `@media (max-width: 700px)` altera a largura das caixas para que elas se reorganizem melhor em telas pequenas.

## Como executar

Abra `index.html` diretamente no navegador. Não é necessário instalar dependências ou iniciar um servidor.

## O que observar

Nesta versão, cada decisão visual precisa ser escrita como uma regra CSS. Isso facilita entender o funcionamento do CSS, mas também exige criar e manter os seletores e valores manualmente.
