<h1 align="center">Cap: ☂️ Framework Bootstrap ☔</h1>
<div align="center"><a href="https://getbootstrap.com/"><img src="https://cdn.worldvectorlogo.com/logos/bootstrap-5-1.svg" height="170" title="Clique para acessar o site do Bootstrap"></a></div>
<p>Se trata de um framework para desenvolvimento de sites responsivos. Possui uma vasta biblioteca de componentes que facilita a agiliza o desenvolvimento de páginas web. É um dos frameworks mais conhecidos e usados para desenvolvimento front-end. Atualmente, o Framework está na beta da versão 5 e é com ela que iremos trabalhar!</p>

## Como funciona o Bootstrap?
<div align="center"><img src="https://user-images.githubusercontent.com/61624336/106330804-a5a05f80-6262-11eb-990b-77961ab5ca76.jpg"></div>

<p>O Bootstrap já possui um padrão para containers, divs e entre outras tags, como se fossem uma espécie de caixa, todas elas são chamadas pelos atributos <code>class</code>. Uma desvantagem do Bootstrap é a quantidade de linhas e classes no arquivo html, tornando o código mais longo do que estilizado pelo CSS puro. No entanto, é possível utilizar o Framework Bootstrap junto com a folha de Estilo, basta somente usar outros nomes para os seletores.</p>

Em até quantas colunas uma página pode ser dividida no Bootstrap? Até 12 colunas no total!

O Bootstrap está funcionando ao modificar o tamanho da tela para ver sua responsividade.

## Estrutura do Bootstrap
<p>Podemos estruturar ele no nosso arquivo baixando os componentes ou via CDN. Veremos os dois casos abaixo:</p>

### Via DOCUMENT
Baixe o arquivo do Bootstrap e descompacte-o. Em seguida, organize a estrutura de documentos da sua página de acordo com o exemplo abaixo.

![Sem Título-1](https://user-images.githubusercontent.com/61624336/106341041-8f060280-627a-11eb-940c-95ac5279d24c.jpg)
![Sem Título-1](https://user-images.githubusercontent.com/61624336/106341387-d9d44a00-627b-11eb-8726-5084ed02964a.jpg)

### Via CDN
Copie e cole o link abaixo no documento da sua página, logo você não precisará mais do documento, somente do link hospedado na internet. O que é ideal para deixar o seu site mais leve para a hospedagem.

<pre>&lt;link href="https://cdn.jsdelivr.net/npm/bootstrap@5.0.0-beta1/dist/css/bootstrap.min.css" rel="stylesheet"&gt;</pre>
<pre><script src="https://cdn.jsdelivr.net/npm/bootstrap@5.0.0-beta1/dist/js/bootstrap.bundle.min.js"></script></pre>

![Sem Título-1](https://user-images.githubusercontent.com/61624336/106341494-451e1c00-627c-11eb-9813-9484e32e3ba9.jpg)

## Diferença do arquivo css e do min
<p>O arquivo.css é todo indentado e legível, já o min possui o código todo junto, como se fosse uma única linha. O min aumenta a performance do site por ser mais leve do que o arquivo.css original.</p>

### Deixar elementos ocultos no Bootstrap
<pre>class="hidden-xs"</pre> 

## Documentation
https://getbootstrap.com/docs/5.0/getting-started/introduction/

<p>Na documentação do Bootstrap podemos utilizar modelos prontos de como criar elementos para a nossa página.</p>

## Criando containers personalizados para o seu site
![Sem Título-1](https://user-images.githubusercontent.com/61624336/106649682-b0176d80-6570-11eb-88be-8c651d26cf81.jpg)
![Sem Título-1](https://user-images.githubusercontent.com/61624336/106650159-52375580-6571-11eb-9af7-293c5976ffaf.jpg)

## Container ocupando o espaço total da página
<pre>class="container-fluid"</pre>
