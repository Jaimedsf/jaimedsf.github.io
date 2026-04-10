---
title: Dicas de Markdown
description: "Guia prático de formatação Markdown: cabeçalhos, listas, tabelas, código e front matter."
date: 2025-06-04
tags:
  - markdown
  - dicas
authors:
  - name: Jaime
---

A seguir, algumas dicas rápidas para você formatar seus posts com Markdown de forma eficiente e clara. Markdown é uma linguagem de marcação leve que permite criar texto rico apenas adicionando símbolos simples ao redor do conteúdo. Este guia aborda desde a formatação básica até elementos mais avançados, como tabelas e blocos de código, tornando seus posts mais legíveis e profissionais.

## Formatação Básica

### Cabeçalhos (Headings)

Use o símbolo `#` seguido de espaço para criar títulos hierárquicos. Há seis níveis de cabeçalho, de `#` (título principal) a `######` (título de nível 6).

```markdown
# Título Nível 1
## Título Nível 2
### Título Nível 3
```

### Texto em Negrito e Itálico

- **Negrito**: coloque dois asteriscos `**` ou dois underlines `__` ao redor do texto.
- *Itálico*: coloque um asterisco `*` ou um underline `_` em cada lado do trecho.

### Citação em Bloco

```markdown
> Esta é uma citação de exemplo.
> Ela pode ocupar várias linhas.
```

## Listas

### Lista Não Ordenada

```markdown
- Item 1
- Item 2
  - Subitem 2.1
```

### Lista Ordenada

```markdown
1. Primeiro passo
2. Segundo passo
3. Terceiro passo
```

## Links e Imagens

### Links

```markdown
[Texto do Link](https://www.exemplo.com)
```

### Imagens

```markdown
![Texto Alternativo](https://www.exemplo.com/imagem.jpg "Título da Imagem")
```

## Blocos de Código

Para blocos maiores, utilize três crases antes e depois, especificando a linguagem para realce de sintaxe:

````markdown
```javascript
function saudacao() {
  console.log("Olá, mundo!");
}
```
````

## Tabelas

```markdown
| Linguagem  | Criado em | Paradigma           |
|------------|-----------|---------------------|
| JavaScript | 1995      | Multiparadigma      |
| Python     | 1991      | Orientado a Objetos |
| Go         | 2009      | Concorrente         |
```

Alinhamento de colunas:

- `:---` alinha à esquerda
- `:---:` centraliza
- `---:` alinha à direita

## Dicas Avançadas

### Task Lists

```markdown
- [x] Item concluído
- [ ] Item pendente
```

### Strikethrough

```markdown
~~Texto riscado~~
```

### Front matter (YAML)

Essencial em geradores estáticos como Hugo:

```yaml
---
title: "Meu Post em Markdown"
date: 2025-06-04
tags:
  - dica
  - markdown
---
```

Com essas diretrizes e exemplos, você estará pronto para formatar seus posts com Markdown de maneira profissional, legível e visualmente atraente.
