# ⚙️ Aula 09 — Fundamentos do JavaScript

[⬅️ Voltar ao README principal](../README.md)

## 📌 Resumo da atividade

Primeiros passos com **JavaScript**. A aula começa mostrando onde o código pode ser inserido na página e termina com uma **calculadora de operações** que lê valores de um formulário, valida os dados e exibe o resultado.

## 📂 Arquivos da pasta

| Arquivo | O que faz |
|---|---|
| `exemplo-de-aula01-alert.html` | JavaScript no `<head>` (`alert`) e no `<body>` (`document.write`), com estilo via classe `.destaque` |
| `exemplo-de-aula-02-calc.html` | Formulário da calculadora: dois campos numéricos, quatro opções de operação (radio) e campo de resultado |
| `script.js` | Lógica da calculadora, ligada ao botão **Calcular** |
| `style02.css` | Visual da calculadora: formulário com borda dupla, campos em Grid e opções em Flexbox |

## 🧠 Habilidades abordadas

- Formas de inserir JavaScript: bloco `<script>` no `head`, no `body` e em arquivo externo (`<script src defer>`)
- Caixa de diálogo com `alert()` e escrita na página com `document.write()`
- Variáveis com `const` e `let`
- Conversão de texto para número com `Number()`
- **Seleção de elementos:** `getElementById()` e `querySelector()` (com `:checked`)
- **Eventos:** `addEventListener("click", ...)`
- Validação de entrada: campos vazios e operação não selecionada
- Estrutura de decisão: `if` e `switch...case`
- Operadores aritméticos (`+`, `-`, `*`, `/`) e comparação estrita (`===`)
- Escrita do resultado no campo com `.value`
- Entradas de formulário: `type="number"` com `step="any"`, `radio` e `readonly`
- Separação em camadas: HTML (estrutura), CSS (aparência) e JavaScript (comportamento)

## 👀 Como visualizar

Abra os arquivos `.html` no navegador, com `script.js` e `style02.css` na mesma pasta. O primeiro exemplo mostra um alerta ao carregar a página.
