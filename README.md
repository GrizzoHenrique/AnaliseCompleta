# Analise Completa de dados
# 📊 Análise de Dados e Modelagem Preditiva – Regressão Linear

Este repositório contém um projeto completo de **Análise de Dados** aplicado a uma base de **imóveis para aluguel**, abrangendo todas as etapas do pipeline de Ciência de Dados: desde a importação da base, **Análise Exploratória de Dados (EDA)**, **pré-processamento**, até o **treinamento e avaliação de modelos de Regressão Linear Simples e Múltipla**.

O projeto foi desenvolvido como parte do **Módulo 18 – Pratique (Regressão Linear)**, com foco didático e prático na aplicação de modelos de regressão.

---

## 🎯 Objetivo do Projeto

Construir modelos de regressão capazes de **prever o valor do aluguel de imóveis** a partir de variáveis explicativas como metragem, número de quartos, valor do condomínio, entre outras.

Os objetivos específicos incluem:

* Compreender o comportamento das variáveis do dataset
* Identificar relações lineares entre variáveis
* Aplicar técnicas básicas de pré-processamento
* Treinar e avaliar modelos de regressão linear simples e múltipla

---

## 📁 Base de Dados

A base utilizada contém informações de imóveis disponíveis para aluguel.

### Variáveis disponíveis:

* **Valor_Aluguel**: Valor total pago no aluguel (variável alvo)
* **Valor_Condominio**: Valor do condomínio
* **Metragem**: Área do imóvel em metros quadrados
* **N_Quartos**: Número de quartos
* **N_Banheiros**: Número de banheiros
* **Vagas_Garagem**: Número de vagas de garagem

---

## 🛠️ Tecnologias e Bibliotecas Utilizadas

* **Python 3**
* **Pandas** – Manipulação e análise de dados
* **NumPy** – Operações numéricas
* **Matplotlib & Seaborn** – Visualização de dados
* **Plotly Express** – Visualizações interativas
* **Scikit-learn** – Pré-processamento, treino e avaliação dos modelos

---

## 🔍 Etapas do Projeto

### 1️⃣ Importação e Inspeção Inicial dos Dados

* Leitura do arquivo CSV
* Visualização das primeiras linhas da base
* Verificação dos tipos de dados
* Identificação de valores nulos

Essa etapa é essencial para entender a estrutura da base e antecipar possíveis ajustes necessários.

---

### 2️⃣ Análise Exploratória de Dados (EDA)

Na análise exploratória, foram realizadas:

* Estatísticas descritivas das variáveis
* Análise da distribuição dos dados
* Visualização de possíveis outliers
* Análise da relação entre variáveis independentes e o valor do aluguel

Gráficos como histogramas, boxplots e gráficos de dispersão foram utilizados para apoiar as análises.

---

### 3️⃣ Pré-Processamento dos Dados

As principais etapas de pré-processamento incluíram:

* Tratamento de valores ausentes
* Seleção das variáveis relevantes
* Separação entre variáveis independentes (features) e variável dependente (target)
* Divisão da base em **conjunto de treino e teste**

Essas etapas garantem que os dados estejam adequados para o treinamento dos modelos.

---

### 4️⃣ Regressão Linear Simples

Foi aplicado um modelo de **Regressão Linear Simples**, considerando apenas uma variável explicativa para prever o valor do aluguel.

Objetivos dessa etapa:

* Entender o comportamento do modelo
* Visualizar a relação linear entre duas variáveis
* Interpretar coeficientes e intercepto

O desempenho do modelo foi avaliado com métricas apropriadas.

---

### 5️⃣ Regressão Linear Múltipla

Na sequên
