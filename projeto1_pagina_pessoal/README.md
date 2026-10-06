# 🌐 Projeto 1 — Minha Identidade na Web

Projeto desenvolvido para a disciplina de **Desenvolvimento Front-End para Web** (Prof. Vinicius Alves, 2026/2), utilizando **HTML5** e **CSS básico** para a criação de uma página pessoal.

**Nome de apresentação:** Isaque Moreira

## 📌 Sobre o Projeto

O site apresenta quem eu sou: minha trajetória, meus interesses, meus estudos atuais e um dos projetos que desenvolvi, o jogo **Maré de Esperança** (TCC do curso técnico na ETEC).

O objetivo foi praticar os fundamentos de **HTML**: estrutura semântica, navegação entre seções e páginas, imagens, listas, tabelas, áudio, vídeo e formulários. Também foi aplicado CSS básico (cores, fontes, alinhamento e espaçamentos) para dar identidade visual ao site.

## 🚀 Como Abrir o Projeto

1. Clone o repositório ou baixe o ZIP:

   ```bash
   git clone https://github.com/azfIsaque/front-end-web.git
   ```

2. Acesse a pasta do projeto:

   ```bash
   cd front-end-web/projeto1_pagina_pessoal
   ```

3. Abra o arquivo **`index.html`** no navegador (clique duas vezes no arquivo) ou use a extensão **Live Server** no VS Code.

> ⚠️ Mantenha todos os arquivos na mesma pasta para que imagens, áudio e CSS carreguem corretamente. O vídeo do YouTube e a imagem do jogo são carregados da internet, portanto é necessária conexão.

## 📂 Estrutura do Projeto

```text
front-end-web/
│
└── projeto1_pagina_pessoal/
    ├── index.html
    ├── paginas.html
    ├── style.css
    ├── niupo.png
    └── Laufey - Valentine (Official Audio) - Laufey.mp3
```

### 📄 `index.html`

Página principal, organizada com `header`, `nav`, `main` e `footer`, contendo:

* **Apresentação:** avatar, nome e breve introdução
* **Sobre mim:** texto sobre minha trajetória (ETEC, PROUNI, Ciência da Computação) e hobbies
* **Interesses:** lista não ordenada com meus interesses e lista ordenada com meus jogos favoritos
* **Estudos:** tabela de acompanhamento (tema, conhecimento atual e próximo passo), link para a página do projeto Maré de Esperança e formações
* **Mídia:** áudio de uma música favorita e trailer de **Hades** incorporado do YouTube
* **Contato:** formulário demonstrativo (os dados **não são enviados**)
* Menu de navegação com links internos para cada seção e link externo para o GitHub no rodapé

### 🎮 `paginas.html`

Página complementar sobre o **Maré de Esperança**, jogo de aventura *top-down* sobre poluição nos oceanos, voltado a crianças a partir de 10 anos. Apresenta o resumo e a história do jogo, com link para voltar à página inicial.

### 🎨 `style.css`

Folha de estilos da página principal, com paleta em tons de roxo, fonte monoespaçada, menu de navegação horizontal, tabela estilizada, avatar circular e botão com efeito *hover*.

## 🛠️ Recursos Utilizados

* HTML5 com estrutura semântica (`header`, `nav`, `main`, `section`, `footer`)
* Links internos (`href="#id"`), externos e entre páginas
* Imagens (local e remota)
* Lista não ordenada (`ul`) e lista ordenada (`ol`)
* Tabela com cabeçalho (`thead`, `th`, `caption`)
* Áudio com `<audio controls>` (sem autoplay)
* Vídeo incorporado com `<iframe>` (YouTube)
* Formulário com `label`, `input`, `textarea` e botão `type="button"`
* CSS básico: cores, fontes, margens, espaçamentos e alinhamento (Flexbox no menu)

## 🖼️ Fontes das Imagens e Mídias

| Recurso | Uso | Fonte |
|---|---|---|
| `niupo.png` | Avatar da página principal | Imagem local — *(preencher: criação própria / origem)* |
| Imagem do jogo Maré de Esperança | Capa do projeto nas duas páginas | Página do jogo no [itch.io](https://itch.io) — projeto de TCC desenvolvido por mim e meu grupo na ETEC |
| *Valentine* — Laufey | Áudio na seção Mídia | Áudio oficial da artista **Laufey** (YouTube). Direitos pertencem à artista; usado apenas para fins educacionais |
| Trailer de *Hades* | Vídeo na seção Mídia | [YouTube](https://www.youtube.com/watch?v=91t0ha9x0AE) — conteúdo da **Supergiant Games**; incorporado via `iframe` |

## ✅ Testes Realizados

- [ ] Links de seção do menu (Sobre mim, Interesses, Estudos, Mídia, Contato)
- [ ] Link de ida para `paginas.html` e link de volta para `index.html`
- [ ] Link externo para o GitHub
- [ ] Carregamento das imagens
- [ ] Reprodução e pausa do áudio
- [ ] Reprodução do vídeo incorporado
- [ ] Formulário: campos, rótulos e validação de e-mail
- [ ] Navegação por teclado (Tab)
- [ ] Abertura de uma cópia da pasta em outro local para conferir caminhos relativos

*(Marque cada item após testar.)*

## 🤖 Uso de IA

A IA foi utilizada como apoio na revisão do código e na elaboração deste README. Os textos, as escolhas de conteúdo e o código da página foram produzidos e revisados por mim, e sou capaz de explicar cada parte do projeto.

## 🎯 Objetivo

Colocar em prática os conhecimentos adquiridos nas aulas de **Front-End para Web**, construindo uma página pessoal funcional e bem estruturada com os recursos fundamentais do HTML.

## 👨‍💻 Autor

**Isaque Moreira**

Estudante de Ciência da Computação (Universidade Cruzeiro do Sul) e Técnico em Programação de Jogos Digitais, interessado em **desenvolvimento de jogos independentes, Python e desenvolvimento de sistemas**.

🔗 [GitHub](https://github.com/azfIsaque)

---

© 2026 Isaque Moreira — Projeto 1: Desenvolvimento Front-End para Web.
