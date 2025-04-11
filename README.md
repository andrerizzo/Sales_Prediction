 🇧🇷 Este README está em português.  
 🇺🇸 [Click here for the English version.](README_EN.md)


# 📈 Previsão de Vendas com Séries Temporais

## 🔍 Introdução
Este projeto tem como objetivo analisar e prever o volume de vendas ao longo do tempo com base em dados históricos. Previsões de vendas são fundamentais para tomada de decisões estratégicas em áreas como marketing, logística, finanças e produção.

O estudo foi conduzido em partes para estruturar o pipeline completo de previsão, incluindo análise exploratória, tratamento de dados e aplicação de modelos de séries temporais.

---

## 🎯 Objetivos
- Analisar padrões temporais de vendas (tendência, sazonalidade, outliers)
- Construir modelos univariados de previsão
- Preparar o projeto para evolução com modelos multivariados ou machine learning

---

## 🧠 Etapas do Projeto

### ✅ Parte 1 — Análise Exploratória
- Inspeção dos dados
- Visualização de tendência e sazonalidade
- Verificação de estacionariedade

### ✅ Parte 2 — Pré-processamento
- Conversão de datas e ordenação temporal
- Tratamento de valores ausentes
- Agregações por frequência temporal (semanal/mensal)

### ✅ Parte 3 — Modelos Univariados
- Aplicação de modelos clássicos de séries temporais (ex: média móvel, decomposição, ARIMA)
- Avaliação da performance preditiva com métricas apropriadas (RMSE, MAE)

---

## 📦 Bibliotecas Utilizadas
- pandas
- matplotlib / seaborn
- statsmodels
- numpy
- scikit-learn (opcional)

---

## 📊 Resultados
O projeto demonstrou a viabilidade de prever volumes de vendas a partir de padrões históricos. Modelos univariados simples já apresentaram desempenho promissor, especialmente em séries com tendência clara e sazonalidade marcada.

### Comparação de Desempenho dos Modelos de Séries Temporais

| Modelo          | MAE         | MSE             | RMSE        | MAPE (%) |
|----------------|-------------|------------------|-------------|-----------|
| **Holt-Winters**   | **1.158.055,01** | **2.509.331.616.379,43** | **1.584.087,00** | **2,49** |
| SES            | 2.236.854,38 | 6.970.201.281.512,38 | 2.640.113,88 | 4,89      |
| ARIMA (5,1,5)  | 1.776.843,04 | 4.624.319.312.864,23 | 2.150.423,05 | 3,85      |
| ARIMA (5,0,5)  | 1.823.035,46 | 4.830.373.834.662,80 | 2.197.811,15 | 3,91      |


---

## 🔁 Próximos Passos
- Explorar modelos multivariados (incluir variáveis como promoções, clima, etc.)
- Testar modelos de machine learning e deep learning (Prophet, XGBoost, LSTM)
- Automatizar o pipeline e exportar previsões futuras
- Visualizações interativas para relatórios executivos

---

### 👨‍💻 Sobre o Autor

**André Rizzo**  
📊 Cientista de Dados Sênior | Estatístico | MBA em IA e Big Data (USP)  
🧠 Especialista em Machine Learning, Deep Learning e Modelagem Preditiva  
📍 Rio de Janeiro, Brasil  

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Perfil-0077B5?logo=linkedin&logoColor=white)](https://www.linkedin.com/in/andrerizzo1)
[![GitHub](https://img.shields.io/badge/GitHub-Portfólio-181717?logo=github&logoColor=white)](https://github.com/andrerizzo)
[![Email](https://img.shields.io/badge/Email-andrerizzo@hotmail.com-D14836?logo=gmail&logoColor=white)](mailto:andrerizzo@hotmail.com)

---

*Última atualização: 29/03/2025*
