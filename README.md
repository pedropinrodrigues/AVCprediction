# AVC Prediction Project

# Projeto de Predição de AVC

Este repositório abriga um projeto abrangente para desenvolver um modelo de aprendizado de máquina que prevê AVC (Acidente Vascular Cerebral). O projeto está contido em um Jupyter Notebook (`notebook.ipynb`), que detalha minuciosamente cada etapa—da exploração dos dados à pré-processamento, treinamento do modelo e avaliação completa—oferecendo tanto uma demonstração prática quanto um recurso educacional em análise de dados na área de saúde.

Dataset adquirido no Kaggle em: https://www.kaggle.com/datasets/fedesoriano/stroke-prediction-dataset/data

## Visão Geral Detalhada

O notebook apresenta:

- **Exploração de Dados:**  
    Análise aprofundada das características do conjunto de dados, incluindo a distribuição das variáveis, análise de valores faltantes e identificação de possíveis desequilíbrios nos dados.

- **Pré-processamento:**  
    Instruções passo a passo para limpeza dos dados, tratamento de outliers, normalização e técnicas de transformação necessárias para preparar os dados para a modelagem.

- **Modelagem:**  
    Implementação de algoritmos de aprendizado de máquina com foco na otimização de hiperparâmetros, construção de pipelines e garantia de reprodutibilidade. O processo inclui a divisão dos dados em conjuntos de treino e teste para uma avaliação robusta.

- **Avaliação:**  
    Avaliação abrangente do desempenho utilizando métricas padrão, como acurácia, precisão, recall e curvas ROC. Além disso, o notebook oferece ferramentas de visualização para melhor compreensão do desempenho do modelo e identificação de possíveis áreas de melhoria.

## Como Começar

### Pré-requisitos

- Python 3.x
- Jupyter Notebook ou JupyterLab
- Bibliotecas populares do Python (por exemplo, pandas, numpy, scikit-learn, matplotlib)

Para instalar os pacotes, execute:

```bash
pip install -r requirements.txt
```

### Executando o Notebook

1. Clone o repositório:
        ```bash
        git clone https://github.com/your-username/AVCprediction.git
        ```
2. Altere para o diretório do projeto:
        ```bash
        cd AVCprediction
        ```
3. Inicie o Jupyter Notebook:
        ```bash
        jupyter notebook
        ```
4. Abra o arquivo `notebook.ipynb` e execute as células na sequência.

## Estrutura do Projeto

```
AVCprediction/
├── notebook.ipynb       # Análise detalhada e modelagem preditiva
├── README.md            # Visão geral e instruções de uso
├── data/healthcare-dataset-stroke-data.csv # Dados usados na análise
└── requirements.txt     # Lista de pacotes Python necessários
```

## Contribuindo

Contribuições são bem-vindas. Por favor, abra uma issue ou envie um pull request para sugestões ou melhorias.

## Licença

Este projeto é de código aberto e está disponível sob a licença MIT.

