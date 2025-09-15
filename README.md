# Teste de Performance 2: Detector de Fake News com NLP

Este repositório contém o segundo Teste de Performance (TP) do bloco de Machine Learning, focado em Processamento de Linguagem Natural (NLP).

### Objetivo

O projeto visa aplicar técnicas de NLP e Machine Learning para construir um classificador de texto capaz de distinguir notícias verdadeiras de falsas, utilizando um dataset real.

### Base de Dados

O dataset utilizado é o **"Fake and Real News Dataset"**. Ele consiste em dois arquivos:
* `Fake.csv`: Contém notícias classificadas como falsas.
* `True.csv`: Contém notícias classificadas como verdadeiras.

Os dados foram disponibilizados pelo professor e podem ser encontrados [neste repositório](https://github.com/professortiagoinfnet/inteligencia_artificial/tree/main).

### Etapas do Projeto

O desenvolvimento do classificador seguiu as seguintes etapas:

1.  **Pré-processamento e Extração de Features:**
    * Limpeza e preparação dos dados textuais.
    * Vetorização do texto utilizando a técnica **TF-IDF (Term Frequency-Inverse Document Frequency)** para transformar as palavras em features numéricas.

2.  **Treinamento e Ajuste do Modelo:**
    * Implementação de um modelo de classificação **K-Nearest Neighbors (KNN)**.
    * Análise do impacto do hiperparâmetro **K** (número de vizinhos) na performance do modelo, testando diferentes valores para encontrar a configuração ótima.

3.  **Avaliação de Performance:**
    * Uso de **validação cruzada (cross-validation)** para garantir uma estimativa robusta da eficiência do modelo.
    * Análise de métricas de classificação binária para avaliar o desempenho do modelo final, incluindo:
        * Acurácia
        * Precisão (Precision)
        * Recall (Sensibilidade)
        * F1-Score
        * Curva ROC (AUC)

4.  **Análise de Resultados e Conclusão:**
    * Interpretação das métricas de avaliação para determinar a eficácia do classificador.
    * Discussão sobre as limitações do modelo e os resultados obtidos.
