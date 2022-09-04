O desempenho de um programa é afetado por:
- Algoritmo
- Linguagem, compilador e arquitetura
- Processador e sistema de memória
- Sistema de E/S (inclusive SO)

Algoritmo: determina o número de instruções do código fonte e o número de operações de entrada e saída, por exemplo, se é necessário realizar uma busca, pode-se escolher entre o algoritmo de bubble sort, quick sort e merge sort, são três opções que irão realizar a busca e ordenação na lista, onde cada uma tem particularidades ao desempenho e número de instruções e isso afeta o desempenho.

Linguagem, compilador e arquitetura: determina o número de instruções de máquina para cada instrução em nível de fonte, por exemplo, dependendo da linguagem escolhida em que será realizado o algoritmo, vai haver uma sequência determinada de instruções de alto nível e esse número de instruções de alto nível irá gerar um número diferentes de instruções em linguagem de máquina que vai ser executado no processador. O compilador irá afetar a forma que é feita essa tradução(de alto nível para baixo nível). Em relação a arquitetura, dependendo de qual processador essas instruções serão realizadas, irá haver uma diferença no desempenho por possuirem caracteristicas diferentes e por esse fator serem gerados um número de instruções diferentes.

Processador e sistema de memória: determinam a velocidade com que as instruções podem ser executadas. Se o algoritmo for executado em um processador Pentium ou em um processador I7, o desempenho vai ser diferente, são dois processadores com possuem a mesma arquitetura, porém possuem características de implementação diferentes e acessam o sistema de memória de forma diferente.

Sistema de E/S (hardware e sistema operacional): Determina a velocidade em que as operações de E/S podem ser executadas.