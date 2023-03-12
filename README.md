# K-Means-Algoritmo-
O objetivo do algoritmo é agrupar um conjunto de pontos em K grupos, onde K é um número pré-definido pelo usuário.

A classe possui os seguintes métodos estáticos:

set_cores(Num_de_cores): define o número de cores que serão utilizadas para colorir os pontos nos gráficos gerados.

criar_pontos(K): gera aleatoriamente K pontos dentro de um plano de tamanho fixo, e retorna uma lista contendo esses pontos.

mostrar_grafico(centroides, pontos): plota um gráfico com os pontos e os centroides passados como argumento.

mostrar_grafico_set(centroides, pontos_dos_centroides): plota um gráfico com os pontos de cada centróide passados como argumento, além de mostrar a posição dos centroides.

centroides_mais_proximos(centroides, pontos): retorna uma lista de listas, onde cada lista contém os pontos que pertencem a um determinado centróide.

recalcular_centroides(centroides, pontos_dos_centroides): recalcula a posição dos centroides com base na média das posições dos pontos que pertencem a cada centróide.
