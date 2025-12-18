# 📊 Bitcoin Data Pipeline – Databricks

Projeto de **análise de dados** com foco em **ETL, SQL e visualização**, utilizando o **Databricks (Free Edition)** para coletar, transformar e analisar dados de cotação do Bitcoin em reais (BRL).

--

## 🎯 Objetivo do Projeto

Construir um pipeline simples de dados que:
- Consome dados de uma API externa
- Realiza tratamento e padronização
- Armazena os dados em tabelas
- Permite análises via SQL
- Gera visualizações em dashboard

Projeto desenvolvido com foco em **aprendizado prático** e **portfólio para vagas de Analista de Dados Júnior / Power BI**.

--

## 🛠️ Tecnologias Utilizadas

- **Databricks Free Edition**
- **Python**
- **SQL**
- **API REST**
- **Delta Lake**
- **Dashboards Databricks**

--

## 🔄 Pipeline de Dados

1. Extração dos dados de cotação do Bitcoin via API
2. Transformação dos dados (tratamento de datas, valores e estrutura)
3. Armazenamento em tabelas no Databricks
4. Consultas SQL para análise
5. Visualização dos dados em dashboard

--

## 📈 Dashboard

O dashboard apresenta:
- Última cotação do Bitcoin (BRL)
- Valor máximo e mínimo com timestamp
- Média do valor do Bitcoin ao longo do tempo

[Dashboard Bitcoin](dashboard/dashboard_bitcoin.jpeg)

--

## 📂 Estrutura do Projeto

```text
bitcoin-data-pipeline-databricks/
│
├── src/
│   └── pipeline_bitcoin.py
│
├── dashboard/
│   └── dashboard_bitcoin.jpeg
│
└── README.md
