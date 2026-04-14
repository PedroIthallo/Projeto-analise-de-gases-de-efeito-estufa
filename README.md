# 🌍 Análise de Emissões de Gases de Efeito Estufa no Brasil

Projeto de **Análise Exploratória de Dados** focado nas emissões de gases de efeito estufa (GEE) por estado brasileiro, utilizando dados do SEEG (Sistema de Estimativas de Emissões de Gases de Efeito Estufa).

---

## 📋 Sobre o Projeto

Este notebook realiza uma análise detalhada das emissões de CO₂ equivalente no setor de **Mudança de Uso da Terra e Floresta** (principalmente desmatamento) nos estados brasileiros.

O objetivo é explorar padrões de emissão, identificar os estados mais críticos e calcular a emissão per capita para entender o impacto relativo de cada região.

---

## ✨ Principais Análises Realizadas

- Carregamento e limpeza do dataset de emissões (SEEG)
- Filtragem por setor: **Mudança de Uso da Terra e Floresta**
- Agrupamento por estado com soma total de emissões
- Junção com dados de população por estado
- Cálculo da **emissão per capita** (toneladas de CO₂e por habitante)
- Visualizações interativas com Plotly:
  - Scatter: População × Emissão Total
  - Scatter com bolhas: População × Emissão Total (tamanho = per capita)
  - Bar Chart: Ranking de emissão per capita

---

## 🗂️ Dataset

- **Fonte:** SEEG (2022)
- **Período:** Até 2021
- **Variáveis principais:**
  - `Estado`
  - `Emissão` (toneladas de CO₂ equivalente)
  - `População` (IBGE)
  - `Emissão per capita`

---

## 🛠️ Tecnologias Utilizadas

- **Python 3**
- **Pandas** (manipulação e agrupamento)
- **Plotly Express** (visualizações interativas)
- **Jupyter Notebook**

---

## 🚀 Como Executar

1. Clone o repositório:
   ```bash
   git clone https://github.com/SEU_USUARIO/nome-do-repositorio.git
