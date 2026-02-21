# Telecom X — Análise de Evasão de Clientes

## Contexto

A Telecom X vem enfrentando um volume elevado de cancelamentos, o que impacta diretamente a receita recorrente e a previsibilidade financeira do negócio. Diante desse cenário, tornou-se necessário compreender melhor os fatores que influenciam a saída dos clientes.

Este projeto tem como foco investigar esses padrões por meio de análise exploratória de dados.

---

## Objetivo

- Examinar o comportamento dos clientes que cancelaram o serviço  
- Identificar características associadas a maior risco de evasão  
- Gerar insumos para estratégias de retenção e análises preditivas futuras  

---

## Metodologia

### Extração de Dados

Os dados foram disponibilizados via API em formato JSON e estruturados em DataFrame utilizando a biblioteca Pandas.

### Limpeza e Tratamento

Durante essa etapa, foram realizadas as seguintes ações:

- Correção e padronização de variáveis categóricas  
- Conversão de colunas numéricas  
- Tratamento de valores ausentes e inconsistentes  
- Criação da variável `Churn_binaria` para facilitar as análises estatísticas  

Esses procedimentos garantiram maior confiabilidade nos resultados obtidos.

---

## Análise Exploratória

Foram avaliadas variáveis contratuais, demográficas e financeiras, com destaque para:

- Tipo de contrato  
- Tempo de permanência  
- Valor mensal  
- Método de pagamento  
- Serviços adicionais contratados  

A comparação entre clientes ativos e cancelados permitiu identificar diferenças relevantes entre os grupos.

---

## Principais Resultados

- Clientes com contrato mensal apresentam maior probabilidade de cancelamento.  
- A evasão ocorre com maior frequência nos primeiros meses de relacionamento.  
- O valor mensal médio é superior entre os clientes que cancelaram.  
- Métodos de pagamento não automáticos, como cheque eletrônico, estão associados a maior taxa de churn.  
- A ausência de serviços adicionais está relacionada a maior risco de evasão.  

---

## Recomendações

Com base nos achados, recomenda-se:

- Fortalecer ações de retenção nos primeiros meses de contrato.  
- Estimular a migração para contratos de maior duração.  
- Incentivar a adoção de pagamento automático.  
- Desenvolver ofertas que agreguem serviços complementares ao plano principal.  

---

## Tecnologias Utilizadas

- Python  
- Pandas  
- Matplotlib  
- Seaborn  
- Google Colab  


