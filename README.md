# Instacart Customer Purchasing Behavior Analysis

## English Version

# Overview

This project was developed as the final assignment for Sprint 3 of the TripleTen Data Analytics Program, focusing on **Data Wrangling** and **Exploratory Data Analysis (EDA)** using real-world transactional data from Instacart, a leading online grocery delivery platform.

The analysis involved transforming raw datasets into a structured analytical environment capable of supporting business insights related to customer purchasing behavior, reorder patterns, and product demand.

By applying data cleaning techniques and exploratory analysis, this project demonstrates the importance of data quality as the foundation for reliable decision-making.

# Objectives

* Prepare and validate raw transactional datasets for analysis.
* Identify and address data quality issues, including missing values and duplicate records.
* Analyze customer purchasing behavior and shopping habits.
* Investigate reorder patterns and customer loyalty indicators.
* Identify the most frequently purchased products and departments.
* Generate actionable insights to support inventory planning and operational efficiency.

# Business Context

Online grocery retailers generate large volumes of transactional data that can provide valuable insights into customer preferences and purchasing behaviors. However, extracting meaningful information requires robust data preparation and validation processes.

This project addresses that challenge by transforming Instacart's operational datasets into an analytical framework that enables the exploration of customer behavior, purchase frequency, and product demand trends.

The resulting insights can support decisions related to inventory management, assortment planning, and customer engagement strategies.

# Dashboard Structure & Analytical Views

## 1. Data Quality Assessment

Analytical view dedicated to evaluating and improving dataset reliability before conducting business analyses.

### Key Metrics

* Missing values distribution.
* Duplicate record identification.
* Data type consistency checks.
* Dataset completeness indicators.

### Features

* Detection of explicit and implicit duplicates.
* Treatment of missing values in critical variables.
* Validation of transactional integrity.
* Standardization of analytical datasets.

## 2. Customer Purchase Behavior Analysis

Perspective focused on understanding when and how customers interact with the platform.

### Key Metrics

* Order volume by hour of the day.
* Order distribution by day of the week.
* Average time between purchases.
* Purchase frequency patterns.

### Features

* Identification of peak shopping periods.
* Analysis of customer purchasing cycles.
* Evaluation of shopping behavior trends.
* Recognition of seasonal consumption patterns.

## 3. Product Demand & Reorder Analysis

Analytical perspective designed to identify high-demand products and customer loyalty behaviors.

### Key Metrics

* Most frequently purchased products.
* Reorder frequency indicators.
* Product popularity rankings.
* Department-level demand distribution.

### Features

* Identification of products with high repurchase rates.
* Analysis of customer retention through reorder behavior.
* Evaluation of product category performance.
* Support for assortment optimization initiatives.

# Technologies & Tools

* **Python:** Development of the complete analytical workflow.
* **Pandas:** Data cleaning, transformation, and exploratory analysis.
* **Matplotlib:** Construction of visualizations to support exploratory findings.
* **Jupyter Notebook:** Documentation and presentation of the analytical process.

# Technical Challenges Overcome

## Data Quality Management

* Identification and treatment of missing values in critical variables.
* Removal of explicit and implicit duplicate records.
* Validation of data consistency across multiple datasets.

## Integration of Multiple Data Sources

* Consolidation of several transactional files into a unified analytical environment.
* Standardization of variables to support cross-dataset analysis.

## Exploratory Analysis of Consumer Behavior

* Investigation of purchasing patterns across time dimensions.
* Identification of reorder behaviors as indicators of customer loyalty.

# Key Insights

## Consumer Purchase Timing

* Orders tend to concentrate during specific hours of the day and days of the week, revealing opportunities for operational optimization.

## Customer Loyalty Indicators

* High reorder rates among certain products suggest recurring consumption behaviors and potential customer preferences.

## Product Demand Concentration

* A relatively small subset of products accounts for a significant share of purchase volume, highlighting opportunities for assortment prioritization.

## Importance of Data Preparation

* Reliable business insights depend directly on the quality and consistency of the underlying datasets.

# Repository Structure

instacart-purchasing-behavior-analysis/

├── notebook.ipynb
├── README.md
└── images/
├── order-distribution.png
├── reorder-analysis.png
└── product-popularity.png

*This project is part of my Data Analytics portfolio, demonstrating my ability to transform raw transactional data into structured analyses that support customer understanding and data-driven business decisions.*

---

# Versão em Português

# Visão Geral

Este projeto foi desenvolvido como trabalho final da Sprint 3 do programa de Análise de Dados da TripleTen, com foco em **Manipulação de Dados (Data Wrangling)** e **Análise Exploratória de Dados (AED)** utilizando dados transacionais reais da Instacart, uma das principais plataformas de entrega de supermercados.

A análise envolveu a transformação de dados brutos em um ambiente analítico estruturado, capaz de gerar insights sobre comportamento de compra, padrões de recompra e demanda por produtos.

Por meio da aplicação de técnicas de limpeza e exploração de dados, o projeto evidencia a importância da qualidade dos dados como base para uma tomada de decisão confiável.

# Objetivo

* Preparar e validar conjuntos de dados transacionais para análise.
* Identificar e tratar problemas relacionados à qualidade dos dados.
* Analisar o comportamento de compra dos clientes.
* Investigar padrões de recompra e indicadores de fidelização.
* Identificar produtos e departamentos com maior demanda.
* Gerar insights que apoiem decisões relacionadas a estoque e operações.

# Business Context

Empresas do setor de varejo digital geram grandes volumes de dados transacionais que podem revelar importantes padrões de consumo. Entretanto, transformar esses dados em informações úteis exige processos robustos de preparação e validação.

Este projeto aborda esse desafio ao estruturar os dados operacionais da Instacart em um ambiente analítico que permite compreender hábitos de compra, frequência de consumo e tendências de demanda.

Os resultados obtidos podem subsidiar iniciativas relacionadas ao planejamento de estoque, definição de mix de produtos e estratégias de relacionamento com clientes.

# Dashboard Structure & Analytical Views

## 1. Avaliação da Qualidade dos Dados

Visão dedicada à validação e preparação dos dados antes da realização das análises de negócio.

### Principais Métricas

* Distribuição de valores ausentes.
* Identificação de registros duplicados.
* Consistência dos tipos de dados.
* Indicadores de completude dos dados.

### Funcionalidades

* Tratamento de duplicidades explícitas e implícitas.
* Correção de inconsistências nos registros.
* Padronização dos conjuntos de dados.
* Garantia da confiabilidade analítica.

## 2. Análise do Comportamento de Compra

Perspectiva voltada à compreensão de como e quando os consumidores realizam seus pedidos.

### Principais Métricas

* Volume de pedidos por hora do dia.
* Distribuição de pedidos por dia da semana.
* Tempo médio entre compras.
* Frequência de consumo dos clientes.

### Funcionalidades

* Identificação dos horários de pico.
* Avaliação dos ciclos de compra.
* Monitoramento de tendências comportamentais.
* Identificação de padrões de consumo.

## 3. Análise de Produtos e Recompras

Visão analítica voltada à identificação dos produtos mais demandados e dos padrões de fidelização.

### Principais Métricas

* Produtos mais comprados.
* Taxa de recompra.
* Ranking de popularidade dos produtos.
* Distribuição da demanda por departamento.

### Funcionalidades

* Identificação de produtos com maior recorrência.
* Avaliação da fidelidade dos clientes.
* Análise de desempenho das categorias.
* Apoio à otimização do mix de produtos.

# Technologies & Tools

* **Python:** Desenvolvimento do fluxo analítico completo.
* **Pandas:** Limpeza, transformação e análise exploratória dos dados.
* **Matplotlib:** Construção de visualizações analíticas.
* **Jupyter Notebook:** Documentação e apresentação das análises.

# Technical Challenges Overcome

## Gestão da Qualidade dos Dados

* Tratamento de valores ausentes em variáveis críticas.
* Remoção de registros duplicados.
* Garantia da integridade dos dados analisados.

## Integração de Fontes de Dados

* Consolidação de múltiplos arquivos transacionais.
* Padronização das estruturas para análises consistentes.

## Exploração de Comportamentos de Consumo

* Identificação de padrões temporais de compra.
* Análise de indicadores de recompra e fidelização.

# Key Insights

## Padrões de Compra dos Consumidores

* Identificação dos períodos com maior concentração de pedidos, auxiliando o planejamento operacional.

## Indicadores de Fidelização

* Produtos com altas taxas de recompra podem representar importantes oportunidades de retenção.

## Concentração da Demanda

* Um grupo reduzido de produtos concentra grande parte do volume de compras.

## Importância da Qualidade dos Dados

* Dados preparados adequadamente são essenciais para a geração de insights confiáveis.

# Repository Structure

instacart-purchasing-behavior-analysis/

├── notebook.ipynb
├── README.md
└── images/
├── distribuicao-pedidos.png
├── analise-recompras.png
└── popularidade-produtos.png

*Este projeto integra meu portfólio em Data Analytics, demonstrando minha capacidade de transformar dados transacionais brutos em análises estruturadas que apoiam a compreensão do comportamento do consumidor e a tomada de decisão orientada por dados.*
