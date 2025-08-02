# 🩺 Análise da Oferta e Distribuição dos Serviços de Traumatologia e Ortopedia de Urgência em Pernambuco

📍 Projeto de análise exploratória dos dados de saúde pública voltado à compreensão da distribuição regional dos serviços especializados de urgência em Traumatologia e Ortopedia no estado de Pernambuco.

## 🎯 Objetivo

Este projeto tem como objetivo identificar **desigualdades territoriais** no acesso aos serviços de Traumatologia e Ortopedia de Urgência no estado de Pernambuco, analisando a distribuição por municípios e regiões de saúde.

---

## 🧰 Tecnologias e Ferramentas

- **Python (Google Colab)**: tratamento, análise e limpeza de dados com `pandas`, `numpy` e `matplotlib`.
- **Power BI**: visualização de dados, mapas coropléticos, dashboards interativos.
- **Bases públicas**:
  - [CNES – Cadastro Nacional de Estabelecimentos de Saúde](https://cnes.datasus.gov.br)
  - [IBGE – População por município](https://www.ibge.gov.br)

---

## 📊 Extração de dados

1. **Coleta de Dados**  
   - CNES (dados estruturados via ElasticCNES).
   - IBGE (população estimada por município de PE).

2. **Limpeza e Tratamento (ETL)**  
   - Remoção de duplicações e inconsistências.
   - Filtro apenas dos serviços com atuação direta em traumatologia e ortopedia de urgência.
   - Cruzamento de dados de serviços com população.
---
