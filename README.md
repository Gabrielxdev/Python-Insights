# Análise de Cancelamento de Clientes

Este repositório contém uma análise detalhada sobre o cancelamento de clientes em uma empresa com mais de 800 mil clientes. O objetivo é identificar os principais motivos de cancelamento e propor ações eficazes para reduzir essa taxa.

## 📊 Objetivo

O principal objetivo desta análise é responder às seguintes perguntas:

- Por que os clientes estão cancelando?
- Quais fatores estão mais correlacionados com o cancelamento?
- Quais ações podem ser tomadas para reter os clientes?

## 📂 Dados Relevantes

Com base no princípio de Pareto (80-20), identificamos que 80% dos cancelamentos podem ser explicados por 20% dos fatores. Os dados mais relevantes para essa análise incluem:

### Duração do Contrato

- Contratos mensais: 19.8% de cancelamento
- Contratos anuais: 40.2% de cancelamento
- Contratos trimestrais: 40.0% de cancelamento

### Idade dos Clientes

- Clientes com mais de 50 anos tendem a cancelar mais

### Ligações para o Call Center

- Clientes que fazem mais de 5 ligações para o call center têm uma maior probabilidade de cancelar

### Dias de Atraso

- Clientes com mais de 20 dias de atraso no pagamento têm uma maior tendência a cancelar

### Valor da Mensalidade

- Clientes com mensalidades entre 100 e 500 tendem a cancelar mais

## 🎯 Impacto dos Fatores

### Ligações para o Call Center

A falta de agilidade no atendimento ao cliente está diretamente relacionada ao cancelamento. Clientes que precisam fazer mais de 5 ligações para resolver problemas têm uma maior probabilidade de cancelar.

### Dias de Atraso

Clientes com mais de 20 dias de atraso no pagamento tendem a cancelar, indicando que problemas financeiros ou de cobrança são um fator significativo.

## 📈 Visualização de Dados

Utilizamos a biblioteca Plotly Express para criar gráficos dinâmicos que facilitam a visualização dos dados. Histogramas foram utilizados para analisar a distribuição de cancelamentos por:

- Idade dos clientes
- Número de ligações para o call center
- Dias de atraso
- Valor da mensalidade

## ❓ Questionamento e Entendimento

Após a análise inicial, levantamos hipóteses e verificamos a correlação e causalidade entre os fatores identificados e o cancelamento. Por exemplo:

### Hipótese 1

A falta de agilidade no atendimento ao cliente (medida pelo número de ligações para o call center) está diretamente relacionada ao cancelamento.

### Hipótese 2

Clientes com mais de 20 dias de atraso no pagamento têm uma maior probabilidade de cancelar devido a problemas financeiros ou de cobrança.

## 🧪 Análise Isolada dos Cenários

Para confirmar as hipóteses, realizamos uma análise isolada dos cenários:

### Cenário 1

Reduzir o número de ligações para o call center para menos de 5.

### Cenário 2

Reduzir os dias de atraso para menos de 21 dias.

Após aplicar essas mudanças no código, observamos uma redução significativa na taxa de cancelamento:

- Taxa de cancelamento original: 46.1%
- Taxa de cancelamento após ajustes: 18.4%

Isso confirma que os dois fatores principais (ligações para o call center e dias de atraso) têm um impacto significativo no cancelamento.

## 🚀 Conclusão e Ações Recomendadas

Com base na análise, recomendamos as seguintes ações para reduzir a taxa de cancelamento:

### Melhorar o Atendimento ao Cliente

- Investir em treinamento e recursos para o call center
- Reduzir o número de ligações necessárias para resolver problemas

### Otimizar o Processo de Cobrança

- Implementar políticas de cobrança mais flexíveis
- Oferecer opções de pagamento para clientes com dificuldades financeiras

Essas ações, focadas nos principais fatores identificados, têm o potencial de reduzir significativamente a taxa de cancelamento e melhorar a retenção de clientes.

