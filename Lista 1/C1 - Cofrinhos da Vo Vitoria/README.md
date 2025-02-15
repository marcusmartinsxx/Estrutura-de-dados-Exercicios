# Cofrinhos da Vó Vitória

Vó Vitória mantém, desde o nascimento dos netos Joãozinho e Zezinho, um ritual que faz a
alegria dos meninos. Ela guarda todas as moedas recebidas como troco em dois pequenos
cofrinhos, um para cada neto. Quando um dos cofrinhos fica cheio, ela chama os dois netos para
um alegre almoço, ao final do qual entrega aos garotos as moedas guardadas nos cofrinhos de
cada um.

Ela sempre foi muito zelosa quanto à distribuição igualitária do troco arrecadado. Quando, por
força do valor das moedas, ela não consegue depositar a mesma quantia nos dois cofrinhos, ela
memoriza a diferença de forma a compensá-la no próximo depósito.

## Tarefa

Vó Vitória está ficando velha e tem medo que deslizes de memória a façam cometer injustiças
com os netos, deixando de compensar as diferenças entre os cofrinhos. Sua tarefa é ajudar Vó
Vitória, escrevendo um programa de computador que indique as diferenças entre os depósitos,
de forma que ela não tenha que preocupar-se em memorizá-las.

## Entrada

A entrada é composta de vários conjuntos de teste. A primeira linha de um conjunto de teste
contém um número inteiro N, que indica o número de depósitos nos cofrinhos. As N linhas
seguintes descrevem cada uma um depósito nos cofrinhos; o depósito é indicado por dois
valores inteiros J e Z, separados por um espaço em branco, representando respectivamente os
valores, em centavos, depositados nos cofres de Joãozinho e Zezinho. O final da entrada é
indicado por N = 0.

## Saída

Para cada conjunto de teste da entrada seu programa deve produzir um conjunto de linhas na
saída. A primeira linha deve conter um identificador do conjunto de teste, no formato “Teste n”,
onde n é numerado seqüencialmente a partir de 1. A seguir seu programa deve escrever uma
linha para cada depósito do conjunto de testes. Cada linha deve conter um inteiro que
representa a diferença (em centavos) entre o valor depositado nos cofrinhos do Joãozinho e do
Zezinho. Deixe uma linha em branco ao final de cada conjunto de teste. A grafia mostrada no
Exemplo de Saída, abaixo, deve ser seguida rigorosamente.

## Exemplo

### Entrada:

    3
    20 25
    10 5
    10 10
    4
    0 5
    12 0
    0 20
    17 1
    0

### Saída:

    Teste 1
    -5
    0
    0

    Teste 2
    -5
    7
    -13
    3

## Restrições

- 0 <= N <= 100 (N = 0 apenas para indicar o fim da entrada)
- 0 <= J <= 100 (valor de cada depósito no cofre de Joãozinho)
- 0 <= Z <= 100 (valor de cada depósito no cofre de Zezinho)
