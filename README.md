# Challenge-TelecomX

# 📊 Análise de Evasão de Clientes - Telecom X

## 📌 Sobre o Projeto

Este projeto tem como objetivo analisar os dados de clientes da empresa fictícia **Telecom X** para identificar padrões relacionados à evasão de clientes (Churn).

A análise foi realizada utilizando Python e bibliotecas de ciência de dados para extrair, transformar e analisar os dados, além de gerar visualizações que ajudam a compreender os fatores que podem influenciar o cancelamento de serviços.

---

## 🎯 Objetivo

Identificar possíveis fatores que contribuem para a evasão de clientes e gerar insights que possam ajudar a empresa a desenvolver estratégias de retenção.

---

## 🛠 Tecnologias Utilizadas

- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  
- Google Colab / Jupyter Notebook  

---

## 🔄 Etapas do Projeto

O projeto segue o processo de **ETL (Extract, Transform, Load)** e análise exploratória de dados.

### 1️⃣ Extração de Dados

Os dados foram obtidos a partir de uma API em formato **JSON**, contendo informações sobre clientes da Telecom X.

### 2️⃣ Transformação de Dados

Os dados foram normalizados e convertidos em um **DataFrame do Pandas**, permitindo melhor manipulação e análise.

Durante esta etapa foram realizadas:

- Normalização do JSON
- Verificação de valores nulos
- Verificação de dados duplicados
- Ajuste de nomes de colunas

### 3️⃣ Análise Exploratória

Foram realizadas análises estatísticas e visualizações para compreender melhor o comportamento dos clientes.

Foram analisadas relações entre churn e variáveis como:

- Tipo de contrato
- Método de pagamento
- Tempo de permanência como cliente
- Valor mensal cobrado

---

## 📈 Visualizações Criadas

O projeto inclui diversos gráficos, como:

- Distribuição de evasão de clientes
- Evasão por tipo de contrato
- Evasão por método de pagamento
- Tempo de permanência vs evasão
- Gasto mensal vs evasão

As visualizações foram criadas utilizando **Seaborn** e **Matplotlib**.

---

## 📊 Principais Insights

A análise indicou alguns padrões importantes:

- Clientes com contratos **mensais (Month-to-Month)** apresentam maior taxa de evasão.
- Clientes com **menor tempo de permanência** tendem a cancelar com mais frequência.
- O **método de pagamento** pode estar relacionado com o comportamento de churn.
- Clientes com determinados níveis de **gasto mensal** apresentam maior probabilidade de cancelamento.

---

## 💡 Recomendações

Com base na análise, algumas possíveis estratégias incluem:

- Incentivar contratos de longo prazo
- Criar programas de retenção para clientes novos
- Oferecer benefícios para clientes com maior tempo de permanência
- Avaliar estratégias relacionadas aos métodos de pagamento

---

## 📁 Estrutura do Projeto

telecomx-churn-analysis

│

├── TelecomX_Analise.ipynb  
├── README.md  

---

## 🚀 Como Executar o Projeto

1. Clone o repositório

git clone https://github.com/seu-usuario/seu-repositorio.git

2. Abra o notebook no **Google Colab** ou **Jupyter Notebook**

3. Execute as células em ordem para reproduzir a análise.

---

## 👨‍💻 Autor

Projeto desenvolvido como parte de estudos em **Análise de Dados com Python**.
