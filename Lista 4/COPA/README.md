# Copa do mundo

Uma Copa do Mundo de futebol de botões está sendo realizada com times de todo o mundo. A classificação é baseada no número de pontos ganhos pelos times, e a distribuição de pontos é feita da forma usual. Ou seja, quando um time ganha um jogo, ele recebe 3 pontos; se o jogo termina empatado, ambos os times recebem 1 ponto; e o perdedor não recebe nenhum ponto.

Dada a classificação atual dos times e o número de times participantes na Copa do Mundo, sua tarefa é de determinar quantos jogos terminaram empatados até o momento.

## Entrada

A entrada contém vários casos de teste. A primeira linha de um caso de teste contém dois inteiros T e N, indicando respectivamente o número de times participantes (2 ≤ T ≤ 200) e o número de partidas jogadas (0 ≤ N ≤ 10000). Cada uma das T linhas seguintes contém o nome de um time (uma cadeia de máximo 10 letras e dígitos), seguido de um espaço em branco, seguido do número de pontos que o time obteve até o momento. O final da entrada é indicado por T = 0.

## Saída

Para cada um dos casos de teste seu programa deve imprimir uma única linha contendo um número inteiro, representando a quantidade de jogos que terminaram empatados até o momento.

### Exemplo de entrada

    3 3
    Brasil 3
    Australia 3
    Croacia 3
    3 3
    Brasil 5
    Japao 1
    Australia 1
    0 0

### Saída para o exemplo de entrada

    0
    2
