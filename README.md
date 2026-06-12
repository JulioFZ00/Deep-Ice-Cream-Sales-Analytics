---

# 🍦 Deep Ice Cream – Sales Data Analysis

Após a implementação do banco de dados corporativo da Deep Ice Cream, a diretoria identificou a necessidade de transformar os dados operacionais em
informações estratégicas para apoiar a tomada de decisão.

Com o crescimento da empresa, tornou-se fundamental compreender o comportamento das vendas, identificar padrões de consumo, avaliar o desempenho dos
produtos e entender os fatores que impactam o faturamento da operação.

Diante desse cenário, o time de dados foi solicitado a realizar uma análise aprofundada dos dados históricos da empresa, buscando gerar insights que
auxiliassem a definição de estratégias comerciais e fornecessem uma base sólida para futuras iniciativas de previsão de demanda.

---

## 📌 Contexto de Negócio

A Deep Ice Cream é uma empresa fictícia do setor varejista de sorvetes com operações distribuídas em diferentes regiões do país.

Após a consolidação dos dados em um ambiente estruturado, surgiu a necessidade de responder questões estratégicas relacionadas ao desempenho do negócio, comportamento dos clientes, sazonalidade das vendas e oportunidades de crescimento.

A expectativa da diretoria era utilizar os dados disponíveis para compreender melhor a operação e apoiar decisões baseadas em evidências.

---

## 🎯 Objetivos da Análise 

A análise foi desenvolvida com o objetivo de responder perguntas relevantes para o negócio, tais como:

- Existem padrões sazonais nas vendas da empresa?
- Quais produtos apresentam melhor desempenho comercial?
- Como o faturamento evoluiu ao longo do tempo?
- Existem diferenças de comportamento entre regiões?
- Como os clientes se comportam em relação à frequência e volume de compras?
- Quais fatores podem auxiliar na previsão de vendas futuras?

Além da análise exploratória dos dados, o projeto contempla a construção de modelos preditivos voltados à estimativa de vendas e apoio ao planejamento da
operação.

---

## 📊 Visão Geral da Análise

Para responder às questões levantadas pela diretoria, foi realizado um processo completo de análise dos dados históricos de vendas da empresa.

O projeto contemplou etapas de validação, tratamento e exploração dos dados, permitindo identificar padrões de comportamento, tendências de mercado e
oportunidades de melhoria para o negócio.

As análises foram conduzidas utilizando Python, SQL e ferramentas de visualização de dados, combinando técnicas de análise exploratória, estatística
descritiva e modelagem preditiva.

A abordagem adotada foi dividida em quatro pilares principais:

- Validação e preparação dos dados
- Análise exploratória de vendas
- Geração de insights de negócio
- Modelagem preditiva para previsão de vendas

---

## 📂 Estrutura do Projeto

```
Deep-Ice-Cream-Sales-Analytics/
├── Notebooks/
│   ├── 01_EDA_Vendas.ipynb
│   ├── 02_Analise_Negocio.ipynb
│   └── 03_Machine_Learning.ipynb
│
└── README.md

```

--- 

## 🔎 Analysis Performed

The exploratory analysis includes:

### Data validation
- verification of missing values  
- consistency checks  
- dataset structure validation  

### Sales analysis
- revenue distribution  
- sales by product  
- sales by category  

### Customer analysis
- purchase patterns  
- number of orders per customer  

### Geographic analysis
- sales distribution by state  

### Time analysis
- sales trends  
- seasonality patterns  
- revenue evolution over time  

---

## 📈 Business Questions

Some of the business questions explored in this project include:

- Which products generate the most revenue?
- How are sales distributed across states?
- Are there seasonal patterns in ice cream sales?
- What is the distribution of customer purchasing behavior?

---

## 📊 Key Insights

### Revenue Stabilization in the Second Year

The second year of operation shows a more stable revenue pattern compared to the first year.  
While the first year presents stronger fluctuations, the second year appears to follow a more consistent growth pattern across the months.

This behavior may indicate a **more consolidated customer base and increasing recurring purchases** as the company matures.

<p align="center">
  <img width="630" src="https://github.com/user-attachments/assets/6a0637a2-8c73-4aa0-9541-bc7b38c65038"/>
</p>

Revenue in 2024 starts significantly higher in the first quarter,
declines during mid-year months, and gradually increases again toward the end of the year,
suggesting potential seasonal demand patterns.

---

### Product Average Ticket Analysis

The average ticket per product highlights differences in customer spending behavior across the product portfolio.

Some products generate a high volume of sales but with a lower ticket value, while others show fewer transactions but higher revenue per purchase.

<p align="center">
  <img width="630" src="https://github.com/user-attachments/assets/a2b2efd5-1000-42a1-9345-8a1da5b0cba9" />
</p>

---

## 🚀 How to Run the Project

1. Clone the repository

```bash
git clone https://github.com/JulioFZ00/Portfolio_DataScience.git
cd Portfolio_DataScience
pip install pandas duckdb matplotlib seaborn
```

2. Open the notebook

```bash
jupyter notebook Notebooks/01_EDA_Vendas.ipynb
```

The dataset used in the analysis is available in the **Notebooks/dados/** directory.

The **SQL/** folder contains example SQL queries used for analytical exploration.

---

## 👤 Author

**Julio F.**

Data Science enthusiast passionate about analytics, problem solving and data-driven decision making.

GitHub:  
https://github.com/JulioFZ00
