# Blog do Jaime

Bem-vindo ao repositório do meu blog pessoal, gerado com [Hugo](https://gohugo.io/) e o tema [Hextra](https://imfing.github.io/hextra/).

Site publicado em **[jaimedsf.github.io](https://jaimedsf.github.io/)**.

## Stack

- **Gerador**: Hugo (extended)
- **Tema**: Hextra (via Hugo Modules)
- **Hospedagem**: GitHub Pages
- **CI/CD**: GitHub Actions (`.github/workflows/hugo.yml`)

## Estrutura

```
content/
  _index.md          → página inicial
  about.md           → página "Sobre mim"
  posts/
    _index.md        → listagem de posts
    *.md             → posts do blog
hugo.yaml            → configuração do Hugo/Hextra
```

## Como adicionar um novo post

1. Crie um arquivo em `content/posts/meu-post.md`:
   ```markdown
   ---
   title: Título do post
   date: 2026-04-09
   tags:
     - dev
     - blog
   authors:
     - name: Jaime
   ---

   Conteúdo em markdown...
   ```
2. Commit e push na branch `main`.
3. O GitHub Actions builda e publica automaticamente.

## Rodando localmente

```bash
hugo server -D
```

Abra <http://localhost:1313/>.

## Build local

```bash
hugo --minify
```

O site gerado fica em `public/` (ignorado pelo git).

## Configuração do GitHub Pages

O source está configurado como **GitHub Actions** (Settings → Pages → Source).
