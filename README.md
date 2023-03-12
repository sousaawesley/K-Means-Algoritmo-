# K-Means-Algoritmo-
O código é uma implementação do algoritmo K-Means em Python, que é um algoritmo de clustering amplamente utilizado para agrupar pontos em clusters com base na similaridade.

A classe K_Means contém métodos para definir as cores dos clusters, criar pontos aleatórios, mostrar gráficos dos pontos e centroides, calcular os centroides mais próximos dos pontos e recalcular a posição dos centroides.

A primeira parte do código define algumas variáveis e cria um conjunto de pontos e centroides aleatórios. Se a variável data_set_exemplo for definida como True, o conjunto de dados de exemplo será usado em vez de um conjunto de dados aleatório.

O método mostrar_grafico exibe o gráfico dos pontos e centroides em um gráfico de dispersão. O método mostrar_grafico_set exibe o gráfico dos pontos e centroides, mas desta vez os pontos são coloridos com as cores dos seus respectivos clusters.

Em seguida, há um loop while que recalcula a posição dos centroides até que eles não se movam mais. A condição de parada é se a posição dos centroides permanecer a mesma em iterações consecutivas. O loop primeiro calcula os centroides mais próximos de cada ponto e depois recalcula a posição dos centroides com base nesses pontos. Quando os centroides não se movem mais, o loop é interrompido e o resultado final é exibido em um gráfico.
