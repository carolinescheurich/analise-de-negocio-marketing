# 📊 Análise de Dados: Otimização de Despesas de Marketing

Este projeto tem como objetivo elaborar recomendações estratégicas para otimizar despesas de marketing, a partir da análise de retenção de clientes e do volume de vendas por campanha.  
A base do estudo é composta por logs de visitas, pedidos e custos de campanhas publicitárias.

## 🧩 Descrição do conjunto de dados

O estudo utiliza três conjuntos de dados principais:

| Dataset | Descrição |
|----------|------------|
| visits_log_us.csv | Registro de visitas ao site/app |
| orders_log_us.csv | Informações sobre pedidos realizados |
| costs_us.csv | Gastos com campanhas de marketing |


## 🎯 Objetivos da análise

1. Avaliar o desempenho das campanhas de marketing, comparando custos, receita e retorno.
2. Medir a retenção de clientes, identificando o comportamento de recompra e a eficiência dos canais de aquisição.
3. Calcular indicadores-chave de marketing:
   - CAC (Custo de Aquisição de Cliente)
   - LTV (Lifetime Value)
   - ROI (Retorno sobre Investimento)
4. Identificar oportunidades de otimização de gastos, priorizando canais e campanhas com melhor rentabilidade.
5. Elaborar recomendações estratégicas para aprimorar a alocação do orçamento de marketing.

## 📈 Principais Resultados e Insights

- As campanhas apresentam diferenças significativas de performance entre os canais de aquisição. 
- Certos canais têm alto custo e baixa conversão, impactando negativamente o ROI geral.  
- Há oportunidade de redução de despesas em campanhas de baixo retorno e realocação de verba para canais com maior retenção e LTV.  
- O comportamento de retenção demonstra que a fidelização é mais forte entre usuários de determinados dispositivos e origens.  
- Recomenda-se monitorar continuamente o CAC e LTV por canal e otimizar o funil de conversão conforme o comportamento identificado.

## 🛠️ Tecnologias e Bibliotecas Utilizadas
- **Python 3.10+**  
- **Pandas** — manipulação de dados  
- **NumPy** — operações numéricas  
- **Matplotlib** — visualizações estáticas e interativas  
- **SciPy** — testes estatísticos e inferência  
- **Jupyter Notebook** — ambiente de análise
