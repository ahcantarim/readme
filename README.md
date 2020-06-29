## Sumário

- <a href="#títulos">Títulos</a>
- <a href="#parágrafos-e-quebras-de-linha">Parágrafos e quebras de linha</a>
- <a href="#ênfase">Ênfase</a>
- <a href="#links">Links</a>
- <a href="#blocos-de-citação">Blocos de citação</a>
- <a href="#listas">Listas</a>
- <a href="#imagens">Imagens</a>
- <a href="#tabelas">Tabelas</a>
- <a href="#task-lists">Task List</a>
- <a href="#código-inline-e-bloco">Código inline e em bloco</a>
- <a href="#backslash-scapes">Backslash Scapes</a>
- <a href="#referências">Referências</a>

## Títulos

Para marcar um título, utilizar `#` a quantidade de vezes que irá representar o nível do título. Exemplo:

\# Título nível 1:
# Título nível 1


\#\# Título nível 2:
## Título nível 2


\#\#\# Título nível 3:
### Título nível 3


\#\#\#\# Título nível 4:
#### Título nível 4


\#\#\#\#\# Título nível 5:
##### Título nível 5


\#\#\#\#\#\# Título nível 6:
###### Título nível 6


<a href="#sumário">🔝 Voltar ao topo</a>


## Parágrafos e quebras de linha

Para gerar parágrafos, escrever o texto pulando uma linha, ou colocar dois espaços em branco ao final:

Parágrafo 1.  
Parágrafo 2. 

Parágrafo 3.


<a href="#sumário">🔝 Voltar ao topo</a>


## Ênfase

Para itálico, utilizar `*` ou `_`.  

```
_Exemplo de texto_
```
_Exemplo de texto_


Para negrito, utilizar `**` ou `__`.  

```
**Exemplo de texto**
```
**Exemplo de texto**


Para negrito e itálico, utilizar `***`.  

```
***Exemplo de texto***
```
***Exemplo de texto***


Para riscado, utilizar `~~`.  

```
~~Exemplo de texto~~
```
~~Exemplo de texto~~


<a href="#sumário">🔝 Voltar ao topo</a>


## Links

### Links manuais

Para gerar links, utilizar `[]` e `()`.  
Dentro de `[]` colocar o texto do link e dentro de `()` colocar a URL:  

```
[Link Aqui](http://www.link.com):  
```
[Link Aqui](http://www.link.com)


Pode-se informar um texto após a URL, separando o link do texto por um espaço em branco.  
Esse texto será usado como `title`:

```
[Link Aqui](http://www.link.com "Clique aqui para acessar"):  
```
[Link Aqui](http://www.link.com "Clique aqui para acessar")

### Links automáticos

Se o texto do seu link é o próprio link, pode-se envolvê-lo entre `<>`, que o link será gerado automaticamente:

```
<https://www.google.com.br>  
```
<https://www.google.com.br>

E funciona também para e-mails:

```
<meu@email.com>  
```
<meu@email.com>


<a href="#sumário">🔝 Voltar ao topo</a>


## Blocos de citação

Para criar um bloco de citação, utilizar `>` no início da linha.

```
> Esse é um bloco de citação:
> Ele pode ter várias linhas por parágrafo.
>
> Inclusive, dando um espaço, você tem um novo parágrafo.
```

> Esse é um bloco de citação.
> Ele pode ter várias linhas por parágrafo.
>
> Inclusive, dando um espaço, você tem um novo parágrafo.


<a href="#sumário">🔝 Voltar ao topo</a>


## Listas

Para listas não ordenadas, utilizar `*`, `+` ou `-`.

```
* Item 1
+ Item 2
- Item 3
```
* Item 1
+ Item 2
- Item 3


Para listas ordenadas, utilizar o número seguido de `.`:

```
1. Item 1
2. Item 2
3. Item 3
```
1. Item 1
2. Item 2
3. Item 3


<a href="#sumário">🔝 Voltar ao topo</a>


## Imagens

Geração de imagens é bem parecido com a geração de links: você só precisa adicionar uma `!` no início. E o texto que você coloca entre os colchetes, é usado como `alt` na imagem:
Para adicionar imagens, utilizar como links, adicionando `!` no início.

```
![Account](https://cdn3.iconfinder.com/data/icons/signs-symbols-5/126/slice330-64.png)
```
![Account](https://cdn3.iconfinder.com/data/icons/signs-symbols-5/126/slice330-64.png)


O `title` também funciona como no link:

```
![Account](https://cdn3.iconfinder.com/data/icons/signs-symbols-5/126/slice330-64.png "Minha conta")
```
![Account](https://cdn3.iconfinder.com/data/icons/signs-symbols-5/126/slice330-64.png "Minha conta")


<a href="#sumário">🔝 Voltar ao topo</a>


## Tabelas

Para criar tabelas, utilizar `|` para separar colunas e `-` para separar linha de título:

```
| Alimentos | Preço |
| --------- | ----- |
| Arroz     | R$ 10 |
| Feijão    | R$ 8  |
| Batata    | R$ 7  |
| Macarrão  | R$ 8  |
```

| Alimentos | Preço |
| --------- | ----- |
| Arroz     | R$ 10 |
| Feijão    | R$ 8  |
| Batata    | R$ 7  |
| Macarrão  | R$ 8  |

Não é necessário alinhar com espaços, mas visualmente fica melhor.  
Para alinhar o conteúdo, utilizar `:` nos `-` que ficam abaixo do título da tabela.  

Se utilizar `:` no lado esquerdo, o alinhamento será feito à esquerda (padrão);  
Se utilizar `:` no lado direito, o alinhamento será feito à direita;  
Para centralizar, utilizar dos dois lados.  

| Alimentos | Preço |
| :-------: | ----: |
|   Arroz   | R$ 10 |
|  Feijão   |  R$ 8 |
|  Batata   |  R$ 7 |
| Macarrão  |  R$ 8 |


<a href="#sumário">🔝 Voltar ao topo</a>


## Task lists

Para criar uma lista de tarefas, utilizar a notação `- [ ] Texto da task` (para itens desmarcados) ou `- [x] Texto da task` (para itens marcados):

- [ ] Comprar arroz
- [ ] Comprar feijão
- [ ] Comprar batata
- [x] Comprar macarrão


<a href="#sumário">🔝 Voltar ao topo</a>


## Código inline e bloco

Para adicionar código a nível inline, utilizar `crase`:

```
O `<blockquote>` é uma tag HTML.
```
O `<blockquote>` é uma tag HTML.

Para gerar blocos de código, utilizar três `crases` no início da primeira e última linha, para marcar o início e o fim do bloco:

```
function sayHello() {
  return 'Hi';
}
```

Você ainda pode definir qual a linguagem que está sendo utilizada, para que seja feito `code highlight` no seu código. Para isso, informar a linguagem após as 3 crases, dessa forma:

### js
```js
function sayHello() {
  return 'Hi';
}
```


### bash
```bash
  # Clonando o repositório
  $ git clone https://github.com/ahcantarim/readme
```


<a href="#sumário">🔝 Voltar ao topo</a>


## Backslash Scapes

Para escapar caracteres que são parseados pelo [Markdown], utilizar a barra invertida `\` (backslash) seguida do caractere, para imprimí-lo literalmente. O escape funciona para os caracteres listados abaixo:

```
\   backslash (barra invertida)
`   backtick (crase)
*   asterisk (asterisco)
_   underscore
{}  curly braces (chaves)
[]  square brackets (colchetes)
()  parentheses (parênteses)
#   hash mark (sustenido)
+   plus sign (sinal de "mais" ou somar)
-   minus sign (hyphen) (sinal de "menos" ou hífen)
.   dot (ponto)
!   exclamation mark (ponto de exclamação)
```

Além de tudo isso, é importante saber também, que *é possível usar HTML junto com [Markdown]*.
Se você precisar adicionar uma classe em uma imagem para alinhar, ou colocar uma cor específica em alguma palavra, você pode usar tags HTML normalmente.


<a href="#sumário">🔝 Voltar ao topo</a>


## Referências

[Aprenda Markdown](https://blog.da2k.com.br/2015/02/08/aprenda-markdown/)

[Sintaxe básica de escrita e formatação no GitHub](https://help.github.com/pt/github/writing-on-github/basic-writing-and-formatting-syntax)

---

<p align="center">
  <a href="LICENSE" style="text-decoration: none"><img alt="License" src="https://img.shields.io/github/license/ahcantarim/readme" /></a>
  <a href="https://github.com/ahcantarim/readme/issues" style="text-decoration: none"><img alt="Issues" src="https://img.shields.io/github/issues/ahcantarim/readme" /></a>
  <a href="#" style="text-decoration: none"><img alt="GitHub Top Language" src="https://img.shields.io/github/languages/top/ahcantarim/readme" /></a>
  <a href="https://github.com/ahcantarim/readme/stargazers" style="text-decoration: none" ><img alt="Stars" src="https://img.shields.io/github/stars/ahcantarim/readme?style=social" /></a>
</p>

<p align="center">
  <a href="https://github.com/ahcantarim" target="_blank"><img alt="I am André Cantarim" src="https://img.shields.io/badge/I%20am-Andr%C3%A9_Cantarim-informational"></a>
  <a href="https://github.com/ahcantarim" target="_blank" ><img alt="Github" src="https://img.shields.io/badge/Github--%23F8952D?style=social&logo=github"></a>
  <a href="https://www.linkedin.com/in/ahcantarim/" target="_blank" ><img alt="LinkedIn" src="https://img.shields.io/badge/Linkedin--%23F8952D?style=social&logo=linkedin"></a>
  <a href="mailto:andre.cantarim@gmail.com" target="_blank" ><img alt="Email" src="https://img.shields.io/badge/Email--%23F8952D?style=social&logo=gmail"></a>
  <a href="https://api.whatsapp.com/send?phone=5511996834418" target="_blank" ><img alt="WhatsApp" src="https://img.shields.io/badge/Whatsapp--%23F8952D?style=social&logo=whatsapp"></a>
</p>

## License
This project is under the MIT license. See the file [LICENSE](LICENSE) for more details.