# 😃 Markdown

Tudo que você precisa saber sobre essa linguagem de marcação!

## Sintaxe

### Comentários

Memso usado no HTML: `<!-- Comments -->`

### Headings

Cabeçalhos que serão convetidos para tags `h1 - h6`

- `#` h1
- `##` h2
- `###` h3
- `####` h4
- `#####` h5
- `######` h6

### Linhas de divisão

Pode ser utilizando tanto `---` como `***`

### Texto

*Ênfase* será transformado em `<em>`, pode ser feito utilizando `*Texto*`

**Negrito** será transformado em `<strong>`, pode ser feito utilizando `**Texto**`

_Itálico_ será transformado em `<i>`, pode ser feito utilizando `_Texto_`

~~Taxado~~ será transformado em `<del>`, pode ser feito utilizando `~~Texto~~`

### Listas

#### Lista ordenada:

```markdown
1. Item 1
1. Item 2
   1. item 2.1
1. Item 3
```

vai virar:

1. Item 1
1. Item 2
   1. item 2.1
1. Item 3

#### Lista não ordenada:

```markdown
- Item 1
- Item 2
  - item 2.1
- Item 3
```

se transforma em:

- Item 1
- Item 2
  - item 2.1
- Item 3

#### Lista com checkbox

```markdown
- [ ] Item 1
- [x] Item 2
  - [ ] Item 2.1
- [ ] Item 3
```

vira:

- [ ] Item 1
- [x] Item 2
  - [ ] Item 2.1
- [ ] Item 3

### Citação (blockquote)

```markdown
> citação
> > citação aninhada
```

> citação
> > citação aninhada

### Código

Código inline pode ser escrito com uma crase antes e depois: `\`code\``

Se for em bloco, use 3 crases antes e depois.


### Tabela

```markdown
| Name | Date       |
| ---- | ---------- |
| A    | 10/05/2020 |
| B    | 10/05/2020 |
```

| Name | Date       |
| ---- | ---------- |
| A    | 10/05/2020 |
| B    | 10/05/2020 |

### Links e imagens

Links utilizam a seguinte sintaxe: `[Texto do link](url "Titulo")`

Enquanto imagens: `[texto alt](url/da/imagem)`

## Links úteis

- [Wikipedia Markdown](https://pt.wikipedia.org/wiki/Markdown)
-  [John Gruber Makrdown doc](https://daringfireball.net/projects/markdown/)
-  [Markdown Emoji Cheat Sheet](https://github.com/ikatyang/emoji-cheat-sheet)
-  [MDX](https://github.com/mdx-js/mdx)
-  [Welcome UI - Usando docz e mdx](http://welcome-ui.com/components/dropdown-menu)
-  [Editor de markdown online](http://stackedit.io/)