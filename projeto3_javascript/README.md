# Descubra seu caminho no Front-End

**Projeto 3 – Painel Interativo com JavaScript**
Disciplina: Desenvolvimento Front-End para Web · Universidade Cruzeiro do Sul · 2026/2

## Integrantes

| Nome | RGM | Responsabilidades |
|------|-----|-------------------|
| Isaque Moreira | 48034983 | Estrutura HTML, identidade visual (paleta roxa), CSS, JavaScript, testes e documentação |

## Tema

Uma página em que o visitante informa o **nome**, escolhe uma **área de interesse** (HTML, CSS ou JavaScript) e recebe uma **orientação personalizada** de estudos. A página também permite alternar entre **tema claro e tema escuro**, ambos em tons de roxo.

## Estrutura dos arquivos

```
projeto3_javascript/
├── index.html
├── README.md
├── css/
│   └── estilo.css
└── js/
    └── script.js
```

## Como usar

1. Abra o arquivo `index.html` em qualquer navegador.
2. Digite seu nome e escolha uma área de interesse.
3. Clique em **Gerar orientação** para ver a mensagem.
4. Clique em **Alterar tema** para alternar entre claro e escuro.

## Como funciona

- **HTML** define a estrutura: `header`, `main` e `footer`, um `input` para o nome, um `select` para a área de interesse, dois `button` (gerar orientação e alterar tema) e a área de resultado.
- **CSS** cuida da aparência. As cores ficam em variáveis (`--primaria`, `--fundo` etc.). O tema escuro é ativado pela classe `.tema-escuro` no `body`, que apenas redefine essas variáveis. Há estilos para `:hover` nos botões, mensagem de erro/resultado e uma *media query* para telas menores.
- **JavaScript** dá o comportamento:
  1. localiza os elementos da página;
  2. espera o clique nos botões;
  3. lê o nome e a área escolhida;
  4. valida se o nome não está vazio;
  5. escolhe a orientação com `switch`;
  6. exibe a mensagem na própria página com `textContent`.

Se o nome estiver vazio, a página mostra uma mensagem pedindo o preenchimento (em estilo de erro) e devolve o foco ao campo.

## Comandos JavaScript utilizados

| Comando | Onde e para que é usado |
|---------|-------------------------|
| `document.getElementById()` | Localiza o campo de nome, o select, os botões e a área de resultado. |
| `const` e `let` | `const` guarda os elementos e valores que não mudam; `let` guarda a mensagem que é definida dentro do `switch`. |
| `addEventListener('click', ...)` | Executa `gerarOrientacao` e `alternarTema` quando os botões são clicados. |
| `.value` e `.trim()` | Lê o texto digitado e remove espaços das pontas, para detectar nome vazio ou só com espaços. |
| `if/else` | Decide entre mostrar o erro (nome vazio) ou a orientação. |
| `switch` | Escolhe uma orientação diferente para HTML, CSS e JavaScript. |
| Template string `` `Olá, ${nome}!` `` | Insere o nome do visitante dentro da mensagem. |
| `.textContent` | Escreve a mensagem na área de resultado (sem interpretar HTML). |
| `function` | Organiza o código em `mostrarMensagem`, `criarOrientacao`, `gerarOrientacao` e `alternarTema`. |
| `.classList.toggle()` | Adiciona/remove a classe `tema-escuro` no `body` e as classes de erro no resultado. |

## Testes realizados

- [x] Nome vazio e nome com apenas espaços exibem a orientação de preenchimento.
- [x] HTML, CSS e JavaScript geram mensagens diferentes.
- [x] O botão **Alterar tema** alterna entre claro e escuro.
- [x] A página foi testada em tela pequena (largura de celular).

## Observação

Nenhum dado pessoal (RGM, telefone, endereço) aparece na página pública; o RGM consta apenas neste README, destinado ao professor.
