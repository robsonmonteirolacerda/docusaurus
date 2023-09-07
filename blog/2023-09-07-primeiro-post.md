---
slug: Primeiro-post
title: Referências de Markdown
authors: [rob]
tags: [markdown]
---

Guia resumido de Referências para Markdown.

<!--truncate-->

# Titulação

```bash
# Título <h1>
## Título <h2>
### Título <h3>
#### Título <h4>
##### Título <h5>
###### Título <h6>

```
Exemplos de titulação

# Título 
## Título 
### Título 
#### Título 
##### Título 
###### Título 


# Ênfase

Para adicionar ênfase ao conteúdo que será escrito, usa-se o asterisco * ou traço-baixo (underline) _:

Negrito: adicione dois asteriscos `**texto**` ou dois traços-baixos `__texto__` no início e no fim do conteúdo.
Itálico: adicione apenas um asterisco `*texto*` ou um traço-baixo `_texto_` no início e no fim do conteúdo.

Exemplos:
_Nam quam mi, semper eget dignissim non, ultricies nec magna. Quisque id justo ex. Pellentesque dui purus, aliquet sit amet nunc at, lobortis ornare turpis. Morbi rutrum rhoncus tellus. Maecenas hendrerit dolor non orci porttitor ultricies. Nulla iaculis tristique sodales. Aenean tincidunt rhoncus elit nec ornare. Proin aliquam non erat id commodo._

**Nam quam mi, semper eget dignissim non, ultricies nec magna. Quisque id justo ex. Pellentesque dui purus, aliquet sit amet nunc at, lobortis ornare turpis. Morbi rutrum rhoncus tellus. Maecenas hendrerit dolor non orci porttitor ultricies. Nulla iaculis tristique sodales. Aenean tincidunt rhoncus elit nec ornare. Proin aliquam non erat id commodo.**

Lista de itens 

Para listas não ordenadas, utilize um asterisco * na frente to item da lista:

```bash
* Primeiro
* Segundo
* Teceriro
* Etc...
```

* Primeiro
* Segundo
* Teceriro
* Etc...

Para ordenação utilize o número seguido de ponto `.`

```bash
1. Primeiro 
2. Segundo
3. Terceiro
```

1. Primeiro 
2. Segundo
3. Terceiro


# Links

 * Texto-âncora: Utiliza os caracteres `[]()`. 
  
  [Creditos da referência](https://docs.pipz.com/central-de-ajuda/learning-center/guia-basico-de-markdown#open)

 * Link direto: Para deixar o endereço do link visivel basta colocar entrar `<>`

    Exemplo: <https://pipz.com/br/>


# Imagens 

Adicionar uma imagem ao texto é semelhante ao inserir links-âncora. Basta adicionar uma exclamação `!`

```bash
![Alt ou título da imagem](URL da imagem)
```
Este é um exemplo ![gatinho](https://img.freepik.com/fotos-gratis/bela-foto-de-um-gatinho-branco-de-pelo-curto-britanico_181624-57681.jpg)

#Citação (Quote)

Use o sinal > no inicioda linha, para transformar um texto em uma citação ou comentário, semelhante ao código HYML `<blockquote>`
```bash
>Esta linha é um *blockquote*. O sinal usado abre e fecha este código no HTML. 
>Para adicionar mais uma linha à citação, basta teclar Enter para um novo
>código sinal. Isso gerará um novo parágrafo dentro de *blockquote*.
>Códigos de **negrito**, _itálico_ e <https://links.com> funcionam aqui.
```
>Esta linha é um *blockquote*. O sinal usado abre e fecha este código no HTML.
Para adicionar mais uma linha à citação, basta teclar Enter para um novo
código sinal. Isso gerará um novo parágrafo dentro de *blockquote*.
Códigos de **negrito**, _itálico_ e <https://links.com> funcionam aqui.

# Código (Code Highlight)

Temos dois modos de adicionar trechos de código ao Markdown:

* Código em linha (_inline_): Acentro grave ``` ` ``` no início e no final do código.
* Mútiplas linhas de código: Três aceontos graves ` ``` ` ou três tils ` ~~~ `

```bash
 Esta é uma linha que contém um ˋcódigoˋ.

 ˋˋˋ
Esta é uma linha de código
 ˋˋˋ
```
É possivel especificar o nome da linguagem que está sendo apresentada no bloco de código, basta adicionar o nome referente da linguagem de programação após o  ` ```  ` ou ` ~~~`, por exemplo ` ~~~javascript ` ou `~~~ruby `

```bash
~~~javascript
Esta é uma linha de código em Javascript.
~~~

~~~php
Esta é uma linha de código em PHP.
~~~

~~~html
Esta é uma linha de código em HTML.
~~~
```

```javascript
Esta é uma linha de código em Javascript.
```

```php
Esta é uma linha de código em PHP.
```

```html
Esta é uma linha de código em HTML.
```

# Tabela

Escolha os títulos das colunas e use | para delimitar as colunas. Depois, utilize hífen - na segunda linha para indicar que acima estão os títulos das colunas, usando novamente o | para delimitar colunas. Veja um exemplo abaixo:

```bash

Exemplo   | Valor do exemplo
--------- | ------
Exemplo 1 | R$ 10
Exemplo 2 | R$ 8
Exemplo 3 | R$ 7
Exemplo 4 | R$ 8

```
Exemplo   | Valor do exemplo
--------- | ------
Exemplo 1 | R$ 10
Exemplo 2 | R$ 8
Exemplo 3 | R$ 7
Exemplo 4 | R$ 8

Para especificar o tipo de alinhamento que deseja ter nas tabelas, utilize : ao lado do campo horizontal de hífens ---, na segunda linha da sua tabela. Veja abaixo:

* Alinhado a esquerda: usar `:` no lado esquerdo (alinhamento padrão);
* Alinhado a direita: usar `:` no lado direito;
* Centralizado: usar `:` dos dois lados.

Veja no exemplo:

```bash
Alinhado a esquerda | Centralizado | Alinhado a direita
:--------- | :------: | -------:
Valor | Valor | Valor
```
Alinhado a esquerda | Centralizado | Alinhado a direita
:--------- | :------: | -------:
Valor | Valor | Valor


creditos:

[Pipz Academy][def]

[def]: https://pipz.com/br/