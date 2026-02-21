# Telecom X — Análise de Evasão de Clientes (Churn)

## 1. Contexto

A Telecom X enfrenta uma alta taxa de evasão de clientes (churn), impactando diretamente sua receita e estabilidade financeira. Este projeto realiza uma análise exploratória de dados com o objetivo de identificar os principais fatores associados ao cancelamento.

---

## 2. Objetivo

- Identificar padrões relacionados ao churn  
- Apoiar decisões estratégicas de retenção  
- Fornecer base para futuros modelos preditivos  

---

## 3. Metodologia

### Extração de Dados
- Dados obtidos via API em formato JSON  
- Normalização e estruturação utilizando Pandas  

### Limpeza e Tratamento
- Tratamento de valores nulos e inconsistentes  
- Conversão de variáveis numéricas  
- Padronização de variáveis categóricas  
- Criação da variável alvo `Churn_binaria`  

### Análise Exploratória de Dados
- Taxa geral de churn  
- Churn por tipo de contrato  
- Relação entre tempo de contrato e evasão  
- Impacto do valor mensal  
- Método de pagamento  
- Influência de serviços adicionais  

---

## 4. Principais Resultados

- Contratos mensais apresentam maior taxa de churn  
- Cancelamentos concentram-se nos primeiros meses de contrato  
- Clientes que cancelam possuem maior valor mensal médio  
- Pagamentos via cheque eletrônico apresentam maior risco  
- Ausência de serviços adicionais aumenta a probabilidade de evasão  

---

## 5. Recomendações

- Incentivar contratos de maior duração  
- Implementar estratégias de retenção nos primeiros 30/60/90 dias  
- Estimular pagamento automático  
- Desenvolver pacotes com serviços agregados  

---

## 6. Tecnologias Utilizadas

- Python  
- Pandas  
- Matplotlib  
- Seaborn  
- Google Colab  

---
