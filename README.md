# Títulos (<h1> a <h6>)

Para marcar um título, você vai usar # a quantidade de vezes que irá representar o nível do título. Exemplo:

# Título nível 1
## Título nível 2
### Título nível 3
#### Título nível 4
##### Título nível 5
###### Título nível 6

# Parágrafos e quebras de linha (<p> e <br />)

Para gerar parágrafos, basta você escrever o texto pulando uma linha, ou colocando dois espaços em branco ao final:

Parágrafo.  
Parágrafo.  

# Ênfase (<strong> e <em>)

Para enfatizar uma palavras (<em>), usamos um * ou _:

Textos *com ênfase* podem ser feitos _dessas formas_.

Para dar forte ênfase em palavras (<strong>), você usa dois ** ou __:

Textos **com forte ênfase** podem ser feitos __dessas formas__.

# Links (<a>)

Para gerar links, você usa [](). Dentro dos colchetes você coloca o texto do link, e dentro dos parênteses, você coloca a URL:

[Blog do Da2k](https://blog.da2k.com.br)

Passando um texto após a URL, separando o link do texto por um espaço em branco, esse texto será usado como title:

[Blog do Da2k](https://blog.da2k.com.br "Clique e acesse agora!")

# Links automáticos

Se o texto do seu link é o próprio link, você pode envolvê-lo entre < e >, que o link será gerado automaticamente:

<https://www.google.com.br>

E isso funciona também para e-mails:

<meu@email.com>

# Blocos de citação (<blockquote>)

> Esse é um bloco de citação.
> Ele pode ter várias linhas por parágrafo.
>
> Inclusive, dando um espaço, você tem um novo parágrafo.

# Listas (<ul> e <ol>)

Para listas não ordenadas (<ul>), você pode usar *, + ou -. Veja:

* Item 1
* Item 2
* Item 3
  
+ Item 1
+ Item 2
+ Item 3
  
- Item 1
- Item 2
- Item 3

E para listas ordenadas, você usa o número, seguido de ponto:

1. Item 1
2. Item 2
3. Item 3

Alguns parsers renderizam automaticamente os próximos números, após o 1. Você só precisa usar * para os itens do 2 em diante:

1. Item 1
* Item 2
* Item 3

# Imagens (<img />)

Geração de imagens é bem parecido com a geração de links: você só precisa adicionar uma ! no início. E o texto que você coloca entre os colchetes, é usado como alt na imagem:

![Banana](http://cdn.osxdaily.com/wp-content/uploads/2013/07/dancing-banana.gif)

O title também funciona como no link:

![Banana](http://cdn.osxdaily.com/wp-content/uploads/2013/07/dancing-banana.gif "Olha a banana dançando!")

# Tabelas (<table>)

Para criar tabelas, também é bem simples:

Alimentos | Preço
--------- | ------
Arroz     | R$ 10
Feijão    | R$ 8
Batata    | R$ 7
Macarrão  | R$ 8

O título da tabela é marcado com os traços - abaixo da palavra. O pipe | cria as colunas. Não é necessário alinhar com espaços, mas visualmente fica melhor. Não precisa fazer se tiver preguiça :P

Você consegue alinhar usando : nos traços que ficam abaixo do título da tabela.

Se usar : no lado esquerdo, o alinhamento será feito à esquerda (padrão);
Se usar : no lado direito, o alinhamento será feito à direita;
E para centralizar, use dos dois lados.

Alimentos | Preço
:-------: | ------:
Arroz     | R$ 10
Feijão    | R$ 8
Batata    | R$ 7
Macarrão  | R$ 8

# Task lists

Basta você usar a notação - [ ] Texto da task (com um espaço dentro dos colchetes) para criar um checkbox desmarcado, ou então - [x] Texto da task, para um checkbox marcado. Exemplo:

- [ ] Comprar arroz
- [ ] Comprar feijão
- [ ] Comprar batata
- [x] Comprar macarrão

# Código inline e bloco (<code> e <pre>)

Vocế ainda pode adicionar trechos de código via Markdown. Para adicionar código a nível inline, você usa \`:

O `<blockquote>` é uma tag HTML.

E para gerar blocos de código, você simplesmente indenta o código 4 espaços (ou 1 tab) à frente do parágrafo:

Essa é a função sayHello():
    function sayHello() {
      return 'hi!';
    }

Isso é como está na documentação. Mas a maior parte dos parses que eu conheço não funcionam dessa forma. Eles geram blocos de código usando três crases no início da primeira e última linha, para marcar o início e o fim do bloco:

```
function sayHello() {
  return 'Hi';
}
```

O Github inclusive recomenda que se use as 3 crases, pois é mais fácil de visualizar e dar manutenção no código.

No Github, você ainda consegue definir qual a linguagem que está sendo utilizada, para que seja feito code highlight no seu código. Só passe a linguagem após as 3 crases, dessa forma:

```js
function sayHello() {
  return 'Hi';
}

# Backslash scapes

Para escapar caracteres que são parseados pelo Markdown, você pode usar a barra invertida \ (backslash), seguida do caractere, para imprimí-lo literalmente. O escape funciona para os caracteres listados abaixo:

```
\   backslash (barra invertida)
`   backtick (crase)
*   asterisk (asterisco)
_   underscore
{}  curly braces (chaves)
[]  square brackets (colchetes)
()  parentheses (parênteses)
#   hash mark (sustenido / hash / jogo da velha)
+   plus sign (sinal de "mais" ou somar)
-   minus sign (hyphen) (sinal de menos ou hífen)
.   dot (ponto)
!   exclamation mark (ponto de exclamação)
```

Além de tudo isso, é importante saber também, que é possível usar HTML junto com Markdown! Isso mesmo! Se você precisar adicionar uma classe em uma imagem para alinhar, ou colocar uma cor específica em alguma palavra, você pode usar tags HTML normalmente.

# Referências

<https://blog.da2k.com.br/2015/02/08/aprenda-markdown/>
<https://help.github.com/pt/github/writing-on-github/basic-writing-and-formatting-syntax>
<https://medium.com/@raullesteves/github-como-fazer-um-readme-md-bonit%C3%A3o-c85c8f154f8>

---

<img alt="PROJECT_NAME" src= "IMAGEM?raw=true" />

<p align="center">
  <a href="LICENSE" style="text-decoration: none">
    <img alt="License" src="https://img.shields.io/github/license/ahcantarim/readme" />
  </a>
  <a href="https://github.com/ahcantarim/readme/issues" style="text-decoration: none">
    <img alt="Issues" src="https://img.shields.io/github/issues/ahcantarim/readme" />
  </a>
  <a href="#" style="text-decoration: none">
    <img alt="GitHub Top Language" src="https://img.shields.io/github/languages/top/ahcantarim/readme" />
  </a>
  <a href="https://github.com/ahcantarim/readme/stargazers" style="text-decoration: none" >
    <img alt="Stars" src="https://img.shields.io/github/stars/ahcantarim/readme?style=social" />
  </a>
</p>

<p align="center">
  <a href="https://github.com/ahcantarim" target="_blank">
    <img alt="I am André Cantarim" src="https://img.shields.io/badge/I%20am-Andr%C3%A9_Cantarim-informational">
  </a>
  <a href="https://github.com/ahcantarim" target="_blank" >
    <img alt="Github" src="https://img.shields.io/badge/Github--%23F8952D?style=social&logo=github">
  </a>
  <a href="https://www.linkedin.com/in/ahcantarim/" target="_blank" >
    <img alt="LinkedIn" src="https://img.shields.io/badge/Linkedin--%23F8952D?style=social&logo=linkedin">
  </a>
  <a href="mailto:andre.cantarim@gmail.com" target="_blank" >
    <img alt="Email" src="https://img.shields.io/badge/Email--%23F8952D?style=social&logo=gmail">
  </a>
  <a href="https://api.whatsapp.com/send?phone=5511996834418" target="_blank" >
    <img alt="WhatsApp" src="https://img.shields.io/badge/Whatsapp--%23F8952D?style=social&logo=whatsapp">
  </a>
</p>

<p align="center">
 <a href="#-menu1">MENU 1</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
 <a href="#-menu2">MENU 2</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
 <a href="#-menu3">MENU 3</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
 <a href="#-menu4">MENU 4</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
 <a href="#-menu5">MENU 5</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
 <a href="#-menu6">MENU 6</a>
</p>

## Título 1
**Fonte em negrito** e fonte regular.

- [Título](link)
- [React](https://github.com/facebook/react)
- [React Native](https://github.com/facebook/react-native)
- [Figma](<https://www.figma.com/file/9TlOcj6l7D05fZhU12xWT3/Ecoleta-(Booster)>)

### Subtítulo 1
```bash
  # Clonando o repositório
  $ git clone https://github.com/ahcantarim/readme

  # Acessando o diretório DESTE projeto
  $ cd './readme'

  # Instalando as dependências
  $ npm install
```

## Título 2
- Fork it;
- Create a branch: `git checkout -b my-feature`;
- Submit your changes: `git commit -m 'feat: My new feature'`;
- Push your branch: `git push origin my-feature`.

After merging your receipt request to done, you can delete a branch from yours.

## License
This project is under the MIT license. See the file [LICENSE](LICENSE) for more details.

---

PROJECT_NAME