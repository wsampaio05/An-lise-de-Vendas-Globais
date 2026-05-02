# Análise de Vendas Globais
https://colab.research.google.com/drive/1so7grCdHIM585DJ1iGBACPXRmbgif4X3?usp=sharing

#Visão Geral

Este projeto tem como objetivo analisar o desempenho de vendas de uma empresa global que atua nos canais online e offline, utilizando dados históricos de pedidos, produtos e países.

A análise foi realizada com foco em geração de insights de negócio, identificação de padrões e apoio à tomada de decisão baseada em dados.

---

# Estrutura dos Dados

O projeto utiliza três conjuntos de dados:

- **events.csv** — informações de vendas (pedidos, datas, preços, quantidades, canal)
- **products.csv** — categorias de produtos e seus códigos
- **countries.csv** — países, regiões e seus respectivos códigos

As tabelas foram integradas utilizando:

- `Product ID` ↔ `id`
- `Country Code` ↔ `alpha-3`



#Etapas do Projeto

# 1. Tratamento de Dados
- Remoção de valores ausentes críticos (Country Code)
- Conversão de datas (Order Date, Ship Date)
- Criação de métricas:
  - Receita (Revenue)
  - Custo (Cost)
  - Lucro (Profit)
  - Tempo de envio (Shipping Time)
- Verificação de duplicatas



# 2. Análise Exploratória

Foram analisadas as seguintes dimensões:

- 📦 Categorias de produtos
- 🌍 Países e regiões
- 🛒 Canais de vendas (Online vs Offline)
- 🚚 Tempo de envio
- 📅 Evolução ao longo do tempo
- 📆 Dia da semana (sazonalidade)



#  Principais Insights

- **Cosmetics** é a categoria mais lucrativa, com forte contribuição para o resultado total
- **Fruits** apresenta o menor lucro, indicando baixa margem ou menor valor agregado
- O lucro está concentrado em poucos países, sugerindo mercados mais maduros
- Existem diferenças relevantes entre os canais online e offline
- O tempo de envio não impacta diretamente o lucro
- Foram identificados padrões de vendas ao longo do tempo e dias da semana



# Recomendações

- Focar em categorias com maior margem de lucro
- Expandir atuação em mercados com baixo desempenho
- Investir no canal de vendas mais eficiente
- Melhorar a logística para otimizar a experiência do cliente
- Explorar padrões sazonais para campanhas estratégicas


#Tecnologias Utilizadas

- Python
- Pandas
- Matplotlib
- Seaborn
- Google Colab


# Resultados

O projeto resultou em:

- Integração e limpeza de dados
- Análises exploratórias detalhadas
- Visualizações estratégicas
- Geração de insights orientados a negócio



# Próximos Passos

- Construção de dashboard interativo (Looker Studio ou Power BI)
- Análise mais aprofundada por cliente
- Modelos preditivos de vendas



# Autor

Washington Sampaio  
Analista de Dados   
