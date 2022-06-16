Revelando o HTML

A base de trabalho de muitos Dev’s são por meio do HTML e muitas vezes esse quebra cabeça de letrinhas às vezes pouco intuitiva prejudica a compreensão e o processo de aprendizagem. 

Procurando esclarecer um pouco mais todo esse novo mundo que para muitos como eu é a porta de entrada para uma carreira como desenvolvedor. 

Vamos juntos nessa aventura e fique a vontade para contribuir com novos elementos ou com sua opinião nos comentários.


Conhecendo a estrutura HTML.
Anatomia do HTML
Categorias de conteúdo do elemento (HTML)
Elementos HTML
Conheça os atributos globais
Quais são os inputs permitidos no html
Agradecimentos e feeedback.


Conhecendo a estrutura HTML.

Primeiro ponto da nossa conversa, o famoso HTML não é uma linguagem de programação!!!!

HyperText Markup Language ou simplesmente HTML é uma linguagem de marcação, ou seja, ela se comunica com navegador de internet para assim você ver pode ver suas páginas. Ele é o responsável por estruturar as páginas web tanto simples como as páginas  complexas. 

Essa estruturação é feita a partir de uma série de elementos. A organização desses elementos é composta por três etapas fundamentais: tag de abertura; o conteúdo e tag de fechamento. 

A Tag de abertura indica o ínicio do elemento, onde começa a produzir o efeito, são envolvidos entre parênteses angulares (< >), já conteúdo é a informação que irá dentro do elemento e Tag de fechamento sinaliza a onde aquele elemento se encerra, sendo envolvimento pela sequência de um parêntese angular + barra + parentes angular (</ >). 

Exemplo: 

TAG DE ABERTURA       <body> 
CONTEÚDO	               	Aqui vai seu conteúdo podendo ser de infinitas formas.
TAG DE FECHAMENTO  </body>

Um elemento pode conter outros elementos no seu conteúdo, isso é chamado de aninhamento. Os elementos devem estar adequadamente aninhados, abrindo e fechando corretamente para que fique claro onde começar um elemento e onde termina. 



Exemplo: 
<body> 
	<p>Aqui vai seu conteúdo podendo ser de infinitas formas.</p>
</body>

Os elementos em HTML podem ser categorizados em duas importantes categorias, os elementos em bloco e os elementos inline. 

Elementos em blocos são geralmente estruturais na página, cada novo bloco irá aparecer em uma nova linha após outro elemento em bloco. Podemos considerar elementos em blocos por exemplo parágrafos <p>, listas <ul>, cabeçalho <head>. 
Importante: um elemento em bloco pode ser aninhado dentro de outro elemento em bloco, mas nunca dentro de um elemento inline. 

Já os blocos inline ou blocos em linhas, envolvem apenas parte do conteúdo, logo, um elemento inline não fará aparecer um nova linha no documento, exemplos de elementos inline são: ancora <a> e negrito <strong>.

Exemplo: 
<body> 
	<p>Aqui vai seu conteúdo podendo ser de <strong>infinitas formas</strong>.</p>
</body>

Cabe ressaltar que usamos a referência de estrutura acima para fins didático, já que  no HTML 5 as categorias em bloco e inline não são mais usadas devida a confusão muito comum que ocorria com os tios de caixas CSS com os mesmo nomes. 

Atualmente no HTML 5 existe as seguintes categorias de conteúdo de elementos: conteúdo de metadados; conteúdo do fluxo; conteúdo de seção; conteúdo do título; conteúdo de frase; conteúdo incorporado; conteúdo interativo; raízes de corte; elementos associados ao formulário; elementos listados; elementos que podem ser enviados; elementos reajustáveis; elementos herdados de capitalização automática; elementos rotuláveis; conteúdo palpável e elementos de suporte a script. 
Mas no HTML não existe somente os elementos descritos acima, que possuem um tag de abertura, conteúdo e tag de fechamento. Existe os elementos vazios, são compostos de uma única tag que é usada para inserir ou incorporar algo no documento. Por exemplo, à inclusão de imagens com img.

Exemplo: 
<body> 
	<p>Aqui vai seu conteúdo podendo ser de <strong>infinitas formas</strong>.</p>
	<img src=./imagens/estrutura-html.png>
</body>

Os elementos podem conter atributos que são informações extras, mas que não devem aparecer no conteúdo. Logo um atributo deve ter um espaço entre ele e o nome do elemento ou atributo anterior; o nome do atributo é seguido de sinal de igual e o valor do atributo deve estar com aspas de abertura e fechamento. 

Exemplo: 
<body> 
	<p class=“conteudo-geral”>Aqui vai seu conteúdo podendo ser de <strong>infinitas formas</strong>.</p>
	<img src=./imagens/estrutura-html.png>
</body>

Existe também atributos sem valores, são conhecidos como atributos booleanos normalmente irão tornar um elemento relevante ou não, podendo ser usado para ocultar elementos da página até que uma ação seja realizada. Por exemplo, podemos desativar uma caixa de texto inserida na página sem ter que retirar o elemento. 

 Exemplo: 
<body> 
	<p class=“conteudo-geral”>Aqui vai seu conteúdo podendo ser de <strong>infinitas formas</strong>.</p>
	<img src=./imagens/estrutura-html.png>
	<input type=”text” disabled>
</body>

Os valores dos atributos na sua grande maioria devem ser inseridos entre as aspas. Você pode usar as aspas simples ou duplas, isso é uma questão de estilo e não ira interferir no seu código, só lembre que as apas devem ser iguais na linha do código, a que começou tem que finalizar.

Até aqui você conheceu um pouco como é formado a estrutura do HTML, já entende que essa estrutura é composta de elementos, que existem diversos tipos de elementos com diversas finalidades.

Ao entender a importância dos elementos na estrutura HTML, você já pode vislumbrar como o HTML é importante para desenvolvimentos dos tipos mais diferentes de projetos e que um bom Dev tem que procurar entender o máximo possível sobre essa linguagem. 

#tecnologia #bootcamp #Dio #ContratoComCompromisso #GeraçãoTechUnimedBH

@Dio
@Unimed-BH

Anatomia do HTML

O desenvolvimento em HTML é realizado pela combinação de diversos elementos. Mas existe uma anatomia básica a ser seguida em um documento HTML, um mínimo necessário para que se possa desenvolver um bom documento .

Ao compreender a função desses elementos e como eles interagem com seu projeto, começa a ficar mais fácil pensar em HTML, ressalto que essa é uma estrutura mínima composta por seis elementos: 


<!DOCTYPE html>
<html>
	<head>
		<meta charset=”utf-8”>
		<title> Anatomia HTML</title>
	</head>
	<body>
		<p> Conteúdo do documento</p>
	</body>
</html>

O primeiro elemento no código é o doctype <!DOCTYPE html>  esse elemento não é uma tag do HTML e sim uma declaração para informar ao navegador qual é a versão do HTML utilizado no arquivo. 

Antes da versão 5 do HTML eram feitos declarações extensas do Doctype, atualmente essa declaração não é mais obrigatória, mas a presença dela garante que o navegador se comporte de maneira mais adequada e precisa. Logo seu uso é essencial em qualquer documento ou melhor é sim obrigatório em qualquer documento que valorize as boas práticas, o perfeito funcionamento e a segurança do documento. 

O segundo elemento é o html <html></html>, chamado de elemento raiz de um HTML documento ele vai envolver todo conteúdo. Ele é responsável por iniciar e finalizar o documento. 

O head <head></head> é o cabeçalho do documento, atua com todo conteúdo que não é visível ao usuário. Vai apresentar a descrição da página e as palavras-chave que vai aparecer nos resultados das buscas, como também o head vai conter metadados sobre o documento, como título e links para scripts e folhas de estilos. 

O elemento inline <meta charset=utf-8> vai ficar localizado dentro do head e será responsável pela codificação dos caracteres que o documento irá usar. O UTF-8 inclui a maioria dos caracteres das línguas humanas escritas, é isso mesmo das línguas! 
Com isso esse meta charset consegue interpretar com qualquer conteúdo textual que estiver no documento. 

o título <title></title> é outro elemento que fica dentro do head do documento, ele será responsável pela nomeação do documento, esse nome irá aparecer na guia do navegador e será usado também quando a página for salva nos favoritos do navegador. 

E por último, esse elemento é o responsável por todo conteúdo que irá no seu documento ele é corpo de todo HTML <body></body>, ele é responsável por todo texto, imagens, áudios e vídeos e qualquer outra coisa em seu documento. Só vai existir apenas um documento <body> em todo documento. 

Uma coisa importante que você deve ter em mente ao escrever seu código, é que os espaços em branco no HTML serão reduzidos em único espaço quando o código é renderizado. 

Mas lembre-se ao usar os espaços você melhorar a legibilidade, logo criar um padrão de formatação é importante principalmente quando essa formatação é composta por boas práticas. 

Você já deve ter reparado que os caracteres <, >, “,” e o & fazem parte da sintaxe do HTML, mas se você precisar incluí-los no texto terá que usar a equivalência chamada de referência de caractere. Essa referência de caractere equivalente é iniciada com & (e comercial) e finalizada com um ponto e vírgula (;). 

Logo: 
< = &lt;
> = &gt;
“ = &quot;
‘ = &apos; 
& = &amp;
Outra coisa que ajuda na formatação do seu documento e na compreensão é o uso de comentários ao longo do código, principalmente nos trabalhos colaborativos e/ou em códigos que você já trabalhou a muito tempo. 

Para poder usar os comentários no HTML você deverá agrupá-los por meio dos marcadores especiais <!-- -->. 

Os elementos apresentados neste texto são considerados o básico para um documento HTML, mas lembre-se que existem diversos outros elementos que irão tornar seu código funcional e atrativo. 

Esse é apenas o início de uma longa caminhada. 

 
Categorias de conteúdo do elemento (HTML)

A ideia desse texto é apresentar as categorias presentes no HTML e qual seria sua utilização e os principais elementos de cada categoria. 

Conteúdo de metadados permite configurar a apresentação ou comportamento do conteúdo do documento, estabelecendo relação com outros documentos. Elementos: <base>, <command>, <link>, <meta>, <noscript>, <script>, <style> e <title>.

Conteúdo do fluxo está relacionado diretamente com elementos usados no corpo do documento. Elementos: <a>, <abbr>, <address>, <article>, <aside>, <audio>, <b>,<bdo>, <bdi>, <blockquote>, <br>, <button>, <canvas>, <cite>, <code>, <command>, <data>, <datalist>, <del>, <details>, <dfn>, <div>, <dl>, <em>, <embed>, <fieldset>, <figure>, <footer>, <form>, <h1> , <h2> , <h3> , <h4> , <h5> , <h6> , <header>, <hgroup>, <hr>, <i>, <iframe>, <img>, <input>, <ins>, <kbd> , <keygen> , <label>, <main>, <map>, <mark>, <math>, <menu> , <meter>, <nav>, <noscript>, <object> , <ol>, <output>, <p>, <pre>, <progress>, <q>, <ruby>, <s>, <samp> , <script>, <section>, <select>, <small> , <span>, <strong>, <sub>, <sup>, <svg>, <table>, <template>, <textarea>, <time>, <ul>, <var>, <video>, <wbr> e Text.

Conteúdo de seção pode ser usado dentro de elementos como <header>, <footer> e no conteúdo do cabeçalho. Elementos: <article>, <aside>, <nav> e <section>.

Conteúdo do título define o cabeçalho de uma seção. Elementos:  <h1>, <h2>, <h3>, <h4>, <h5>, <h6>  e <hgroup>.

Conteúdo de frase (fraseado) está relacionado ao texto e a sua marcação, conjunto de frases compõem parágrafos. Elementos:<abbr>, <audio>, <b>, <bdo>, <br>, <button>, <canvas>, <cite>, <code>, <command>, <datalist>, <dfn>, <em>, <embed>, <i>, <iframe>, <img>, <input>, <kbd>, <keygen>, <label>, <mark>, <math>, <meter>, <noscript>, <object>, <output>, <progress>, <q>, <ruby>, <samp>, <script>, <select>, <small>, <span>, <strong>, <sub>, <sup>, <svg>, <textarea>, <time>, <var>, <video>, <wbr> e texto simples (não consistindo somente de caracteres de espaço em branco). 

Conteúdo incorporado permite importar outros recursos para o documento ou inserir conteúdo de uma outra linguagem de marcação. Elementos: <audio>, <canvas>, <embed>, <iframe>, <img>, <math>, <object>, <svg> e <video>.

Conteúdo interativo está destinado à interação com usuário. Elementos:<a> (se o href estiver presente), <audio> (se o controls estiver presente), <button>, <details>,  <embed>, <iframe>, <img>(se o usemap estiver presente), <input>(se o type não estiver no estado Oculto), <label>, <select>, <textarea>, <video>(se o controls estiver presente).  

Raízes de Corte possuem suas próprias características não está associado diretamente ao elemento mãe. Elementos: <blockquote>, <body>, <details>, <dialog>, <fieldset>, <figure>, <td>.

Elementos associados ao formulário estão relacionados a um formulário. Elementos:  <button>, <fieldset>, <input>, <object>, <output>, <select>, <textarea>, <img>, elementos personalizados associados a formulários.

Elementos listados está relacionado a um form de conteúdo ao qual possui um proprietário definido (form.elements e fieldset.elements). Elementos: <button>, <fieldset>, <input>, <object>, <output>, <select>, <textarea>, elementos personalizados associados a formulários.

Elementos que podem ser enviados são elementos que podem ser usados para construir a lista de entrada quando um form é submetido. Elementos: <button>, <input>, <select>, <textarea>, elementos personalizados associados a formulários.

Elementos reajustáveis está relacionado a elementos que podem ser afetados quando um form é redefinido. Elementos: <input>, <output>, <select>, <textarea>, elementos personalizados associados a formulários.

Elementos herdados de capitalização automática esses elementos herdam o autocapitalize do proprietário do formulário. Elementos: <button>, <fieldset>, <input>, <output>, <select>, <textarea>. 

Elementos rotuláveis são elementos que podem ser associados a um label. Elemento: <button>, <input>(se o type não estiver no estado Oculto ), <meter>, <output>, <progress>, <select>, <textarea>, elementos personalizados associados a formulários.

Conteúdo palpável em regra geral está associado a conteúdo de fluxos ou fraseado e que não tenham o hiddean especificado. Elementos: <a>, <abbr>, <address>, <article>, <aside>, <audio> (se o controls estiver presente), <b>, <bdi>, <bdo>, <blockquote>, <button>, <canvas>, <cite>, <code>, <data>, <details>, <dfn>, <div>, <dl> (se os filhos do elemento incluírem pelo menos um grupo nome-valor), <em>, <embed>, <fieldset>, <figure>, <footer>, <form>, <h1>, <h2>, <h3>, <h4>, <h5>, <h6>, <header>, <hgroup>, <i>, <iframe>, <img>, <input> (se o type não estiver no estado Oculto), <ins>, <kbd>, <label>, <main>, <map>, <mark> <menu> (se os filhos do elemento incluirem pelo menos um li), <meter>, <nav>, <object>, <ol>(se os filhos do elemento incluirem pelo menos um li), <output>, <p>, <pre>, <progress>, <q>, <ruby>, <s>, <samp>, <section>, <select>, <small>, <span>, <strong>, <sub>, <sup>, <table>, <textarea>, <time>, <u>, <ul> (se os filhos do elemento incluirem pelo menos um li), <var>, <video>, elementos personalizados autônomos, texto que não é espaço em branco entre elementos.

Elementos de suporte a script são aqueles que não são renderizados, mas fornecem funcionalidade para o usuário. Elementos:  <script>, <template> 

Elementos HTML

Elementos são a base do documento HTML, eles iniciam e finalizam o documento com elemento raiz <html>. 

Mas além do elemento raiz, temos diversos elementos para as mais variadas situações, esses elementos irão permitir criar uma estrutura cada vez mais complexa para seu código. 

Após incluído o elemento raiz, os próximos elementos estão relacionados aos metadados do documento.

<base> esse elemento será usado apenas uma vez no documento e será responsável por especificar o endereço (URL) de todos os endereços contidos dentro do documento. 

Esse elemento além de incluir atributos globais está diretamente relacionado aos atributos href e target.

<head> vai conter título, links para scripts e folha de estilos podem ser adicionados os atributos globais.

<link> esse elemento está relacionado a um recurso externo, normalmente são usados para vincular as folhas de estilos. Os link poderão conter os seguintes atributos: as, charset, crossorigin, disabled, href, hreflang, media, methods, rel, rev, sizes, target, type.

<meta> vai definir as informações referente aos metadados que não podem ser definidos por outros elementos (<base>, <link>, <script>, <style> ou <title>). Esse elemento vai incluir os atributos globais, além: charset, content, http-equiv, name, creator, googlebot, publish, robots, slurp, viewport, scheme. 

<style> vai conter as informações sobre o estilo do documento, normalmente no CSS. Pode conter os atributos type, media, scoped, title, disabled e os atributos globais. 

<title> defini o título do documento que será mostrado nos bucadores e na aba da página. Deve conter apenas texto e será sempre usado dentro da <head> e irá incluir somente os atributos globais.

Até aqui vimos os elementos relacionados ao metadados, mas agora iremos conhecer os elementos que permitem fazer a separação de conteúdo. Os elementos que separam os conteúdos permitem fazer uma organização lógica do documento. 

<adress> vai fornecer informações de contato, podendo ser as informações necessárias, como endereço físico, RTL, email, telefone, mídia social, coordenadas geográficas e o que mais for preciso referente ao contato. Lembrar sempre de incluir o nome da pessoa ou do grupo/organização para qual são referentes às informações de contato. Esse elemento inclui somente os atributos globais. 

<article> é um elemento que representa uma forma de conteúdo independente. São aplicados os atributos globais.  

<aside> é um elemento que vai está relacionado ao conteúdo do seu entorno. São aplicados os atributos globais.
<footer> vai representar um rodapé para o conteúdo de seção do seu parente mais próximo. Normalmente vai conter informações como direitos autorais, links para documentos relacionados ou informações sobre o autor. São aplicados os atributos globais.

<header> é o cabeçalho que irá conter suporte introdutório ou navegacional, além de outros elementos como um logo, seções de cabeçalho, formulário de pesquisa e muitos outros elementos. Os atributos globais podem ser atribuídos a esse elemento.  
<h1> a <h6> está relacionado a seis níveis de título de seção. <h1> é o nível de seção mais alto e deve ser usado apenas uma vez e o <h6> é o mais baixo. 

<main> vai definir o conteúdo principal dentro do <body>, dessa forma esse deve ser o único na página. Não pode ser filho dos elementos <articles>, <aside>, <footer>, <header> ou <nav>. São aplicados os atributos globais.

<nav> é um elemento de navegação que irá pontar para outras páginas ou para outras áreas do documento, seria uma seção com links de navegação. O documento poderá ter vários elementos <nav>, podendo ser para navegação em site e para navegação dentro da página, cabe ressaltar que nem todos os links devem estar dentro da <nav>. São aplicados os atributos globais.

<section> vai representar uma seção generalista no documento, normalmente possui um título e os atributos aplicados são os globais.

Quando necessitamos organizar os blocos e seções identificando o propósito ou estrutura do conteúdo colocados dentro da tag <body>, usamos os elementos de conteúdo textual. 

<blockquote> informa que o texto é referente a uma longa citação, já a fonte da citação poderá ser registrada por meio do atributo cite, esse elemento também aceita os atributos globais. 

<dd> vai fornecer mais detalhes ou uma definição mais completa dos termos de uma lista de descrições. Além dos atributos globais, esse elemento poderá ter o atributo nowrap. 

<div> é um elemento de divisão que pode agrupar elementos para fins de estilos (usando class ou id) ou por compartilhar valores de atributos. Deve ser usado somente quando não tem outro elemento semântico. São aplicados os atributos globais.

<dl> vai englobar um lista de pares de termos e descrições que é usualmente aplicado em glossário ou para exibir metadados. Pode ser aplicado os atributos globais ou o atributo compact que irá funcionar apenas no Internet Explorer. 

<dt> quando esse elemento é filho de um <dl> é capaz de identificar um termo na lista de definição. Podem ser aplicados os atributos globais. 

<figcaption> permite inserir uma legenda a uma figura ou ilustração, deve estar aninhada ao elemento <figure>. Podem ser aplicados os atributos globais. 

<hr> é um elemento inline que irá representar um quebra temática (por meio de uma linha horizontal) entre parágrafos. Além dos atributos globais podem ser adicionados o color. Para que possa realizar alteração é necessário usar folhas de estilos em cascata. 

<li> esse elemento irá criar uma lista, mas deve estar contido a um a elemento pai <ol>, <ul> ou <menu>. Podem ter os atributos value, type e os globais. 

<menu> é um elemento que permite criar uma lista não ordenada representados por elementos que podem ser links ou comandos que podem ser ativados pelos usuários. Podem ser aplicados os atributos globais.

<ol> representa um lista de itens ordenados que podem possuir os atributos compact, reversed, start, type e as globais. 

<p> representa um parágrafo que podem ter atributos globais. 

<pre> essa tag permite representar texto pré-formatado, logo os texto serão exibidos em uma fonte não proporcional e os espaços em branco serão mantidos como foi digitado. Podem ser usados atributos cols, width e wrap. 

<ul>  representa uma lista de itens sem ordem rígida podem ser incluídos os atributos compact, type e global. 

Os elementos textuais inline ajudam a definir significado, estrutura ou estilo de uma palavra, linha ou qualquer outro tipo de texto. 

<a> conhecido como elemento âncora que possui o atributo href que permite uma ligação de páginas web, arquivos, emails e outros. Além do atributo href podem ser incluídos os atributos download, hreflang, ping, referrerpolicy, rel, target e type. 

<abbr> representa uma abreviação e opcionalmente fornece uma descrição completa para ela. Usar o atributo title para definir a descrição completa da abreviação. 

<b> representa um intervalo de texto estilísticamente diferente do texto normal sem emitir grau de importância. Normalmente é usado para destacar palavras-chave, nome de produtos. Podem ser aplicados os atributos globais.

<bdi> isola um trecho  de texto que pode ser formatado em uma direção diferente de outro texto fora dela. Somente o atributo dir não é herdado, todos outros atributos globais podem ser incluídos. 

<bdo> muda a direção do texto. Podem ser usados o atributo dir e os atributos globais.

<br> permite fazer um quebra de linha em um texto. Podem ser incluídos atributos globais. 

<cite> trata-se de uma representação de uma referência a um trabalho acadêmico, científico ou artístico. Deve ser incluído o título do trabalho ou URL. Quando for referenciar uma fonte online deve ser usado o <cite> aninhado a um elemento <bloclquote> ou <q>. 

<data> vincula um determinado conteúdo a uma tradução legível por máquina. Se o conteúdo estiver relacionado à hora ou à data, o <time> deve ser usado. Podem ser incluídos os atributos globais. 

<dfn> marca o termo que será definido. O atributo title deve ser considerado. 

<em> marca o texto com ênfase. Podem ser incluídos os atributos globais. 

<i> vai representar parte do texto que será destacada do restante do texto, como termos técnicos ou expressões em outro idiomas por exemplo. Podem ser incluídos os atributos globais.

<kdb> esse elemento representa a entrada textual de um teclado ou entrada de voz. Podem ser incluídos os atributos globais.

<mark> é usado para destacar parte de um texto (como um marca texto). Podem ser incluídos os atributos globais.

<q> Indica que o texto é uma pequena citação, pode ser incluído o atributo cite para designar a fonte. 

<ruby> permite mostrar a pronùncia de caracteres do Leste Asiático. Podem ser incluídos os atributos globais.

<s> vai formatar com uma linha cortando o texto, normalmente usado em texto não relevantes ou que não estão corretos.

<samp> defina algum texto como saída de amostra de um programa de computador em um documento.
<small> esse elemento por padrão vai renderizar o texto em um tamanho de fonte menor, normalmente usado em direitos autorais e texto legal. 

<span> usado para agrupar elementos para fins de estilo (class ou id) ou para compartilhar valores de atributos como lang. Seu uso só é recomendado quando nenhum outro elemento semântico for apropriado. Ele é um elemento de linha diferente do <div> que um elemento de bloco. 

<strong> mostra o texto em negrito. 

<sub> mostra o texto subscrito. 

<sup> mostra o texto sobrescrito. 

<time> representa o tempo tanto no formato de 24 horas ou como um data precisa. Podem ser incluídos os atributos datetime e pubdate.

<u>  esse elemento sublinha o texto indicando uma anotação não textual. 

<var> representa uma variável em uma expressão matemática ou um contexto de programação. 

Os elementos abaixo estão relacionados aos recursos multimídias, podendo ser eles de imagens, áudio e vídeo. 

<area> esse elemento deve ser usado dentro de um <map>, vai definir uma região hot-spot em uma imagem. Podem ser incluídos os atributos alt, coords, download, href, hreflang, media, rel, shape, target e type.

<audio> é utilizado para embutir conteúdo de som em documento. Pode ser incorporados os atributos: autplay, buffered, controls, loop, muted, played, preload, src. 

<img> vai permitir incluir imagem no documento, os formatos aceitos serão jpeg, gif, png, svg, bmp. Os atributos associados são: alt, border, crossorigin, anonymous, use-credentials, heigth, ismap, src, srcset, width, usemap. 

<map> é usado com elemento <área> para definir uma área clicável no link. Pode ter o atributo name. 

<track> é um elemento filho dos elementos <audio> e <video> que permite especificar faixas de texto, por exemplo uma legenda automática. Podem ser incluídos os atributos default, kind, label, src e srclang.

<video> é utilizado para incorporar conteúdo de vídeo no documento. Pode ser incluído os atributos autoplay, autobuffer, buffered, controls, height, loop, muted, played, preload, poster, src e  width.

Além dos conteúdos multimídia apresentados até aqui, existem outros conteúdos que irão permitir uma série de variedade no documento. Conheça agora os elementos do conteúdo integrado. 

<embed> permite incorporar conteúdo externo em ponto do documento, esse conteúdo será fornecido por um aplicativo externo ou outra fonte de conteúdo interativo. Podem ser incluídos os atributos height, src, type e width.

<iframe> incorpora outra página html no documento. Podem ser incluídos os atributos allowfullscreen, height, mozallowfullscreen, webitallowfullscreen, mozapp, mozbrowser, name, remote, sandbox, seamless, src, srcdoc e width.  

<object> esse elemento vai representar um recurso externo. Podem incluir os atributos achive, border, classid, codebase, codetype, data, declare, form, height, name, standby, type e width. 

<picture> vai atuar como um container que irá especificar múltiplos elementos <source> para um elemento específico <img> contido nele. Podem ser usados os atributos media e type. 
<portal> esse elemento é semelhante ao iframe, que permite incorporar contexto de navegação no documento, mas a diferença está na limitação desse elemento que permite uma visualização do conteúdo sem interação. Os atributos referrerpolicy e src podem ser incorporados. 

<source> serve para especificar diversos recursos de mídia <picture>, <audio> ou <video>. Podem ser incluídos os atributos src, type, media.

Os elementos Scripting permitem a criação de conteúdos dinâmicos e aplicações Web. 

<canvas> pode ser utilizado para desenhar gráficos, composição de fotos e animações utilizando scripts. Atributos que podem ser associados são width, height. 

<noscript> define uma seção que será inserida se o script estiver desativado ou não for suportado.

<script> é usado para incluir ou referenciar um script executável. podem ser associados os atributos: async, crossorigin, defer, integrity, nomodule, src, text, type. 

Existe elementos que permitem demarcar edições, irão indicar que partes específicas de um texto foram alteradas. 

<del> representa um parte do texto que foi excluída de um documento. Pode ser associados aos atributos cite e datetime. 

<ins> vai representar um intervalo de texto que foi adicionado ao documento.Pode ser associados aos atributos cite e datetime. 

Os conteúdos tabulados permitem a criação e manipulação de dados em tabelas no documento HTML.

<caption> representa o título de uma tabela. 

<col> normalmente encontrado dentro do elemento <colgroup> vai definir a coluna na tabela. Podem ser associados ao atributos bgcolor, span.

<colgroup> define um grupo de colunas dentro de uma tabela. Podem ser incluídos os atributos span, align, col, bgcolor, char, charoff, valign. 

<table> representa dados em duas dimensões ou mais. Os atributos que podem ser associados são: align, bgcolor, border, cellpadding, cellspacing, frame, rules, summary e width. 

<tbody> representa o elemento do corpo da tabela, vai ter um conjunto de linhas da tabela.  Os atributos que podem ser associados são: align, bgcolor, char, charoff, valign. 

<td> define um célula de uma tabela que contém dados. Podem ser associados aos atributos: colspan, headers, rowspan. 

<tfoot> define um conjunto de linhas as quais farão parte do rodapé de uma tabela. Podem ser incluídos os atributos align, bgcolor. 

<th> define um célula cabeçalho do grupo de células da tabela. Podem ser associados os atributos abbr, colspan, headers, rowspan, scope.

<thead> define um conjunto de linhas definindo o cabeçalho das colunas da tabela.

<tr> define uma linha de células em uma tabela. 

O conteúdo que permite a elaboração de formulários são representado por vários elementos que juntos criam formulários que podem ser preenchidos e enviado por website ou aplicativos. 

<button> representa um botão clicável, pode ser associado aos atributos: autofocus, autocomplete, disabled, form, formaction, formenctype, formmethod, formnovalidate, formtarget, name, type, value. 
<datalist> contém um conjunto de elementos <option> que representam as opções possíveis para o valor de outros controles. 

<fieldset> é usado para agrupar elementos, assim como labels dentro de um formulário web. Os atributos que podem ser associados são: disabled, form, name.  

<input> é usado para criar controles interativos para formulários baseados na web para receber dados do usuário. Está relacionado diretamente com atributo type, aceept, mozactionhint, autocapitalize, autocomplete, autocorrect, autofocus, autosave, checked, disabled, form, formaction, formmethod, formnovalidate, formtarget, height, incremental, inputmode, list, max, maxlength, min, minlength, multiple, name, pattern, placeholder, readonly, required, selectiondirction, size, spellcheck, src, step, value, width. 

<label> é um elemento que representa uma legenda para um item em uma interface de usuário. Pode ser incluída o atributo accesskey, for e form. 

<legend> representa um rótulo para o conteúdo <fieldset>.  

<meter> representa um valor escalar dentro de um intervalo conhecido ou um valor fracionário. Os atributos que podem ser incluídos nesse elemento são: value, min, max, low, high, optimun, form.

<output>  O elemento de saída no qual um site ou aplicativo pode injetar os resultado de um cálculo ou o resultado de uma ação do usuário. Os atributos que podem ser colacionados são: for, form, name. 

<progresso> é usado para visualizar o progresso de uma tarefa e pode está relacionado com os atributos: max, value. 

<select> esse elemento representa um controle que apresenta um menu de opções. As opções de menu podem ser representadas pelo <option> e podem ser agrupadas pelo <optgroup>. 

<textarea> vai representar um controle de edição para uma caixa de texto, útil quando você quer permitir ao usuário informar um texto extenso em formato livre. 

Os elementos interativos auxiliam na criação de objetos interativos de interface para usuários. 

<details> usado como uma ferramenta de onde o usuário irá obter informações adicionais e pode ser relacionado ao atributo open. 

<dialog> representa uma caixa de diálogo ou outro componente interativo. saiba que o atributo tabindex não deve ser usado no <dialog>, mas o atributo open pode ser relacionado. 
Conheça os atributos globais 

A primeira coisa que se deve saber sobre os atributos globais que eles são comuns a todos os elementos, mas alguns elementos podem não ter os efeitos esperados. 

accesskey - fornece um dica para gerar um atalho de teclado para o elemento atual. 
autocapitalize - permite controlar a entrada de texto inserido ou editado pelo usuário. 
autofocus - Indica que um elemento deve ser focado no carregamento da página. 
class - separa uma lista por espaços das classes do elemento, logo as classes permitem que o CSS e o JavaScript  acessem elementos específicos por meio de seletores ou funções. 
contenteditable - Este atributo vai indicar se o elemento deve ser editado pelo usuário. 
contextmenu - pode ser usado como menu contextual .
data-* - é um atributo personalizado que permite que informações sejam trocadas e que pode ser usada por scripts. 
dir - indica a direção do texto do elemento. 
draggale - indica se o elemento pode ser arrastado. 
enterkeyhint - indica qual rótulo ou ícone será apresentado em teclados virtuais para tecla Enter. 
hidden - indica a relevância do elemento. 
id - é um identificador único que deve conter apenas um em todo documento. 
imputmode - fornece informações sobre a configuração de teclado virtual a ser usado ao editar este elemento ou seu conteúdo. 
is - permite especificar o padrão que o elemento deve se comportar. 
itemid - o identificador exclusivo de um item. 
itemprop - usado para adicionar propriedade a um item. 
itemref - fornece uma lista de ids de elementos com propriedades adicionais em outras partes do documento. 
itemscope - funciona em conjunto com itemtype para especificar que o HTML contido em um bloco é sobre um item específico. 
itemtype - vai especificar a URL que será usada na estrutura de dados. 
lang - ajuda a definir o idioma de um elemento. 
nonce - criptografa o elemento informando se ele pode ser usado. 
part - cria uma lisa por espaços dos nomes das partes do elemento. 
slot - atribui um slot a um elemento. 
spellcheck - define se o elemento pode ser verificado quanto a erros de ortografia. 
style - Contém declarações de estilo CSS a serem aplicadas ao elemento.
tabindex - se o elemento pode receber o foco de entrada.  
title - Contém um texto que representa informações consultivas. 
translate - usado para especificar os valores de atributo de um elemento que pode ser traduzido. 
Quais são os inputs permitidos no html 

Os <input> são usados para criar controles interativos para formulários baseados na web para aceitar dados do usuário.

<input type = “button”> renderiza botões simples que podem ser programados e controlados. 
<input type = “checkbox”>  renderiza caixas que são marcadas quando ativadas.  
<input type = “color”>  insere cor em campo de texto. 
<input type = “data”> insere uma caixa de texto que valida uma data selecionada. 
<input type = “datetime-local”> permite ter um campo para  incluir uma data e hora. 
<input type = “email”> criar um campo que pode ser adicionado um email. 
<input type = “file”> permite escolher um ou mais arquivos do dispositivo. 
<input type = “hidden”> são dados ocultos que são completamente invisíveis e não podem ser modificados pelo usuário. 
<input type = “image”> são usados para criar botões de envio que assumem a forma de uma imagem em vez de texto. 
<input type = “month”> são criadas caixas que permitem ao usuário inserir um mês e ano. 
<input type = “number”> permite que o usuário insira números. 
<input type =”password” > permite ao usuário inserir uma senha com segurança. 
<input type = “radio”> São um conjunto de botão que pode ser criado, mas apenas um pode ser selecionado ao mesmo tempo, normalmente são renderizados com pequenos círculos. 
<imput type = “range”> normalmente é representado por um controle deslizante. Permite especificar um valor entre um número mínimo e um máximo, mas a entrada precisa não é importante. 
<input type =”reset”> permite redefinir todas as entradas de um formulário. 
<input type = “search”> inclui um botão de consulta de pesquisa. 
<input type = “submit”> são os famosos botões de enviar.  
<input type = “tel”> permite ao usuário informar números de telefone. 
<input type = “text” > cria caixa de texto que o usuário pode utilizar. 
<input type = “time”> criar campo que usuário pode inserir facilmente uma hora. 
<input type = “url”> permite ao usuário inserir um endereço URL. 
<input type = “week”> cria um campo que permite ao usuário inserir um ano e a semana (podendo ser de 1 a 52 ou 53). 

Agradecimentos e feeedback. 

As informações contidas até aqui são apenas o início de uma longa jornada que irá permitir a todos nós nos desenvolver como Dev’s.  Acredito que essa base apresentada nesse documento já será de grande valia não apenas para compreensão de alguns termos, mas também como uma valiosa fonte de consulta. 
Agradeço a você que leu esse material até aqui e espero ter contribuído com a sua jornada.
Não esqueça de deixar nos comentários a sua percepção sobre essa obra, essa pequena atitude nos motivar a continuar produzindo mais textos como esse, além de ser um fonte valiosa de feedback para saber os pontos que posso melhorar em materiais futuros. 



