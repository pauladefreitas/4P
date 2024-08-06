# Aula 1

## Introdução - fundamentos da computabilidade

### Teoria dos grafos

Euler soluciona o problema das pontes de Konigsberg em 1736, pois descobriu que este problema não é possível de ser solucionado. 
- obs: existem os grafos eulerianos; 

Século XIX: 

1. Formulação do problema das quatro cores:

Colorir os países de um mapa arbitrário utilizando no máximo 4 cores, de tal forma que países fronteiriços possuam cores diferentes.

A conclusão que se chegou é de que qualquer mapa pode ser colorido com apenas 4 cores. (ver se tá certo)

2. Problema do ciclo hamiltoniano:

Inventou um jogo que envolve um dodecaedro (sólido com 20 lados) onde cada vértice representa uma cidade e o objetivo era que o jogador viajasse ao "redor do mundo" passando por cada cidade exatamente uma vez. Dadas n cidades, determinar rota que passe por cada cidade uma vez e retorne ao ponto de partida. 

Para n=4, são 6 rotas possíveis e 24 testes (!4 = 24).

Para n grande torna-se inviável.

Em 1930, resultados fundamentais foram obtidos:

- Menger: conectividade;
- Kuratowski: Planaridade;
- Konig: 1º livro sobre teoria de grafos.

Desenvolvimento impulsionado pela aplicação em otimização e pelo uso de computadores na implementação dessas aplicações.

Grafo representa relações entre um conjunto de objetos, portanto é fácil encontrá-los nas mais diferentes situações.

ex: objetos são estações, trechos entre elas são as relações.
REDECOMEP BH (rede comunitária metropolitana de ensino e pesquisa BH) 
objetos são instituições de ensino e a conexão via fibra óptica são as relações. 

### Modelagem - Aspectos Fundamentais

1ª parte - identificação dos elementos (quantidade e natureza dos elementos, existência de diferentes tipos de elementos); 

2ª parte - identificação das relações (quantidade e natureza das relações, verificar se os relacionamentos são unidirecionais ou bidirecionais); 

3ª parte - construir um grafo (gerar conjunto de vértices e conjunto de arestas); 

4ª parte - solucionar o problema (usar método já existentes ou desenvolvendo novos).

MODELO {

    - vértices: casas e serviços;

    - arestas: ligações entre as casas e serviços. 

    -> determinar se o grafo possui uma representação sem cruzamento de arestas (grafo planar ou não).
}