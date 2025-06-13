# Hackathon de Análise de Dados e Aprendizado de Máquina

### Professor: Howard Cruz  
### Alunos: Eve Chalab, Wilton Oliveira, Yasmin Neumman, Yasmin Souza  

---

## Tema do Projeto

**Análise de Dados de Preços de Casas nos Estados Unidos**

Este projeto tem como objetivo explorar e modelar dados de preços de imóveis residenciais nos Estados Unidos, utilizando técnicas de ciência de dados, estatística e aprendizado de máquina. A partir de um dataset público, busca-se compreender os fatores que mais influenciam o preço final de venda de uma casa e construir modelos capazes de realizar previsões confiáveis.

---

## Objetivos

- Realizar análise exploratória e estatística descritiva sobre os dados.
- Aplicar engenharia de atributos para otimizar as variáveis do modelo.
- Construir modelos de regressão e classificação com foco em previsão de preços.
- Explorar técnicas de aprendizado não supervisionado para segmentação de dados.
- Avaliar o desempenho dos modelos com métricas apropriadas.

---

## Conjunto de Dados

O conjunto de dados utilizado foi extraído da plataforma [Kaggle](https://www.kaggle.com/), contendo informações detalhadas sobre imóveis residenciais nos Estados Unidos, como:

- Número de quartos e banheiros  
- Área construída e do terreno  
- Ano de construção  
- Condição do imóvel  
- Localização (bairro ou região)  
- Entre outras variáveis estruturais e geográficas  

---

## Etapas do Projeto

### 1. Análise Exploratória de Dados (EDA)

- Identificação de distribuições estatísticas das variáveis
- Análise de correlação entre atributos
- Detecção de valores ausentes e outliers
- Geração de gráficos e tabelas descritivas

### 2. Engenharia de Atributos (Feature Engineering)

- Seleção das variáveis mais relevantes
- Transformação e codificação de dados categóricos
- Normalização e padronização de atributos contínuos
- Criação de variáveis derivadas

### 3. Aprendizado Supervisionado

**Regressão Linear**  
- Modelagem com regressão simples e múltipla  
- Avaliação com RMSE, MAE e R²  

**Classificação Binária**  
- Conversão do preço em classes (alto vs. baixo)
- Avaliação com métricas: Accuracy, Precision, Recall, F1-score  

### 4. Aprendizado Não Supervisionado

- **Clusterização**: K-Means e DBSCAN para segmentação dos imóveis  
- **Redução de Dimensionalidade**: PCA e t-SNE para visualização  
- **Análise de Associação**: Algoritmo Apriori para identificar padrões frequentes  
- **Detecção de Outliers**: Local Outlier Factor (LOF) aplicado aos dados  

### 5. Avaliação de Modelos

- Comparação entre algoritmos supervisionados
- Validação cruzada e divisão treino/teste
- Visualização de desempenho e erros
- Interpretação dos resultados obtidos

---

## Ferramentas e Tecnologias

- Linguagem: Python 3  
- Bibliotecas: Pandas, NumPy, Scikit-Learn, Seaborn, Matplotlib, Plotly  
- Modelagem: XGBoost, LightGBM, LogisticRegression  
- Clusterização e Redução: KMeans, PCA, t-SNE  
- Regras de Associação: MLxtend (Apriori)  
- Detecção de Outliers: LOF  

---

## Resultados Esperados

- Compreensão profunda dos fatores que influenciam os preços de imóveis  
- Modelos preditivos com boa capacidade de generalização  
- Estratégias de segmentação baseadas em características semelhantes  
- Visualizações e análises que auxiliam a tomada de decisão no mercado imobiliário  

---

## Referências

- Kaggle: House Prices – Advanced Regression Techniques  
- Scikit-Learn Documentation  
- Interpretable Machine Learning Book (Molnar, 2020)  
- UCI Machine Learning Repository  
