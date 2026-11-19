# 📐 Aula 08 — CSS Grid

[⬅️ Voltar ao README principal](../README.md)

## 📌 Resumo da atividade

Construção de uma página completa com **CSS Grid**, o recurso de layout para organizar elementos em linhas e colunas. O exemplo é o **Portal Front-End**: cabeçalho, barra lateral com menu, área principal com cards dos conteúdos estudados e rodapé.

## 📂 Arquivos da pasta

| Arquivo | O que faz |
|---|---|
| `exemplo-de-aula01-grid.html` | Estrutura do portal com `header`, `aside`, `nav`, `main`, `article` (cards) e `footer` |
| `style01.css` | Layout em Grid, cards responsivos, menu lateral e efeitos de passagem do mouse |

## 🧠 Habilidades abordadas

- Layout de página com `display: grid`
- Posicionamento por áreas com `grid-template-areas` e `grid-area`
- Definição de colunas e linhas: `grid-template-columns: 220px 1fr` e `grid-template-rows: auto 1fr auto`
- Grid **responsivo** sem media query: `repeat(auto-fit, minmax(300px, 1fr))`
- Espaçamento entre itens com `gap`
- Reset com `box-sizing: border-box`
- Altura mínima de tela cheia com `min-height: 100vh`
- Cards com `border-radius` e `box-shadow`
- Efeitos com `:hover` e `transition`
- HTML semântico: `header`, `aside`, `nav`, `main`, `section`, `article`, `footer`
- Links de navegação transformados em botões com `display: block`

## ⚠️ Ponto de atenção

Na regra `.rodape` do `style01.css`, o valor `padding: 1opx` contém um erro de digitação (letra "o" no lugar do zero), então o navegador ignora a declaração. Para corrigir, use `padding: 10px`.

## 👀 Como visualizar

Abra `exemplo-de-aula01-grid.html` no navegador e mantenha o `style01.css` na mesma pasta. Redimensione a janela para ver os cards se reorganizarem.
