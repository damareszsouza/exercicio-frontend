# exercicio-frontend
Praticas de front end perguntas e respostas exercício 1

questão 1

complete o codigo 

Para adicionar um elemento a uma matriz em JavaScript, você pode usar o método push(). O método push() adiciona um ou mais elementos ao final de uma matriz e retorna o novo comprimento da matriz. Aqui está um exemplo de como você pode adicionar um elemento à sua matriz:

var currencies = ["bitcoin", "ethereum"];
currencies.push("litecoin");
console.log(currencies);

Isso  resutarar 

["bitcoin", "ethereum", "litecoin"]

To add an element to an array in JavaScript, you can use the push() method. The push() method adds one or more elements to the end of an array and returns the new length of the array. Here's an example of how you can add an element to your array:

```javascript
var currencies = ["bitcoin", "ethereum"];
currencies.push("litecoin");
console.log(currencies);
```

This will output:

```
["bitcoin", "ethereum", "litecoin"]
```

Questão 2

o que significa o termo 'polyfill' quando usado no desenvo de software ?


Polyfill é um módulo ou recurso de código que atende à necessidade de um desenvolvedor. O termo foi cunhado para descrever algo que preencheria a lacuna quando uma certa plataforma não possui a funcionalidade que os desenvolvedores esperavam12.

Na prática, os polyfills permitem que os desenvolvedores Web usem uma API independentemente de ser suportada por um navegador ou não, e geralmente com sobrecarga mínima


Claro! Aqui está um exemplo de código JavaScript de polyfill para o método `Math.trunc()`²:

```javascript
Math.trunc = Math.trunc || function(x) {
  return x < 0 ? Math.ceil(x) : Math.floor(x);
}
```

É um pedaço de codigo que fornece fucionalidade moderna em um navegaor que não suporta.

exp:

(1) Math.trunc() - JavaScript | MDN - MDN Web Docs. https://developer.mozilla.org/pt-BR/docs/Web/JavaScript/Reference/Global_Objects/Math/trunc.
(2) Math.trunc() - JavaScript | MDN - MDN Web Docs. https://bing.com/search?q=exemplo+de+codigo+javascript+de+polyfill.
(3) javascript - O que é Polyfill? - Stack Overflow em Português. https://pt.stackoverflow.com/questions/194857/o-que-%c3%a9-polyfill.
(4) Object.create() - JavaScript | MDN - MDN Web Docs. https://developer.mozilla.org/pt-BR/docs/Web/JavaScript/Reference/Global_Objects/Object/create.
(5) Polyfills and transpilers - The Modern JavaScript Tutorial. https://javascript.info/polyfills.

(1) 5 Ways To Add Elements To Javascript Array (Simple Examples) - Code Boxx. https://code-boxx.com/add-elements-javascript-array/.
(2) 6 Ways to Insert Elements to an Array in JavaScript. https://howtocreateapps.com/ways-to-insert-elements-to-an-array-in-javascript/.
(3) JavaScript Array push() Method - W3Schools. https://www.w3schools.com/jsref/jsref_push.asp.
(4) How To Add New Elements To A JavaScript Array - W3docs. https://www.w3docs.com/snippets/javascript/how-to-add-new-elements-to-a-javascript-array.html.
(5) javascript - How to append something to an array? - Stack Overflow. https://stackoverflow.com/questions/351409/how-to-append-something-to-an-array.


Qual escolha não é m valor doatributo type do elemento <input>?

address 

Os valores possíveis para o atributo `type` do elemento `input` são: `text`, `password`, `checkbox`, `radio`, `submit`, `reset`, `file`, `hidden`, `image`, `button`, `date`, `datetime-local`, `month`, `week`, `time`, `email`, `number`, `range`, `search`, e `tel`¹.


(1) <input> - HTML: Linguagem de Marcação de Hipertexto | MDN. https://developer.mozilla.org/pt-BR/docs/Web/HT
(2) Atributos - HTML: Linguagem de Marcação de Hipertexto | MDN. https://developer.mozilla.org/pt-BR/docs/Web/HTML/Attributes.
(3) <input type="date"> - HTML: Linguagem de Marcação de Hipertexto | MDN. https://developer.mozilla.org/pt-BR/docs/Web/HTML/Element/input/date.


Não, `address` não faz parte do elemento `input`². O elemento HTML `<input>` é usado para criar controles interativos para formulários baseados na web para receber dados do usuário. A semântica de um `<input>` varia consideravelmente dependendo do valor de seu atributo `type`¹.

(1) <address> - HTML: Linguagem de Marcação de Hipertexto | MDN. https://developer.mozilla.org/pt-BR/docs/Web/HTML/Element/address.
(2) <input> - HTML: Linguagem de Marcação de Hipertexto | MDN. https://developer.mozilla.org/pt-BR/docs/Web/HTML/Element/input.
(3) HTML input: criando formulários interativos! - Blog da Trybe. https://blog.betrybe.com/html/input-html/.

questão 4



  no código a seguir, a variável fruta recebeu um valor de maçã. como você mudaria o valor para ameixa?

deixe fruta = 'maçã';
  
  Para mudar o valor da variável `fruta` para `ameixa`, você pode simplesmente atribuir o novo valor à variável:

```javascript
fruta = 'ameixa';
```

  
  Questão 5 
  
  
  o que é um link de salto
  
  um link colocado carlu <body> par apermitir que o usuario pule para o conteudo principal 
  
 
  
  Um link de salto (ou link de âncora) é um link que leva o usuário para uma parte específica da página (ou para uma página externa) instantaneamente. Os destinos de âncora são normalmente especificados usando o elemento `a` (nomeando-o com o atributo `name`), ou por qualquer outro elemento (nomeando com o atributo `id`) ¹².


(1) Como Criar Links de Âncora no WordPress (3 Métodos Fáceis) - Kinsta. https://bing.com/search?q=o+que+%c3%a9+um+link+de+salto%3f.
(2) Como Criar Links de Âncora no WordPress (3 Métodos Fáceis) - Kinsta. https://kinsta.com/pt/blog/links-de-ancora/.
(3) Como criar links de salto de âncora no WordPress. https://bforbloggers.com/pt/how-to-create-anchor-jump-links-in-wordpress/.
(4) Criando um link de âncora – Central de ajuda do Squarespace. https://support.squarespace.com/hc/pt/articles/207135178-Criando-um-link-de-%C3%A2ncora.
