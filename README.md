# Projeto de Análise e Modelagem de Dados

Este repositório contém um projeto completo de análise exploratória de dados, preparação dos dados, modelagem e avaliação de desempenho de modelos de machine learning. O projeto aborda duas abordagens de modelagem: uma usando uma Rede Neural MLP e outra utilizando Regressão Logística. A seguir estão as principais atividades realizadas no projeto:

## Atividades Realizadas

### 1. Análise Exploratória dos Dados
   - Utilização da biblioteca pandas_profiling para gerar um relatório detalhado sobre a estrutura, distribuição e correlação das variáveis no conjunto de dados.

### 2. Preparação dos Dados
   - Carregamento do conjunto de dados a partir de um arquivo parquet.
   - Divisão dos dados em conjuntos de treino e teste.
   - Normalização dos dados de entrada utilizando a classe StandardScaler.

### 3. Modelagem
   - **Modelo MLP (Rede Neural Multicamadas):**
     - Configuração de uma MLP com camadas ocultas de tamanhos (1000, 50).
     - Treinamento do modelo usando os dados de treino.

   - **Modelo de Regressão Logística:**
     - Ajuste de parâmetros e treinamento do modelo usando a classe LogisticRegression da scikit-learn.

### 4. Avaliação e Performance dos Modelos
   - **Avaliação do Modelo MLP:**
     - Matriz de confusão.
     - Relatório de classificação (precision, recall, F1-score).

   - **Avaliação do Modelo de Regressão Logística:**
     - Matriz de confusão.
     - Relatório de classificação (precision, recall, F1-score).

## Como Executar a Solução

1. **Pré-requisitos:**
   - Certifique-se de ter o Python instalado em seu ambiente.
   - Instale as bibliotecas necessárias executando o seguinte comando no terminal:
     ```
     pip install -r requirements.txt
     ```

2. **Executando o Código:**
   - Abra o notebook ou script Python no ambiente desejado (Google Colab, Jupyter, etc.).
   - Execute cada célula de código sequencialmente.

3. **Explorando os Resultados:**
   - Após a execução, analise os resultados apresentados, incluindo os relatórios de análise exploratória, a matriz de confusão e os relatórios de classificação dos modelos.

## Contribuições e Melhorias
Contribuições são bem-vindas! Se você tiver sugestões para melhorar o código ou identificar possíveis problemas, sinta-se à vontade para abrir uma issue ou enviar um pull request.

Esperamos que este projeto seja útil e forneça insights valiosos sobre a análise e modelagem de dados. Boas análises!
