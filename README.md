# Análise do Conjunto de Dados de Habitação de Boston com Árvore de Decisão

## Descrição do Projeto
Este projeto envolve a análise do conjunto de dados de habitação de Boston, utilizando árvores de decisão para prever o valor médio das casas ocupadas pelos proprietários (MEDV). O projeto foca em entender as relações entre as características das casas e seus valores, otimizando o modelo de árvore de decisão através da pós-poda para um melhor desempenho preditivo.

## Métodos Utilizados
- **Coleta e Preparação de Dados**: Obtidos via URL e processados usando pandas e numpy.
- **Análise Exploratória de Dados**: Incluindo a criação de uma matriz de correlação e visualizações com seaborn e matplotlib.
- **Modelagem Preditiva**: Construção e otimização de uma árvore de decisão.
- **Pós-Poda**: Aplicação de poda de complexidade de custo na árvore de decisão para prevenir overfitting e melhorar a generalização.

## Resultados Principais
- Identificação de correlações significativas entre variáveis como CRIM, NOX, RM, LSTAT e MEDV.
- Construção inicial de uma árvore de decisão com profundidade máxima de 8, resultando em um MSE de 14.9359 no conjunto de teste.
- Aplicação da pós-poda, que reduziu o MSE para 12.3138, indicando uma melhoria na generalização.
- O modelo final apresentou um R-quadrado de 0.8104 no conjunto de teste, sugerindo que o modelo é capaz de explicar uma grande parte da variância na variável dependente.

## Ferramentas e Bibliotecas Utilizadas
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-Learn
