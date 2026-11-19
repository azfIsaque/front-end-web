# 📦 Aula 07 — CSS: div, span e box model

[⬅️ Voltar ao README principal](../README.md)

## 📌 Resumo da atividade

Continuação do CSS com foco no **box model** (como cada elemento ocupa espaço na página) e na diferença entre **classe** e **id**. Há dois exercícios: um comparando seletores em `div` e `span`, e outro que monta o layout de um **Portal da Turma** com cabeçalho e menu de navegação.

## 📂 Arquivos da pasta

| Arquivo | O que faz |
|---|---|
| `exemplo1-class-id.html` | Compara `div` e `span` usando a classe `.caixa` e o id `#aviso` |
| `style01.css` | Estilo da classe `.caixa` (borda, cantos arredondados, `padding`, `box-shadow`) e do id `#aviso` (largura e altura) |
| `exemplo02-portal-turma.html` | Página "Portal da Turma" com `header`, `nav`, `main`, `article` e `section` |
| `style02.css` | Layout do portal: contêiner central, cabeçalho, menu horizontal com Flexbox e efeito `:hover` |

## 🧠 Habilidades abordadas

- Seletor de **id** (`#nome`) e de **classe** (`.nome`), e quando usar cada um
- Uso de `class` e `id` na mesma tag
- `<div>` (bloco) × `<span>` (trecho dentro do texto)
- **Box model:** `width`, `height`, `margin`, `padding` e `border`
- Cantos arredondados com `border-radius`
- Sombra com `box-shadow`
- **Seletor descendente** (`nav ul`, `nav a`)
- Menu horizontal com `display: flex`, `justify-content: center` e `gap`
- Remoção do estilo padrão de lista (`list-style: none`) e de link (`text-decoration: none`)
- Interação visual com a pseudo-classe `:hover`
- Estrutura semântica: `header`, `nav`, `main`, `article`, `section`

## ⚠️ Ponto de atenção

Em `exemplo1-class-id.html` falta a abertura da tag `<body>` (existe apenas o fechamento). O navegador corrige sozinho, mas vale adicionar `<body>` logo após o `</head>`.

## 👀 Como visualizar

Abra os arquivos `.html` no navegador e mantenha os `.css` na mesma pasta.
