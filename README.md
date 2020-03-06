# aula06_03_2020
## atividade de pesquisa 
### conceito de css
CSS é a sigla para Cascading Style Sheet que, em português, significa Folha de Estilo em Cascatas. É uma linguagem de programação que serve para compor o estilo visual das páginas na internet. 
CSS é uma linguagem de programação usada para estilizar elementos de uma página desenvolvida com uma linguagem de marcação, como o HTML.  O que ela faz é separar a parte estrutural escrita, ou seja, o conteúdo, da parte visual, ou seja, o design gráfico dessa mesma página.
A expressão cascata da nomenclatura indica que é possível usar mais de um arquivo CSS ao mesmo tempo para criar o estilo visual de um site. É o CSS que estipula o visual dele, incluindo elementos como tamanho da fonte, imagens de fundo e estilo de cores.
A linguagem CSS tem muitas possibilidades de formatação. Ela permite mexer, editar, remover, alinhar ou trabalhar no espaçamento dos elementos de uma página de forma prática e fácil.
Isso garante mais flexibilidade e agilidade não apenas para os elementos textuais e gráficos que constituem essa mesmo página, mas também para profissionais que trabalham com essa linguagem de estilos.
É por isso que desenvolvedores, sejam iniciantes ou experientes, costumam usá-la nos seus projetos online. Sites, blogs e ecommerce frequentemente são feitas com folha de estilo CSS, além de outras linguagens.  

### aplicações do css
Animações
São elementos que ajudam sites a receber mais atenção dos visitantes do que simples páginas estáticas. Neste caso, é exigido um conhecimento mais aprofundado do programador para executar a estrutura certa de uma animação, pois ela é mais complexa do que apenas configurar elementos visuais simples.    
Efeitos Visuais
O estilo cascata do CSS se encaixa com efeitos de estilo que se sobrepõem uns aos outros. Isso cria um atrativo visual extra para quem está acessando tal página na internet com essas funcionalidades. Um dos efeitos mais apropriados para este aspecto é o Parallax, que confere um efeito de profundidade mais realista ao layout.
Sites Dinâmicos
Como a linguagem de estilos CSS é versátil e fácil de implementar, desenvolvedores são capazes de criar sites dinâmicos usando efeitos combinados. Podem ser animações, passagens de transição, páginas responsivas, linhas e fontes personalizadas e mudanças de tonalidades quando o cursor do mouse passa sobre algum objeto.
Landings Pages
São as páginas de destino usadas para capturar informações dos visitantes ou oferecer vendas de produtos e serviços. Estas páginas precisam ser visualmente atrativas para conquistar a atenção de quem as acessa. Além disso, geralmente contam com formulários de inscrição e elementos gráficos destacados. Tudo feito com CSS.

### selotores css
Permite que selecionemos qualquer elemento na página.

Seletor de tipo: Com este seletor, selecionamos todas as tags de um mesmo tipo. Por exemplo, se digitamos a estaremos selecionando todas as tags a (links) da página e poderemos aplicar estilos a elas. Útil para estilos gerais, mas para maior especificidade utilizamos outros seletores.
Seletor descendente: com este seletor, podemos escolher um ou mais elementos que estão dentro de outro, ou seja, que são descendentes do elemento principal. Exemplo: p strong. Com isso, selecionamos apenas tags strong que estão dentro de parágrafos. Podemos selecionar com ainda mais especificidade, escrevendo mais elementos, como: div p strong a. Neste exemplo, selecionamos links que estão dentro de tags strong que estão dentro de parágrafos que estão dentro de tags div.
Seletor de classe: seleciona elementos com uma classe específica aplicada. Exemplo: .destaque seleciona todos os elementos com a classe "destaque".
Seletor de id: seleciona o elemento com a id especificada. Exemplo: #cabecalho irá selecionar o elemento com a id "cabecalho". Cada id é única e não pode ser repetida no mesmo documento.

Podemos também combinar os seletores que aprendemos acima, para conseguir diferentes elementos e partes mais específicas de nossos sites. Alguns exemplos:

p.destaque seleciona apenas os parágrafos que possuem a classe "destaque".
div#cabecalho h1 seleciona tags h1 que estejam dentro da div com a id "cabecalho".
#conteudo ul li a seleciona links (tag a) dentro de itens de lista dentro de tags ul que estejam dentro de um elemento com a id "conteudo".
#conteudo p.destaque strong seleciona elementos strong dentro de parágrafos com a classe "destaque" que estejam dentro de um elemento com a id "conteudo".
.mensagem.destaque seleciona apenas elementos que tenham a classe "mensagem" e a classe "destaque".
Separando itens por vírgulas, como p.destaque, h1, a.saiba-mais seleciona todos os respectivos elementos para as regras. Muito útil para diminuir a repetição de regras no arquivo CSS.

### Diferença entre estilos CSS, Internos, Externos e Inline
Existem 3 maneiras para adicionar estilos CSS ao seu site: você pode usar CSS interno e incluir regras CSS na seção <head> do documento HTML, link para um arquivo .css externo que contém todas as regras CSS ou usar CSS em linha para aplicar regras para Elementos específicos.
  
CSS Interno
Código CSS interno é colocado na seção <head> de uma determinada página. As classes e IDs podem ser usados para se referir ao código CSS, mas eles só estão ativos nessa página específica. CSS estilos incorporados desta forma são baixados cada vez que a página carrega para que ele possa aumentar a velocidade de carregamento. No entanto, existem alguns casos quando a pagina de estilos interna é útil. Um exemplo seria enviar alguém um modelo de página – como tudo está em uma página, é muito mais fácil ver uma pré-visualização. O CSS interno é colocado entre tags <style></style>. 
 
<head>
<style type="text/css">
p {color:white; font-size: 10px;}
.center {display: block; margin: 0 auto;}
#button-go, #button-back {border: solid 1px black;}
</style>
</head>

CSS externo
Provavelmente a maneira mais conveniente de adicionar CSS ao seu site, é vinculá-lo a um arquivo .css externo. Dessa forma, quaisquer alterações feitas em um arquivo CSS externo serão refletidas em seu site globalmente. Uma referência a um arquivo CSS externo é colocada na seção <head> da página:
  
<head>
<link rel="stylesheet" type="text/css" href="style.css" />
</head>

CSS Inline
O CSS inline é usado para uma tag HTML específica. O atributo <style> é usado para formatar uma tag HTML específica. Usar CSS desta forma não é recomendado, pois cada tag HTML precisa ser denominada individualmente. Gerenciando seu site pode tornar-se muito difícil se você usar apenas CSS inline. No entanto, pode ser útil em algumas situações. Por exemplo, nos casos em que você não tem acesso a arquivos CSS ou precisa aplicar estilo para um único elemento. 
  
<!DOCTYPE html>
<html>
<body style="background-color:black;">

<h1 style="color:white;padding:30px;">Hostinger Tutorials</h1>
<p style="color:white;">Something usefull here.</p>

</body>
</html>

### framework's css mais usados 

bootstrap 
Um framework front-end para desenvolvimento web. Mais do que outros framework front-end, o Bootstrap tem se tornado ao longo dos anos uma das ferramentas mais importantes para a criação de websites. Isto porque seus padrões seguem os princípios de usabilidade e as tendências de design para interfaces.

Além disso, sua padronização permite que os sites tenham um melhor aspecto, sendo uma forma de criar páginas esteticamente agradáveis. E você sabe que quanto melhor o design de uma página, maior a taxa de satisfação dos usuários.

purecss
Pure é um framework muito simples, mantido pelo Yahoo! inc. que contém um conjunto componentes CSS responsivos que você pode utilizar me qualquer projeto. O arquivo .min do Pure possui apenas 4.5KB, muito menor que o arquivo do Bootstrap por exemplo, e possui link para servidores CDN. Esse framework é muito prático para resolver problemas.

foudantion
É um framework CSS construído com Sass, um pré-processador CSS poderoso, que nos permite desenvolver muito mais rápido nossas próprias fundações e nos disponibiliza novas ferramentas para personalizar e construirmos em cima dos estilos iniciais.

Com o Foundation podemos escrever e organizar os códigos CSS que podemos manter mais facilmente ao longo do tempo sem as dores de cabeça típicas, temos também plug-ins JavaScript que fazem interações úteis e mais fáceis de implementar em diferentes resoluções de tela.
