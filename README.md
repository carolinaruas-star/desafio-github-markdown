# 📑 Formatação com Markdown

## O que é Markdown?

Markdown é uma linguagem de marcação leve que permite criar documentos formatados utilizando texto simples. É amplamente utilizada em **README.md**, documentações, Wikis, Gists, Issues e Pull Requests por ser simples, legível e fácil de manter.

O **GitHub Flavored Markdown (GFM)** é uma extensão do Markdown tradicional que adiciona recursos específicos do GitHub.

---

# 📝 Sintaxe Básica

## Títulos

```md
# Título 1
## Título 2
### Título 3
```

## Ênfase

```md
*Itálico*
**Negrito**
***Negrito e Itálico***
```

## Links

```md
[GitHub](https://github.com)
```

## Imagens

```md
![Descrição](url-da-imagem)
```

## Listas

**Não ordenada**

```md
- Item
- Item
  - Subitem
```

**Ordenada**

```md
1. Primeiro
2. Segundo
3. Terceiro
```

## Tabelas

```md
| Nome | Idade |
|------|-------|
| Ana  | 25    |
| João | 30    |
```

## Citações

```md
> Esta é uma citação.
```

## Código Inline

```md
Use `git status`.
```

## Blocos de Código

````md
```bash
git status
git add .
git commit -m "Primeiro commit"
```

Linguagens mais comuns para destaque de sintaxe:

bash
python
javascript
java
csharp
sql
html
css
Escape de Caracteres

Utilize \ para exibir caracteres reservados do Markdown.

\*\*Texto comum\*\*
HTML Inline

Quando necessário, é possível utilizar HTML.

Primeira linha<br>
Segunda linha
🚀 Recursos do GitHub Flavored Markdown (GFM)
Referenciar Issues e Pull Requests
#15
usuario/repositorio#15
Referenciar Commits
8304e9c
usuario/repositorio@8304e9c
Mencionar Usuários
@usuario
Lista de Tarefas
- [x] Concluído
- [ ] Pendente
⚡ Slash Commands

Comandos úteis disponíveis em Issues, Pull Requests e Discussões:

Comando	Função
/code	Inserir bloco de código
/details	Criar seção expansível
/saved-replies	Inserir resposta salva
/table	Gerar tabela
/tasklist	Criar lista de tarefas
/template	Inserir modelo de Issue ou PR
✅ Resumo
Markdown é uma linguagem simples para formatação de documentos.
Muito utilizada em projetos do GitHub para documentação.
Permite criar títulos, listas, tabelas, links, imagens, citações e blocos de código.
O GitHub Flavored Markdown (GFM) adiciona recursos como:
Referências a Issues e Pull Requests;
Referências a commits;
Menções de usuários;
Listas de tarefas;
Slash Commands.
