# Blog do Jaime

Este repositório hospeda meu blog pessoal gerado com [Marmite](https://rochacbruno.github.io/marmite/).

## Como adicionar um novo post

1. Crie um arquivo Markdown em `posts/` com o conteúdo do post.
2. Rode `marmite posts docs` para atualizar o site estático em `docs/`.
3. Remova os arquivos binários gerados automaticamente:
   `rm docs/static/Atkinson-Hyperlegible-Regular-102.woff docs/static/avatar-placeholder.png`
4. Envie as alterações para o GitHub.

O GitHub Pages está configurado para servir o conteúdo da pasta `docs/`.
