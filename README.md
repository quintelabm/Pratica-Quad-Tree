# Atividade Pratica - QuadTree

Objetivo: Criar uma implementação básica de uma QuadTree para armazenar pontos 2D (Point QuadTree).

Considere:

* cada nó da árvore possui duas coordenadas (X e Y)
* e pode ter no máximo 4 filhos: NE (nordeste), NW (noroeste), SW (sudoeste) e SE (sudeste)

## Implementação:

1 - Crie uma Classe ou estrutura `QuadTreeNode` para representar os nós da árvore;

2 - Crie uma Classe `QuadTree` para representar a árvore;

3 - Crie uma função para visualizar os pontos armazenados em cada nó;

4 - Crie uma rotina para inserção na árvore; 

## Primeiro Teste:

Teste se a inserção dos pontos está correta.

1 - Considere uma região (0,0) a (10,10).

2 - Insira os seguintes pontos: [(1, 1), (2, 2), (3, 3), (4, 4), (5, 5), (6, 6)].

3 - Verifique como os pontos sao organizados entre os nós da arvore.

## Segundo Teste:

Use a QuadTree para localizar rapidamente pontos dentro de uma região fornecida.
Considere que a região será definida por um retângulo (x_min, y_min) a (x_max, y_max).

1 - Implemente uma função `buscar_regiao(x_min, x_max, y_min, y_max)` que dado os limites da regiao retorna os pontos contidos na região especificada;

Obs: Utilize a propriedade hierárquica da QuadTree para evitar verificar nós irrelevantes;

Insira os pontos: [(1, 1), (3, 3), (7, 7), (9, 9), (2, 8), (6, 2)]

Realize buscas para as regiões:

a) Retângulo (2, 2) a (8, 8).

b) Retângulo (0, 0) a (4, 4).



