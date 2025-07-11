# 📊 Análise de Evasão de Clientes (Churn)

![Python](https://img.shields.io/badge/Python-3.10+-blue?style=for-the-badge&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Processing-yellowgreen?style=for-the-badge&logo=pandas&logoColor=white)
![Seaborn](https://img.shields.io/badge/Seaborn-Visualization-9cf?style=for-the-badge&logo=seaborn&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-Charts-orange?style=for-the-badge&logo=matplotlib&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange?style=for-the-badge&logo=jupyter&logoColor=white)
[![GitHub](https://img.shields.io/badge/GitHub-gouveamoura-181717?style=for-the-badge&logo=github)](https://github.com/gouveamoura)

Este projeto tem como objetivo analisar os fatores que influenciam a evasão de clientes em uma empresa de serviços. Utilizando técnicas de análise exploratória de dados com Python e bibliotecas como Pandas, Seaborn e Matplotlib, buscamos entender o perfil dos clientes que mais cancelam o serviço e propor estratégias para reduzir o churn.

---

## 🧠 Objetivos

- Identificar padrões de comportamento entre clientes que evadiram.
- Verificar quais variáveis estão mais associadas à evasão.
- Propor ações estratégicas para retenção de clientes com base nos dados analisados.

---

## 🗃️ Dados Utilizados

O conjunto de dados contém informações sobre os clientes, incluindo:

- https://github.com/ingridcristh/challenge2-data-science/tree/main


- `gender` – Gênero do cliente  
- `SeniorCitizen` – Indica se o cliente tem 65 anos ou mais  
- `tenure` – Tempo (em meses) com o plano  
- `Contract` – Tipo de contrato (`month-to-month`, `one year`, `two year`)  
- `PaymentMethod` – Método de pagamento (`electronic check`, `mailed check`)  
- `Charges.Monthly` – Gasto mensal  
- `Charges.Total` – Gasto total  
- `Charges.Day` – Gasto diário  
- `Churn` – Indica se o cliente saiu (`True`) ou permaneceu (`False`)

---

## 🧹 Tratamento de Dados

- Normalização de dados do tipo JSON
- Conversão de colunas do tipo `object` para `float` e `boolean`
- Padronização de valores categóricos como "Yes"/"No"
- Remoção ou correção de valores nulos/inconsistentes

---

## 📊 Análises Realizadas

- Distribuição geral da evasão (`Churn`)
- Churn por gênero e idade (`SeniorCitizen`)
- Churn por método de pagamento (`PaymentMethod`)
- Churn por tipo de contrato (`Contract`)
- Relação de churn com gasto mensal, total e diário
- Relação entre churn e tempo de contrato (`tenure`)

Visualizações: gráficos de pizza, barras, boxplots, violinplots e linhas, com uso de `seaborn` e `matplotlib`.

---

## 🔍 Principais Insights

- A evasão foi mais comum entre clientes:
  - Com menos de 65 anos
  - Com contratos mensais
  - Com pagamento eletrônico
  - Com altos gastos mensais e totais
  - Com pouco tempo de contrato (clientes novos)

- O gênero não foi um fator relevante para o churn.

---

## 💡 Recomendações

- Criar programas de fidelidade com foco nos primeiros meses de contrato
- Incentivar migração para contratos mais longos com vantagens comerciais
- Oferecer planos mais acessíveis para clientes com gastos elevados
- Personalizar o atendimento e suporte para novos clientes
- Avaliar e adaptar os métodos de pagamento para reduzir a evasão associada ao `electronic check`

---

## 🛠 Tecnologias Utilizadas

![Google Colab](https://img.shields.io/badge/Google%20Colab-%23F9A825.svg?style=for-the-badge&logo=googlecolab&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![Seaborn](https://img.shields.io/badge/Seaborn-42a5f5?style=for-the-badge&logo=seaborn&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557c?style=for-the-badge&logo=matplotlib&logoColor=white)
![Plotly](https://img.shields.io/badge/Plotly-3F4F75?style=for-the-badge&logo=plotly&logoColor=white)
![Jupyter Notebook](https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white)

---

## ✍️ Autor

**Vinicius Moura**  
[![LinkedIn](https://img.shields.io/badge/LinkedIn-vinicius--moura-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/vinicius-gouvêa-de-moura-303586254)  
[![GitHub](https://img.shields.io/badge/GitHub-gouveamoura-181717?style=for-the-badge&logo=github)](https://github.com/gouveamoura)

---
