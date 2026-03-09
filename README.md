TelecomX – Churn Analysis
🧠 Visão Geral

Este projeto tem como objetivo analisar os dados da empresa fictícia TelecomX, uma operadora de telecomunicações que enfrenta altos índices de evasão de clientes (churn).

Através de técnicas de Análise Exploratória de Dados (EDA), buscamos identificar padrões, comportamentos e fatores que influenciam o cancelamento de serviços. O objetivo é gerar insights estratégicos que possam apoiar a tomada de decisão do negócio e contribuir para a redução da evasão de clientes.

O projeto foi desenvolvido seguindo as etapas clássicas de um pipeline de Ciência de Dados, incluindo extração, tratamento, análise e consolidação dos resultados.

🎯 Objetivos do Projeto

Compreender como a evasão de clientes está distribuída na base de dados

Identificar perfis de clientes com maior propensão ao churn

Analisar o impacto de variáveis categóricas e numéricas no cancelamento de serviços

Gerar insights acionáveis para apoiar estratégias de retenção de clientes

Consolidar os resultados em um relatório claro e estruturado

🛠️ Tecnologias Utilizadas

Python

Pandas – manipulação e limpeza de dados

Matplotlib – visualização de dados

Seaborn – visualizações estatísticas

Google Colab – ambiente de desenvolvimento

Git e GitHub – versionamento e publicação do projeto

📂 Estrutura do Projeto
📁 telecomx-churn-analysis

├── 📄 TelecomX_Data.json        # Dataset original
├── 📄 notebook.ipynb            # Notebook com todo o pipeline de análise
├── 📄 README.md                 # Documentação do projeto
└── 📄 relatorio_final.md / pdf  # Relatório final (opcional)
🔄 Etapas do Projeto
1️⃣ Extração de Dados

Importação do conjunto de dados no formato JSON para o ambiente de análise.

2️⃣ Limpeza e Tratamento de Dados

Nesta etapa foram realizadas as seguintes transformações:

Padronização de variáveis categóricas (ex.: Sim / Não)

Conversão de tipos de dados

Tratamento de valores inconsistentes ou ausentes

Criação da variável Contas_Diarias, permitindo análise do gasto médio diário dos clientes

3️⃣ Análise Exploratória de Dados (EDA)

Foram realizadas diversas análises para entender o comportamento da evasão:

Distribuição geral de churn na base

Análise de churn por variáveis categóricas (tipo de contrato, serviços adicionais, método de pagamento)

Análise de churn por variáveis numéricas (tempo de permanência, valor de cobrança)

Visualizações utilizadas

Gráficos de barras

Gráficos de pizza

Boxplots

Histogramas

📈 Principais Insights

A análise exploratória revelou alguns padrões importantes:

Clientes com contrato mensal apresentam maior taxa de cancelamento

Clientes com menor tempo de permanência possuem maior probabilidade de churn

Cobranças mensais mais elevadas estão associadas a maior evasão

Clientes sem serviços adicionais (como suporte técnico ou segurança online) tendem a cancelar mais

O método de pagamento Cheque Eletrônico apresentou maior risco de churn

📌 Conclusão

Os resultados indicam que a evasão de clientes na TelecomX está fortemente associada a fatores contratuais, financeiros e de experiência do usuário.

Esses insights podem ser utilizados para orientar estratégias de retenção, como:

incentivo a contratos de longo prazo

oferta de serviços adicionais

revisão de políticas de cobrança

melhoria da experiência do cliente

Além disso, esta análise pode servir como base para o desenvolvimento de modelos preditivos de churn, permitindo que a empresa antecipe possíveis cancelamentos.

🚀 Próximos Passos

Possíveis extensões deste projeto incluem:

Construção de um modelo de Machine Learning para previsão de churn

Balanceamento de classes para melhorar a performance do modelo

Feature Engineering (engenharia de atributos)

Avaliação de diferentes métricas de classificação (precision, recall, F1-score, ROC-AUC)
