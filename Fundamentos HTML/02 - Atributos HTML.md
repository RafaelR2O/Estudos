Atributos HTML
- Todos os elemntos HTML podem ter atributos
- Os atributos fornecem informações acionais sobre os elemntos.
- Os atributos são sempre especificados na tag inicial.
- Os atributos geralmente vêm em pares de nome/valor como: name="value"

-----------------------------------------------------------------------------------------------------------

Atributo href
A tag define um hiperlink. O atributo especifica a URL da página.
exemplo: <a href="https://www.w3schools.com">Visite w3schools</a>

-----------------------------------------------------------------------------------------------------------

Atributo src
A tag é usada para incorporar uma <img> src em uma página html. 
O atributo especifica o caminho para a imagem a ser exibida.
Exemplo: <img src="img_girl.jpg">

Há 02 maneiras de especificar a URL no atributo src:
1 - URL abosuloto: Links para uma imagem externa hospedada em outro site. 
Exemplo: <img src="https://www.w3schools.com/images/img_girl.jpg">

Anotações: Imagens externas podem estar protegidas por direitos autorais. 
Se você não obtiver permissão para usá-las, poderá infringir a legislação de direitos autorais.
Além disso, imagens externas estão fora do seu controle e podem ser removidas ou alteradas inesperadamente.

2 - URL relativa: Links para uma imagem hospedada em o site. Aqui, o URL não inclui o nome de domínio.
Se o URL começar sem uma barra, será relativo à página atual.
Exemplo: <img src="img_girl.jpg">
Se o URL começar com uma barra, ele será relativo ao domínio. 
Exemplo: <img src="/images/img_girl.jpg">

-----------------------------------------------------------------------------------------------------------

Os atributos de largura e altura
A tag <img> também deve conter os atributos width e height, que especificam a largura e a altura da 
imagem (em pixels).
Exemplo: <img src="img_girl.jpg" width="500" height="600">

-----------------------------------------------------------------------------------------------------------

O atributo alt
O atributo alt da tag <img> especifica um texto alternativo para a imagem, caso ela não possa ser exibida.
Isso pode ocorrer devido a uma conexão lenta, um erro no caminho da imagem (src) ou quando o usuário utiliza um 
leitor de tela para acessibilidade.
exemplo: <img src="img_girl.jpg" alt="Girl with a jacket">

-----------------------------------------------------------------------------------------------------------

O Atributo de estilo

O atributo style é utilizado para aplicar estilos diretamente a um elemento HTML, como cor, fonte, tamanho, margens, entre outros.
<p style="color:red;">Este é um paragrafo vermelho</p>

-----------------------------------------------------------------------------------------------------------

O atributo lang

O atributo lang deve sempre ser incluído na tag <html> para declarar o idioma da página web. Isso ajuda os mecanismos de pesquisa e navegadores a entenderem o idioma do conteúdo, proporcionando uma melhor experiência para o usuário.

Exemplo de como especificar o inglês como idioma:
<html lang="en">
  <!-- Conteúdo da página -->
</html>

Os códigos de país também podem ser incluídos no atributo lang. Nesse caso, os dois primeiros caracteres definem o idioma, e os dois últimos caracteres especificam o país.

Exemplo: o código a seguir define o inglês como idioma e os Estados Unidos como país:
<html lang="en-US">
  <!-- Conteúdo da página -->
</html>

Você pode ver todos os códigos de idioma em <img src="https://www.w3schools.com/tags/ref_language_codes.asp" alt=" Referência de código de idioma HTML.">

-----------------------------------------------------------------------------------------------------------

O atributo title

O atributo title fornece informações adicionais sobre um elemento.
Quando o valor do atributo title é definido, ele é exibido como uma dica de ferramenta ao passar o mouse sobre o elemento.

Exemplo: 
<p title="Esta é uma dica de ferramenta">Este é um parágrafo.</p>

-----------------------------------------------------------------------------------------------------------

Recomendação: Sempre use atributos em minúsculas.  

Embora o padrão HTML permita que os nomes dos atributos sejam escritos em maiúsculas ou minúsculas (por exemplo, `title` ou `TÍTULO`), o W3C recomenda o uso de minúsculas para todos os atributos HTML. Além disso, para documentos mais rigorosos, como o XHTML, o uso de minúsculas é obrigatório.

Na W3Schools, seguimos a prática de sempre escrever os atributos em minúsculas para garantir consistência e conformidade com as melhores práticas.

-----------------------------------------------------------------------------------------------------------

Sugerimos: Sempre citar valores de atributo

O padrão HTML não requer aspas em torno de valores de atributo.
No entanto, o W3C recomenda aspas em HTML e exige aspas para tipos de documentos mais rigorosos, como XHTML.

Certo:
<a href="https://www.w3schools.com/html/" target="_blank">Visite nosso tutorial de HTML</a>

Incorreto:
<a href=https://www.w3schools.com/html/>Visite nosso tutorial de HTML</a>

Às vezes você tem que usar aspas. Este exemplo não será exibido title corretamente, porque contém um espaço:
<p title=Description of W3Schools>


-----------------------------------------------------------------------------------------------------------

Aspas simples ou duplas?
As aspas duplas são as mais comuns para definir valores de atributos em HTML, mas as aspas simples também podem ser utilizadas.

Em algumas situações, quando o valor do atributo contém aspas duplas, é necessário usar aspas simples para evitar conflitos:
<p title='John "ShotGun" Nelson'>

Da mesma forma, se o valor contiver aspas simples, você pode usar aspas duplas:
<p title="John 'ShotGun' Nelson">

-----------------------------------------------------------------------------------------------------------

### Resumo do Capítulo

- **Todos os elementos HTML podem ter atributos.**

- O atributo `href` especifica a URL da página para a qual o link irá direcionar. Exemplo: `<a href="URL">Link</a>`

- O atributo `src` define o caminho da imagem a ser exibida. Exemplo: `<img src="caminho/para/imagem.jpg">`

- Os atributos `width` e `height` fornecem informações de tamanho para imagens. Exemplo: `<img src="imagem.jpg" width="500" height="300">`

- O atributo `alt` fornece um texto alternativo para uma imagem, importante para acessibilidade. Exemplo: `<img src="imagem.jpg" alt="Descrição da imagem">`

- O atributo `style` é utilizado para adicionar estilos a um elemento, como cor, fonte, tamanho, entre outros. Exemplo: `<div style="color: red;">Texto estilizado</div>`

- O atributo `lang` da tag `<html>` declara o idioma da página da web. Exemplo: `<html lang="pt">`

- O atributo `title` fornece informações adicionais sobre um elemento, que são exibidas como uma dica de ferramenta. Exemplo: `<p title="Texto adicional">Parágrafo</p>`

<a href="https://www.w3schools.com/tags/ref_attributes.asp">Uma lista completa de todos os atributos para cada elemento HTML está listada em nosso: Referência de atributo HTML.</a>