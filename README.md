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
  
exemplo em javascript de link de salto
  
  
  // HTML
<a href="#myAnchor">Ir para o meu link de salto</a>
<div id="myAnchor">Este é o meu link de salto</div>

// JavaScript
document.querySelector('a[href="#myAnchor"]').addEventListener('click', function (e) {
  e.preventDefault();
  document.querySelector(this.getAttribute('href')).scrollIntoView({
    behavior: 'smooth'
  });
});

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

  
  questão 6 
  
  qual é a sintaxe javascript correta para alterar o conteúdo de um parágrafo com um id de 'exemplo'?
Mensagem enviada. qual é a sintaxe javascript correta para alterar o conteúdo de um parágrafo com um id de 'exemplo'?
Procurando por “qual é a sintaxe javascript correta para alterar o conteúdo de um parágrafo com um id de 'exemplo'?”

Procurando por “qual é a sintaxe javascript correta para alterar o conteúdo de um parágrafo com um id de 'exemplo'?”

Gerando respostas para você…

Gerando respostas para você…

Para alterar o conteúdo de um parágrafo com um ID de ‘exemplo’ em JavaScript, você pode usar o método document.getElementById() para selecionar o elemento e o método innerHTML para alterar seu conteúdo 12.

Aqui está um exemplo de como fazer isso:

document.getElementById('exemplo').innerHTML = 'Novo conteúdo do parágrafo';

Este exemplo seleciona o elemento com o ID ‘exemplo’ e altera seu conteúdo para ‘Novo conteúdo do parágrafo’ 1.


Mensagem recebida. Para alterar o conteúdo de um parágrafo com um ID de 'exemplo' em JavaScript, você pode usar o método `document.getElementById()` para selecionar o elemento e o método `innerHTML` para alterar seu conteúdo . Aqui está um exemplo de como fazer isso: ```javascript document.getElementById('exemplo').innerHTML = 'Novo conteúdo do parágrafo'; ``` Este exemplo seleciona o elemento com 
Saiba mais:
1. delftstack.com
2. devmedia.com.br
3. brainly.com.br
4. developer.mozilla.org
+1 mais
14
de
20

O que é o método getElementById() em JavaScript?
Como eu posso selecionar um elemento HTML usando JavaScript?
Quais são algumas outras propriedades comuns de elementos HTML que os desenvolvedores podem alterar com JavaScript?
  Para alterar o conteúdo de um parágrafo com um ID de 'exemplo' em JavaScript, você pode usar o método `document.getElementById()` para selecionar o elemento e o método `innerHTML` para alterar seu conteúdo ¹⁴.

Aqui está um exemplo de como fazer isso:

```javascript
document.getElementById('exemplo').innerHTML = 'Novo conteúdo do parágrafo';
```

Este exemplo seleciona o elemento com o ID 'exemplo' e altera seu conteúdo para 'Novo conteúdo do parágrafo' ¹.

(1) JavaScript Alterar Texto | Delft Stack. https://www.delftstack.com/pt/howto/javascript/javascript-change-text/.
(2) DOM Element.innerHTML: como alterar um conteúdo de uma tag HTML - DevMedia. https://www.devmedia.com.br/dom-element-innerhtml-como-alterar-um-conteudo-de-uma-tag-html/43500.
(3) Qual é a sintaxe correta em JavaScript para alterar o conteúdo do .... https://brainly.com.br/tarefa/24569171.
(4) Sintaxe e tipos - JavaScript | MDN - MDN Web Docs. https://developer.mozilla.org/pt-BR/docs/Web/JavaScript/Guide/Grammar_and_types.

  questão 7 
  
  qual propriedade css e valor removeriam corretamente os marcadores de um item de lista? 
  
  Para remover os marcadores de um item de lista em CSS, você pode usar a propriedade `list-style-type` com o valor `none` ¹²³.

Aqui está um exemplo de como fazer isso:

```css
li {
  list-style-type: none;
}
```

Este exemplo remove os marcadores de todos os itens de lista em uma página ¹.

(1) Como fazer uma lista de marcadores HTML personalizados (UL) 📃 Usando .... https://br.atsit.in/archives/11409.
(2) Manipulando Listas - Aprendendo desenvolvimento web | MDN. https://developer.mozilla.org/pt-BR/docs/Learn/CSS/Styling_text/Styling_lists.
(3) As 3 propriedade CSS para estilização de marcadores de listas e seus .... https://maujor.com/tutorial/propriedades-css-para-estilizacao-de-listas.php.
(4) Especificidade - CSS | MDN - MDN Web Docs. https://developer.mozilla.org/pt-BR/docs/Web/CSS/Specificity.

  
  Questão 9 
  
  qual escolha não é um valor válido para a propriedade contain? layout, content, strict, all
  
  resposta - "content"
  
  A propriedade `contain` é uma propriedade CSS válida que permite que um autor indique que um elemento e seus conteúdos são, na medida do possível, independentes do resto da árvore do documento ¹. As opções válidas para o valor da propriedade `contain` são ¹:

- `layout`: indica que o elemento é independente do layout de seus pais e filhos.
- `paint`: indica que o elemento é independente da pintura de seus pais e filhos.
- `size`: indica que o elemento é independente do tamanho de seus pais e filhos.
- `strict`: indica que o elemento é independente do layout, pintura e tamanho de seus pais e filhos.


(1) contain - CSS | MDN - MDN Web Docs. https://developer.mozilla.org/pt-BR/docs/Web/CSS/contain.
(2) Conceitos básicos de flexbox - CSS | MDN - MDN Web Docs. https://developer.mozilla.org/pt-BR/docs/Web/CSS/CSS_Flexible_Box_Layout/Basic_Concepts_of_Flexbox.
(3) Utilizando propriedades CSS personalizadas (variáveis) - MDN. https://developer.mozilla.org/pt-BR/docs/Web/CSS/Using_CSS_custom_properties.

  questão 10 
  
  qual é a definição correta do elemento html <canvas> ?
  
  O elemento HTML <canvas> é utilizado para desenhar gráficos utilizando scripts (geralmente JavaScript). Ele pode ser usado para fazer composições de fotos e também para animações. O bloco <canvas> pode conter conteúdos alternativos caso o navegador não suporte o elemento <canvas>¹².

(1) canvas - HTML: Linguagem de Marcação de Hipertexto | MDN - MDN Web Docs. https://bing.com/search?q=defini%c3%a7%c3%a3o+do+elemento+html+canvas.
(2) canvas - HTML: Linguagem de Marcação de Hipertexto | MDN - MDN Web Docs. https://developer.mozilla.org/pt-BR/docs/Web/HTML/Element/canvas.
(3) Canvas (HTML5) – Wikipédia, a enciclopédia livre. https://pt.wikipedia.org/wiki/Canvas_%28HTML5%29.
(4) Canvas tutorial - APIs da Web | MDN - MDN Web Docs. https://developer.mozilla.org/pt-BR/docs/Web/API/Canvas_API/Tutorial.

  
  Usando JavaScript, você pode desenhar no canvas. Por exemplo, o código abaixo desenha um retângulo vermelho na tela¹²:
```javascript
var exemplo = document.getElementById('exemplo');
var contexto = exemplo.getContext('2d');
contexto.fillStyle = 'red';
contexto.fillRect(30, 30, 50, 50);
```

Origem: conversa com o Bing, 18/05/2023
(1) Canvas (HTML5) – Wikipédia, a enciclopédia livre. https://bing.com/search?q=exemplo+em+javascript+canvas.
(2) Canvas (HTML5) – Wikipédia, a enciclopédia livre. https://pt.wikipedia.org/wiki/Canvas_%28HTML5%29.
(3) Canvas tutorial - APIs da Web | MDN - MDN Web Docs. https://developer.mozilla.org/pt-BR/docs/Web/API/Canvas_API/Tutorial.
(4) Utilização básica do Canvas - APIs da Web | MDN - MDN Web Docs. https://developer.mozilla.org/pt-BR/docs/Web/API/Canvas_API/Tutorial/Basic_usage.
(5) HTML5 Canvas com JavaScript - DevMedia. https://www.devmedia.com.br/html5-canvas-com-javascript/29866.
  
  questão 11
  
  em uma página com muitas imagens, qual seria o efeito de adicionar loading= "lazy" à tag <img>?
  
  O atributo loading="lazy" em um elemento <img> pode ser usado para instruir o navegador a adiar o carregamento de imagens que estão fora da tela até que o usuário role para perto delas. Isso pode melhorar a velocidade de carregamento da página e reduzir o uso de dados e a contenção de rede durante a inicialização, adiando o carregamento de imagens para quando elas são realmente necessárias². No entanto, é importante não usar o lazy loading em imagens visíveis na tela durante a inicialização da página, pois isso pode afetar negativamente a experiência do usuário
  
(1) Lazy loading images - web.dev. https://web.dev/lazy-loading-images/.
(2) O que é Lazy Load e sua importância para otimização e ... - Alright. https://alright.com.br/o-que-e-lazy-load/.
(3) Lazy loading de imagens em navegadores - web.dev. https://web.dev/i18n/pt/browser-level-image-lazy-loading/.
(4) HTML img loading Attribute - W3Schools. https://www.w3schools.com/tags/att_img_loading.asp.

  Aqui está um exemplo de como desenhar um retângulo vermelho em um canvas usando JavaScript:

```javascript
var exemplo = document.getElementById('exemplo');
var contexto = exemplo.getContext('2d');
contexto.fillStyle = 'red';
contexto.fillRect(30, 30, 50, 50);
```

Este código desenha um retângulo vermelho na tela¹. Espero que isso ajude!

Origem: conversa com o Bing, 18/05/2023
(1) Canvas (HTML5) – Wikipédia, a enciclopédia livre. https://bing.com/search?q=exemplo+em+javascript+canvas.
(2) Canvas (HTML5) – Wikipédia, a enciclopédia livre. https://pt.wikipedia.org/wiki/Canvas_%28HTML5%29.
(3) Canvas tutorial - APIs da Web | MDN - MDN Web Docs. https://developer.mozilla.org/pt-BR/docs/Web/API/Canvas_API/Tutorial.
(4) Utilização básica do Canvas - APIs da Web | MDN - MDN Web Docs. https://developer.mozilla.org/pt-BR/docs/Web/API/Canvas_API/Tutorial/Basic_usage.
(5) HTML5 Canvas com JavaScript - DevMedia. https://www.devmedia.com.br/html5-canvas-com-javascript/29866.

  
  questão 12 
  
  qual é a maneira correta de vincular a uma folha de estilo externa do cabeçalho de um documento html?
  
  Para vincular uma folha de estilo externa ao cabeçalho de um documento HTML, você pode usar o elemento <link> com o atributo rel="stylesheet" e o atributo href apontando para o arquivo CSS externo. Aqui está um exemplo:

```html
<!DOCTYPE html>
<html>
<head>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  ...
</body>
</html>
```
questão  13 

  você usou display: nome em sua folha de estilo quais usuários poderão ver ou ouvir este conteúdo?

 no users 
  
  O valor "nome" do atributo display não é válido. Os valores válidos para o atributo display são "block", "inline", "inline-block", "flex", "grid", "table" e outros. O valor padrão é "block". O atributo display controla como um elemento HTML é exibido na página da web. Todos os usuários que acessam a página da web podem ver ou ouvir o conteúdo, a menos que haja restrições de acesso específicas definidas pelo desenvolvedor da página da web. Espero que isso ajude!
