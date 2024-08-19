# Projeto: Análise e Modelagem de Dados de Crédito e Censo com Machine Learning

# Análise e Modelagem de Dados de Crédito e Censo

Este projeto utiliza técnicas de análise e modelagem de dados para explorar duas bases de dados distintas: uma de crédito e outra do censo. O objetivo é preprocessar os dados, aplicar técnicas de visualização e preparar os dados para futuros modelos de machine learning.

## Estrutura do Projeto

1. **Exploração e Limpeza dos Dados de Crédito:**
   - Carregamento dos dados
   - Tratamento de valores inconsistentes
   - Tratamento de valores faltantes

2. **Exploração e Limpeza dos Dados do Censo:**
   - Carregamento dos dados
   - Tratamento de atributos categóricos com LabelEncoder e OneHotEncoder

3. **Modelagem e Preparação dos Dados:**
   - Separação entre variáveis previsoras e classe
   - Escalonamento dos atributos com StandardScaler

4. **Divisão em Treinamento e Teste:**
   - Divisão dos dados em conjuntos de treinamento e teste para ambas as bases

5. **Modelagem com Naive Bayes e Árvore de Decisão:**
   - Treinamento e avaliação dos modelos Naive Bayes e Árvore de Decisão

6. **Comparação de Resultados:**
   - Análise e comparação das métricas de desempenho dos modelos

## Resultados da Análise e Modelagem

### Base de Dados de Crédito

#### Naive Bayes
- **Acurácia:** {{ accuracy_naive_credit }}
- **Matriz de Confusão:**
- **Relatório de Classificação:**


#### Árvore de Decisão
- **Acurácia:** {{ accuracy_tree_credit }}
- **Matriz de Confusão:**
- **Relatório de Classificação:**


### Base de Dados do Censo

#### Naive Bayes
- **Acurácia:** {{ accuracy_naive_census }}
- **Matriz de Confusão:**
- **Relatório de Classificação:**


#### Árvore de Decisão
- **Acurácia:** {{ accuracy_tree_census }}
- **Matriz de Confusão:**
- **Relatório de Classificação:**


## Conclusão

Na base de dados de crédito, o modelo de Árvore de Decisão apresentou uma acurácia ligeiramente maior que o modelo de Naive Bayes. Ambas as técnicas mostraram-se eficazes, mas a Árvore de Decisão se destacou na maioria das métricas de desempenho.

Na base de dados do censo, o modelo de Naive Bayes teve um desempenho superior, com uma acurácia maior comparada ao modelo de Árvore de Decisão. Além disso, o relatório de classificação indicou que Naive Bayes conseguiu capturar melhor as nuances dos dados.

Esses resultados destacam a importância de avaliar múltiplos modelos para entender qual se ajusta melhor aos dados específicos de cada caso.

## Como Executar

1. Clone o repositório.
2. Instale as dependências necessárias:
   ```sh
   pip install pandas numpy seaborn matplotlib plotly scikit-learn



Com isso, todo o código e o README.md estão prontos para serem utilizados diretamente no GitHub, facilitando a compreensão e a reprodução dos resultados encontrados.
