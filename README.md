# Dijkstra

O Algoritmo de Dijkstra tem como objetivo gerar uma árvore de caminhos mínimos de um grafo. As utilidades que uma árvore de caminhos mínimo tem no mundo real são várias. Qual será o caminho mais rápido para chegar da cidade A até a cidade B? Será que o melhor caminho é este mesmo? Muitas dessas dúvidas são tiradas ao analisar uma árvore de caminhos mínimos.

Após implementar o algoritmo (Arquivo Dijkstra.py), foi executado tendo em mente um agrupamento único de cidades.

### ![Árvore de Caminhos Mínimos](https://i.imgur.com/Jjjamrs.png)

A imagem acima representa a árvore tirada do grafo exemplo (contido no repositório).


# Conjuntos de dados

Pelo algoritmo de Dijkstra, é possível selecionar K pontos iniciais para o algoritmo, simplesmente zerando o peso de certos vértices. À partir disso, conseguimos gerar K agrupamentos de dados que representam K árvores de caminhos mínimos.
Segue abaixo um exemplo de um agrupamento K = 2.

### ![Conjunto K2 de Caminhos Mínimos](https://i.imgur.com/sIHQD3N.png)
É possível notar os dois clusters de dados na parte superior e inferior.

Mas por que parar por aqui? O algoritmo foi executado, sobre o mesmo grafo, para um K = 3, e o resultado obtido foi o representado na imagem abaixo.

### ![Conjunto K3 de Caminhos Mínimos](https://i.imgur.com/D3SYURp.png)

Observe 3 clusters que são todas árvores de caminhos mínimos localizadas na esquerda, direita e abaixo.
