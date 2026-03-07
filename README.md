# 📊 Telecom X – Parte 2: Prevendo Churn



![Status](https://img.shields.io/badge/Status-Concluído-brightgreen)
![Python](https://img.shields.io/badge/Python-3.12%2B-blue)
![Pandas](https://img.shields.io/badge/Pandas-2.2%2B-orange)
![Matplotlib](https://img.shields.io/badge/Matplotlib-3.10%2B-blueviolet)
![Seaborn](https://img.shields.io/badge/Seaborn-0.13%2B-9cf)
![Scikit-learn](https://img.shields.io/badge/Scikit--learn-1.6%2B-orange)
![NumPy](https://img.shields.io/badge/NumPy-2.0%2B-blue)
![Google Colab](https://img.shields.io/badge/Google\_Colab-F9AB00?logo=google-colab\&logoColor=white)



## 📌 Descrição do projeto



Este projeto tem como objetivo desenvolver modelos de Machine Learning capazes de prever a evasão de clientes (churn) na empresa Telecom X. A partir de um conjunto de dados de clientes, foram realizadas etapas de pré-processamento, análise de correlação e seleção de variáveis, seguidas do treinamento e avaliação de modelos de classificação. O foco do projeto é identificar padrões que indiquem risco de cancelamento de serviços, permitindo gerar insights estratégicos que auxiliem a empresa a antecipar a evasão e melhorar a retenção de clientes.



## ✍️ Metodologia



### O que foi praticado neste projeto:



* Pré-processamento de dados para Machine Learning

* Construção e avaliação de modelos preditivos

* Interpretação dos resultados e entrega de insights 

* Comunicação técnica com foco estratégico



### Ferramentas:



* Trello

* Google Colab

* Git



### Tecnologias:



* **Python**

  * Pandas

  * Seaborn

  * Matplotlib

  * Scikit-learn

  * Numpy

## 🛠️ Preparação dos Dados

### 1. Classificação de Variáveis:

  * **Numéricas:** `Tenure` (meses de contrato), `ChargesMonthly`, `ChargesTotal` e `ChargesDaily`.

  * **Categóricas:** `Churn`, `Gender`, `SeniorCitizen`, `Partner`, `Dependents`, `PhoneService`, `PaperlessBilling`, `OnlineSecurity`, `OnlineBackup`, `DeviceProtection`, `TechSupport`, `StreamingTV`, `StreamingMovies`, `InternetService`, `Contract`, `PaymentMethod` e `MultipleLines`

### 2. Codificação e Normalização:

  * Uso de One-Hot Encoding para converter variáveis textuais em formatos numéricos processáveis pelos modelos.

### 3. Divisão de Dados:

  * Separação em 80% para treino e 20% para teste, garantindo que o modelo seja avaliado em dados que nunca viu anteriormente.

## 🤖 Modelagem e Justificativas
Foram implementados os modelos Random Forest e Regressão Logística.

* **Regressão Logística (com pesos balanceados):** Escolhida como modelo principal para o negócio devido à sua alta Sensibilidade (Recall).

## 📊 Insights da EDA

* **Contratos Mensais:** Representam o maior risco de evasão.

* **Tecnologia de Fibra Óptica:** Apresenta taxa de churn superior ao DSL, indicando possível problema de satisfação ou preço.

* **Falta de Suporte Técnico:** Clientes sem serviços de segurança online tendem a cancelar mais rápido.



## 📁 Estrutura do Projeto



```

telecom-x/

├── 📁 data/                    # Dados utilizados no projeto

│   └── 📄 dados_tratados.csv   # Arquivo de dados

├── 📄 README.md                # Documentação e descrição do projeto

├── 📄 Telecom_x2.ipynb         # Notebook

└── 📄 requirements.txt         # Dependências necessárias

```



## 🛠️ Abrir e rodar o projeto



### Com Git:



1. Clone este repositório:



```

git clone https://github.com/michellyaanjos/telecom-x-2.git

```



2. Instale os pacotes necessários:



```

pip install -r requirements.txt

```



3. Execute o notebook:



```

jupyter notebook Telecom_x2.ipynb

```



### Com Google Colab:



1. Acesse: https://colab.research.google.com



2. Clique em **File** → **Open notebook**



3. Vá na aba **GitHub**



4. Cole a URL do repositório abaixo e pressione Enter.



```

https://github.com/michellyaanjos/telecom-x-2.git

```



5. Selecione o arquivo .ipynb desejado e clique em **Open**.







## Autora

| [<img loading="lazy" src="https://avatars.githubusercontent.com/u/219448712?v=4" width=115><br><sub>Michelly Anjos</sub>](https://github.com/michellyaanjos) | 
| :---: | 



