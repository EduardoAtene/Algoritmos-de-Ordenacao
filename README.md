# Estudo comparativo de algoritmos de ordenação

  Foi implementado os algoritmos de ordenação bolha, inserção, seleção, intercalação (mergesort) e quicksort. Foi gerado vetores de tamanhos 1000, 10000, 100000, 200000, 300000, 400000, 500000 com valores de inteiros crescentes, decrescentes e embaralhados (No qual foi embaralhe utilizando o algoritmo de Fisher-Yates). Em que foi comparado o tempo de execução para cada situação de valores crescentes, decrescentes e embalhados de cada tamanho de cada algoritmo. Foi obedecido os seguintes itens descritos abaixo:

1) O vetor foi alocado com malloc() e desalocado com free().
2) Foi medido o tempo de execução utilizando a função clock() da biblioteca time.h. O tempo foi medido exclusivamente nos algoritmos de ordenação (excluindo tempo de construção do vetor, embalhamento, etc).
3) O codigo gerou três tabelas uma para cada situação de crescente, descrescente e emba- ralhado. As tabelas contém nas linhas os tamanhos dos vetores e nas colunas os algoritmos, cada celula da tabela o tempo de execução.
4) Foi gerado um relatorio com gráficos utilizando as tabelas e foi apresentado uma discussão sobre os resultados obtidos. O relatorio foi gerado formato pdf e md (pasta relatorio).
