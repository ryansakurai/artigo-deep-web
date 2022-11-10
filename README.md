# Deep Web: além da superfície

## Resumo
Muito popular entre canais de curiosidade e teorias da conspiração no Youtube, Deep Web é um conceito cercado de mitos, desinformação e sensacionalismo. Visto isso, o objetivo deste artigo é desmistificar e explicar o que de fato é a Deep Web e o que a diferencia da “web normal”.

## Introdução
Apesar dos termos internet e web serem frequentemente utilizados intercambiavelmente, eles não são sinônimos. Por isso, antes de mais nada, é importante diferenciá-los.

A internet é uma rede que conecta computadores, servidores e outros aparelhos em escala global, além da infraestrutura por trás dessa rede. Sua criação data em meados da década de 1960 e ela possibilita o transporte de informações no mundo contemporâneo e tecnologias como a web.

Por sua vez, a web - também conhecida como World Wide Web (WWW) -  é um sistema de compartilhamento de informações através da internet. Ela é um conjunto de arquivos que podem ser visualizados através de um navegador, como o Google Chrome, o Mozilla Firefox, o defunto Internet Explorer e seu substituto Microsoft Edge.

![navegadores](https://github.com/ryansakurai/artigo-deep-web/blob/main/imagens/img_0.png)

*[Exemplos de navegadores](https://www.oficinadanet.com.br/internet/30735-10-navegadores-mais-usados-no-mundo)*

O compartilhamento de informações na web é feito através de HTML, uma linguagem de marcação de hipertexto que, por sua vez, funciona sob os princípios de hipertexto e hipermídia. Hipertexto define o conceito de texto não linear, ou seja, que possui link para outros textos, e hipermídia consiste na coexistência de texto, vídeos, imagens e outras formas de conteúdo na mesma página.

![hipertexto](https://github.com/ryansakurai/artigo-deep-web/blob/main/imagens/img_1.png)

*[Representação visual do conceito de hipertexto](https://en.wikipedia.org/wiki/Hypertext)*

Tendo isso em vista, a web possui 3 principais camadas: a Surface Web, a Deep Web e a Dark Web, que vão ser apresentadas a seguir.

## Surface Web
A primeira camada da web, a Surface Web, é a parte da web formada por páginas que podem ser encontradas e acessadas através de mecanismos de busca como Google e Bing. O que torna essas páginas disponíveis é a ação de algoritmos chamados web crawlers.

Web crawlers são os algoritmos dos mecanismos de busca responsáveis por fazer a indexação das páginas da web. Esses bots inspecionam seus códigos HTML procurando por dados sobre a página, as indexam e as classificam com base nesses dados. Dessa maneira, quando um usuário faz uma pesquisa no Google, ele encontra os resultados que o mecanismo julga serem mais relevantes.

![web crawler](https://github.com/ryansakurai/artigo-deep-web/blob/main/imagens/img_2.png)

*[Ilustração da indexação feita por mecanismos de busca](https://computersciencewiki.org/index.php/Web-indexing)*

## Deep Web
A segunda camada da web, a Deep Web, em oposição à Surface Web, é a parte da web composta por páginas que não podem ser acessadas através de mecanismos de busca, ou seja, que não foram indexadas. A maior parte dessas páginas utilizam as mesmas tecnologias da Surface Web e, apesar de dificuldades no cálculo de seu tamanho, a Deep Web compõe a esmagadora maioria da web.

Os motivos para a não indexação das páginas da Deep Web podem ser diversos: necessidade de autenticação ou pagamento, uso de outros protocolos que não sejam HTTP/HTTPS, conteúdo gerado dinamicamente, dificuldade em indexar mídia ou até falta de link entre uma página e outra. A indexação pode, inclusive, ser impedida de maneira voluntária por parte do criador do site, através do arquivo robots.txt, que diz aos web crawlers quais páginas não indexar.

![robots.txt](https://github.com/ryansakurai/artigo-deep-web/blob/main/imagens/img_3.png)

*Screenshot do arquivo robots.txt do Facebook*

Exemplos de páginas que fazem parte da Deep Web são: conversas no WhatsApp Web, feed do Facebook, caixa de e-mails, salas virtuais do Google Meet, bancos de dados, jornais científicos, etc. Portanto, é equivocada a crença popular de que a Deep Web seja um lugar hostil e perigoso, formado majoritariamente por sites criminosos e visitado por hackers.

## Dark Web
Por último, a camada mais profunda da web é a Dark Web. Ela também é formada por páginas que não foram indexadas pelos sites de busca, ou seja, tecnicamente também faz parte da Deep Web. Porém, o fator que a diferencia do resto da Deep Web é que ela funciona usando como suporte as darknets, ao invés da internet padrão.

Darknets são redes construídas em cima da internet que só podem ser acessadas com tecnologias ou configurações específicas. Apesar de existirem várias, a que está mais comumente associada à Dark Web é a rede Tor - The Onion Router.

Tor é uma rede descentralizada mantida por vários voluntários que usa uma técnica chamada onion routing para a transmissão de informações entre usuário e servidor, que consiste em passar o pacote por várias máquinas intermediárias, o envolvendo em várias camadas de criptografia. Pode ser feita uma analogia entre essas camadas com as de uma cebola, que é de onde se origina o termo onion routing.

No envio de pacote do cliente ao servidor, primeiramente, o dado é encriptado três vezes e encaminhado à primeira máquina, chamada de nó guarda. Essa máquina irá tirar uma camada de criptografia e encaminhar o pacote à máquina intermediária, que, por sua vez, removerá mais uma camada de criptografia e o enviará ao chamado nó de saída. Após a terceira camada de criptografia ser removida, o dado finalmente será encaminhado pelo nó de saída e chegará ao seu destino.

A volta do pacote (sentido servidor-cliente) é feita da maneira inversa. Primeiro o dado é enviado sem nenhuma das camadas de criptografia do Tor (pode ser que o dado já tenha sido encriptado antes de passar pela rede) ao nó de saída, que irá adicionar a primeira. Após isso, será adicionada uma camada de criptografia por máquina, até que o dado seja enviado do nó guarda até o cliente, que removerá as três camadas de uma vez.

![tor processo](https://github.com/ryansakurai/artigo-deep-web/blob/main/imagens/img_4.png)

*[Ilustração do processo de onion routing](https://www.bbc.com/news/technology-30637010)*

A anonimidade nesse sistema se deve ao fato de que um nó conhece apenas o IP do nó anterior e o do nó posterior. Por isso, com exceção do guarda, nenhum dos nós ou o servidor conhecem o IP do cliente, e vice-versa.

Os sites hospedados na rede Tor costumam ter a extensão .onion e podem ser acessados facilmente através do navegador Tor, que também pode ser usado para acessar sites da Surface Web, apesar de vários deles impedirem acesso através da rede onion.

Por causa da anonimidade provida pela Dark Web, ela muitas vezes é palco de atividades ilegais, como: pornografia ilegal, mercado ilegal, contrato de serviço de hackers, etc. Dito isso, seu acesso não é seguro e não compensa ser feito, se não houver um motivo específico para isso. Apesar disso, a Dark Web não é completamente negativa, pois também permite combater a censura em regimes totalitários e facilitar a ação de whistleblowers, por exemplo.

## Conclusão
Através deste artigo, conclui-se que apesar do uso intercambiado entre web e internet, os dois conceitos são diferentes, sendo a web dividida em camadas de acesso. Além disso, é errado dizer que a Deep Web é uma rede usada majoritariamente por criminosos, pois esse tipo de atividade se concentra em parte de uma porção da Deep Web: a Dark Web. Por conta de sua privacidade e anonimato, ela é uma ferramenta que pode muitas vezes ser usada de maneira benigna, porém ainda é insegura e carregada de ilegalidade e perigos. Portanto, ela não deve ser acessada por pessoas leigas e que não tem um bom motivo para acessá-la.

## Bibliografia
1. [Internet vs. Web: What's the Difference? (lifewire.com)](https://www.lifewire.com/difference-between-the-internet-and-the-web-2483335)
2. [A Brief History of the Internet (usg.edu)](https://www.usg.edu/galileo/skills/unit07/internet07_02.phtml)
3. [Who Invented the Internet? - HISTORY](https://www.history.com/news/who-invented-the-internet)
4. [What is the Web? - Definition from Techopedia](https://www.techopedia.com/definition/5613/web)
5. [What is Hypertext? (w3.org)](https://www.w3.org/WhatIs.html)
6. [What is the Deep Web and What Will You Find There? (techtarget.com)](https://www.techtarget.com/whatis/definition/deep-Web)
7. [Is the Dark Web Dangerous? What you need to know (kaspersky.com)](https://www.kaspersky.com/resource-center/threats/deep-web)
8. [What is a web crawler? | How web spiders work | Cloudflare](https://www.cloudflare.com/learning/bots/what-is-a-web-crawler/)
9. [Web Crawler: Entenda o Que é, Quando Usar e Como Funciona (neilpatel.com)](https://neilpatel.com/br/blog/web-crawler/)
10. [Going Dark: The Internet Behind The Internet : All Tech Considered : NPR](https://www.npr.org/sections/alltechconsidered/2014/05/25/315821415/going-dark-the-internet-behind-the-internet)
11. [What is Tor and how does it work? | TechRadar](https://www.techradar.com/vpn/what-is-tor-and-how-does-it-work)
