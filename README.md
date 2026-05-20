# TripleTen Sprint 3: Manipulação de Dados com Instacart 🛒

Este repositório contém o projeto final da terceira sprint do curso de Análise de Dados da TripleTen. O foco principal deste projeto foi a **Manipulação de Dados (Data Wrangling)** e a **Análise Exploratória de Dados (AED)** utilizando um conjunto de dados real do Instacart, uma plataforma de entrega de supermercado.

## 📋 Contexto do Negócio
O Instacart fornece um dataset que detalha os pedidos dos clientes, incluindo quais produtos foram comprados, em que ordem foram adicionados ao carrinho e se foram comprados anteriormente. O objetivo deste projeto foi limpar, preparar e analisar esses dados para extrair insights sobre o comportamento de compra dos usuários.

## 🛠️ Tecnologias e Ferramentas
*   **Python 3.x**
*   **Pandas:** Principal biblioteca para manipulação e limpeza de dados.
*   **Matplotlib:** Utilizada para visualizações iniciais e conferência de distribuições.

## 🚀 Desafios Técnicos Superados
Durante o desenvolvimento, foram aplicadas diversas técnicas avançadas de manipulação de dados:
*   **Tratamento de Dados Brutos:** Importação de múltiplos arquivos CSV com delimitadores específicos.
*   **Limpeza e Pré-processamento:**
    *   Identificação e tratamento de valores ausentes em colunas críticas como `days_since_prior_order` e `product_name`.
    *   Remoção de duplicatas explícitas e implícitas para garantir a integridade da análise.
    *   Conversão de tipos de dados para otimização de memória e precisão nos cálculos.
*   **Análise Exploratória de Dados (AED):**
    *   Análise da distribuição de horários e dias da semana em que os pedidos são feitos.
    *   Estudo do tempo de espera entre pedidos dos clientes.
    *   Identificação dos produtos mais populares e análise de reincidência de compra.

## 📊 Principais Insights
*   Identificação dos horários de pico de pedidos na plataforma, permitindo sugestões para otimização logística.
*   Análise da fidelidade dos clientes através da métrica de produtos reordenados.
*   Mapeamento das categorias de produtos (corredores e departamentos) com maior volume de vendas.

## 📁 Estrutura do Repositório
*   `notebook.ipynb`: O notebook Jupyter contendo todo o código Python, documentação dos passos e conclusões da análise.
*   `README.md`: Este arquivo com a apresentação do projeto.

---
*Este projeto faz parte da minha formação como Analista de Dados na TripleTen Brasil.*
