+++
title = 'LinkedIn e teoria dos grafos'
date = 2025-06-28
draft = false
description = "Entendendo como o LinkedIn pode ser o exemplo perfeito para você entender teoria dos grafos."
image = "/images/grafos1.webp"
imageBig = "/images/grafos1.webp"
categories = ["algoritmos"]
authors = ["PalharesDev"]
avatar = "/images/avatar.webp"
+++

### Estrutura de um grafo
De forma simples, um grafo é uma maneira de representar conexões ou relações entre objetos. Pense nele como um desenho com pontos e linhas, sendo os pontos os vértices, eles representam os objetos individuais que você quer analisar, e as linhas sendo as arestas, que conectam os vértices, elas representam a relação ou conexão entre esses objetos.

Também podemos dizer que um grafo G é formalmente definido como um par de conjuntos (V,E), onde V é o conjunto de vértices e E é o conjunto de arestas, sendo que cada aresta em E conecta um par de vértices em V (mas talvez soe mais chato).

A beleza dos grafos está na sua versatilidade. Eles são usados em inúmeras áreas para modelar e resolver problemas complexos, no nosso caso, uma rede de conexões do LinkedIn.

![Grafo simples e nao direcionado](/images/grafo2a.webp)

### Grafos direcionados e não direcionados
Antes de entrarmos no assunto LinkedIn em si, é bom entender que existe uma distinção entre os grafos direcionados e não direcionados.

 Em um grafo não direcionado, as arestas representam uma relação mútua ou simétrica entre os vértices. Pense nas conexões no LinkedIn, quando você está conectado a alguém, essa pessoa também está conectada a você, ou seja, uma relação mútua. Em um grafo, se existe uma aresta conectando o vértice A ao vértice B, isso implica automaticamente que existe a mesma conexão do vértice B para o vértice A. A ordem dos vértices na definição da aresta não importa.

Em um grafo direcionado (também chamado de dígrafo), as arestas têm uma direção específica, pense em uma rede social em que você pode seguir alguém, mas aquela pessoa pode não necessariamente te seguir de volta, ou seja, a conexão possui uma direção. Uma aresta do vértice A para o vértice B não implica necessariamente que exista uma aresta do vértice B para o vértice A. A ordem dos vértices na definição da aresta é crucial.

No exemplo abaixo temos dois grafos, o não direcionado (Grafo A) e o direcionado (Grafo B).

![Grafo direcionado e nao direcionado](/images/grafos3.webp)

### Recomendação de Conexões
O LinkedIn constrói uma vasta rede social profissional modelada como um grafo. Cada usuário é um vértice (os pontos ".") e as conexões são as arestas (os traços "-"). Essa estrutura de grafo permite diversas funcionalidades.

Algoritmos analisam o grafo para sugerir pessoas que você talvez conheça com base em suas conexões de segundo e terceiro grau, simplificando, o algoritmo analisa seu perfil como um vértice e suas conexões como seus vizinhos, e para as recomendações de conexões ele sugere os vizinhos de seus vizinhos, e, quanto mais vértices vizinhos seus tiverem mais um vizinho em específico que você não possua em comum, maior é a chance desse perfil ser recomendado para você, além de outros fatores como interesses e histórico profissional.

![Explicação das conexões no linkedin utilizando grafos](/images/grafos2.webp)

### Busca de Empregos
Os grafos também ajudam a conectar candidatos a vagas com base em suas habilidades e nas conexões que podem facilitar essa ligação. A rede de conexões permite encontrar pessoas com habilidades específicas dentro da sua rede ou em redes mais amplas.  

Quando adicionamos competências ao nosso perfil, também ampliamos o número de vagas ofertadas, pois a rede de vértices vizinhos dessa vez são vagas com essas competências em comum, então lembre-se, nunca é demais adicionar cada competência sua em seu perfil (mas nada de inventar competências!).

### Por dentro do Linkedin
O algoritmo da rede também ajuda os recrutadores, ofertando os candidatos com a principais palavras-chave e competências que as suas vagas fornecem, facilitando muito o trabalho para não exigir aquela leitura de vários perfis e currículos.

O blog de engenharia do LinkedIn (engineering.linkedin.com) publicou um artigo sobre os desafios técnicos e as soluções implementadas, infelizmente apenas em inglês e sem detalhar algoritmos específicos, mas ainda, sim, mencionam o uso de grafos para modelar a rede e realizar análises.

![Artigo Linkedin](/images/grafos6.webp)

Não deixe de me seguir no LinkedIn. <a></a>

#### Redes sociais
X: [@palharesdev](https://x.com/palharesdev)<br>  
Youtube: [@PalharesDev](https://www.youtube.com/@PalharesDev)<br>  
LinkedIn: [Gabriel Palhares](https://www.linkedin.com/in/gabriel-pizzani-palhares/)<br>  
<!-- Instagram: [@palharesdev](https://www.instagram.com/palharesdev/)<br>     -->


