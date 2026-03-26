# Dashboard de Vendas Xbox Game Pass - Excel

Projeto desenvolvido como parte do desafio **"Criando um Dashboard de Vendas do Xbox com Excel"** da [DIO](https://www.dio.me).

## Objetivo

Transformar dados brutos de assinaturas do Xbox Game Pass em um dashboard visual e interativo no Excel, permitindo análise eficaz do desempenho de vendas.

## Estrutura do Arquivo

O arquivo `dashboard_xbox.xlsx` contém 4 abas:

| Aba | Descrição |
|-----|-----------|
| **Assets** | Paleta de cores e elementos visuais |
| **Bases** | Dados brutos de 295 assinantes |
| **Calculos** | Perguntas de negócio respondidas com fórmulas |
| **Dashboard** | Painel visual com KPIs e tabelas de análise |

## Perguntas de Negócio Respondidas

1. Qual o faturamento total de vendas de planos anuais (todas as assinaturas agregadas)?
2. Qual o faturamento total de planos mensais, separado por auto renovação?
3. Qual o total de vendas de assinaturas do EA Play Season Pass (planos mensais)?
4. Qual o total de vendas de assinaturas do Minecraft Season Pass (planos mensais)?

## KPIs do Dashboard

- Total de assinantes
- Faturamento total geral
- Ticket médio por assinante
- Faturamento por plano (Core, Standard, Ultimate)
- Faturamento por tipo de assinatura (Annual, Monthly, Quarterly)
- Faturamento de add-ons (EA Play e Minecraft)
- Faturamento mensal por auto renewal

## Dados

A base contém 295 registros com os campos:

- Subscriber ID, Name, Plan, Start Date
- Auto Renewal, Subscription Price, Subscription Type
- EA Play Season Pass, EA Play Season Pass Price
- Minecraft Season Pass, Minecraft Season Pass Price
- Coupon Value, Total Value

## Como Usar

1. Abra o arquivo `dashboard_xbox.xlsx` no Microsoft Excel
2. Navegue até a aba **Dashboard** para visualizar o painel
3. Os dados podem ser atualizados diretamente na aba **Bases** e todas as fórmulas recalculam automaticamente

## Tecnologias

- Microsoft Excel
- Fórmulas: SUMIF, SUMIFS, COUNTIF, SUMPRODUCT, COUNTA
