# Implementações de Machine Learning para Classificação de Qualidade de Maçãs

Este repositório contém implementações de alguns algoritmos de machine learning aplicados a um dataset rotulado sobre a qualidade de maçãs. O objetivo é explorar e comparar métodos de aprendizado não supervisionado e de redução de dimensionalidade no contexto da análise de qualidade das frutas.

## Algoritmos Implementados

1. **K-Means**: Algoritmo de agrupamento (clustering) utilizado para identificar grupos dentro dos dados sem utilizar os rótulos, com o intuito de verificar se existem padrões naturais de qualidade.

2. **t-SNE (t-distributed Stochastic Neighbor Embedding)**: Técnica de redução de dimensionalidade não-linear usada principalmente para visualização de dados de alta dimensão em duas ou três dimensões.

3. **PCA (Principal Component Analysis)**: Método de redução de dimensionalidade linear que transforma as variáveis originais em um conjunto de componentes principais, preservando a máxima variância possível.

4. **SFOM (Self-Organizing Feature Map)**: Uma implementação de mapas auto-organizáveis, que agrupam dados em uma estrutura semelhante a uma rede neural, facilitando a análise de padrões.

## Dataset

O dataset utilizado neste projeto contém amostras de maçãs rotuladas com diferentes características de qualidade. Ele inclui atributos que representam características físicas e químicas das maçãs, além de um rótulo indicando sua qualidade.

### Pré-processamento

Antes da aplicação dos algoritmos, os dados passam por um processo de normalização e, em alguns casos, redução de dimensionalidade. Este pré-processamento visa otimizar a eficiência e a precisão dos algoritmos de agrupamento e visualização.

## Estrutura do Repositório

- `k_means_code.ipynb`: Implementação do algoritmo K-Means com análise e visualização dos clusters formados.
- `k_means_x_PCA_x_tsne.ipynb`: Aplicação e Comparação de alguns métodos (k-meansxPCAxtsne) do t-SNE para redução de dimensionalidade e visualização dos dados.
- `sfom.ipynb`: Implementação do algoritmo SFOM, com gráficos que mostram o agrupamento auto-organizado das amostras de maçãs.
- `apple_quality.csv`: Contém o dataset sobre qualidade de maçãs usado nas análises.

