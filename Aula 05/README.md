# 📝 Aula 05 — HTML: formulários e recursos multimídia

[⬅️ Voltar ao README principal](../README.md)

## 📌 Resumo da atividade

Criação de um **formulário de cadastro** com validação nativa do navegador e uso dos elementos de mídia do HTML5, `<video>` e `<audio>`, que tocam arquivos sem precisar de plugins.

## 📂 Arquivos da pasta

| Arquivo | O que faz |
|---|---|
| `exemplo-de-aula01-form.html` | Formulário "Cadastro do Estudante" com nome, e-mail e senha, e botões de enviar e limpar |
| `exemplo-de-aula02-video.html` | Dois vídeos com controles: um arquivo local (`.mp4`) e outro carregado por link |
| `exemplo-de-aula03-audio_js.html` | Elemento de áudio em loop, com o volume ajustado para 50% via JavaScript |
| `16656093_3840_2160_60fps.mp4` | Vídeo usado no exemplo 2 (arquivo grande, cerca de 19 MB) |
| `metal-pipe-sound.mp3` | Áudio usado no exemplo 3 |

## 🧠 Habilidades abordadas

- Estrutura de formulário com `<form>`
- Campos `<input>` dos tipos `text`, `email` e `password`
- Associação de `<label for>` ao `id` do campo (acessibilidade)
- Diferença entre `id` e `name`
- Validação nativa com o atributo `required` e dicas com `placeholder`
- Botões `type="submit"` e `type="reset"`
- Vídeo com `<video controls>` e `<source>`, e texto alternativo para navegadores sem suporte
- Áudio com `<audio>`, `<source>` e o atributo `loop`
- Acesso a um elemento pelo `id` com `document.getElementById()` e ajuste de `volume`

## 💡 Observação

O elemento `<audio>` do exemplo 3 não tem o atributo `controls` nem `autoplay`, então a página só prepara o áudio (loop e volume). Para ouvir o som, é preciso adicionar `controls` à tag.

## 👀 Como visualizar

Abra os arquivos `.html` no navegador e mantenha o `.mp4` e o `.mp3` na mesma pasta. O segundo vídeo depende de conexão com a internet.
