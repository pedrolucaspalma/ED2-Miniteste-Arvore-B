# ED2-Miniteste-Arvore-B

## Questão 1

Q: Por que o número de filhos, ou grau, de um nó de uma árvore B qualquer não pode ser
igual a 1?

R: Como o número de filhos é 1, seria possível criar uma árvore onde todos os nós tem somente 1 filho, o que acabaria criando uma lista ao invés de uma árvore.

## Questão 2

Q: Para que valores de ordem d a árvore da figura abaixo é uma árvore B válida?

R: Ordem 1

## Questão 3

Q: Mostre todas as árvores B válidas de ordem d = 1 que possuem as seguintes chaves
{1,2,3,4,5}

R:
![3_miniteste](https://user-images.githubusercontent.com/72577690/203876724-4a754384-403d-4f56-95a7-fbda15b7a00c.jpg)

## Questão 4

Q: Explique como encontrar a maior chave armazenada em uma árvore B.

R: Deve-se iterar sobre a árvore e ir sempre verificando os filhos direitos de cada nó. Quando o nó atual apontar para null, o nó atual será o maior valor da árvore.

## Questão 5

Q: Desenhe, passo a passo, uma árvore B de ordem d = 2 inserindo as seguintes chaves na
ordem em que estão sendo informadas: 99, 50, 60, 37, 45, 15, 28, 40, 58, 89, 70, 65, 59, 48, 49, 53.

R:

![5_1_arvore_b](./static/5-1.jpeg)
![5_2_arvore_b](./static/5-2.jpeg)
![5_3_arvore_b](./static/5-3.jpeg)
![5_4_arvore_b](./static/5-4.jpeg)
![5_5_arvore_b](./static/5-5.jpeg)

## Questão 6

Q: Sobre a árvore resultante do exercício anterior, ilustre, passo a passo, as seguintes
operações:
a) Inserir, também na ordem em que são informadas, as chaves 47, 46, 39, 52, 51, 55
(notar que as inserções são cumulativas).

![6_Aarvore_b](./static/6.jpeg)

b) Sobre o resultado do passo (a), excluir as chaves 37, 47, 46 e 65, na ordem informada.
Notar que as exclusões são cumulativas.

R:

OBS: A primeira remoção se encontra na imagem acima.
