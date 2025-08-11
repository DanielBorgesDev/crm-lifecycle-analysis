# Customer Lifecycle Mapping / Mapeamento do Ciclo de Vida de Clientes

This repository presents a complete customer lifecycle analysis based on simulated CRM data. The project focuses on key metrics such as retention, churn, value segmentation, and marketing campaign responsiveness. It aims to showcase technical and business-oriented skills in the context of Customer Relationship Management (CRM).

Este repositório apresenta uma análise completa do ciclo de vida de clientes com base em dados simulados de CRM. O projeto foca em métricas como retenção, churn (evasão), segmentação por valor e resposta a campanhas de marketing. A proposta é demonstrar domínio técnico e visão de negócio aplicadas ao contexto de Customer Relationship Management (CRM).

## Project Goals / Objetivos do Projeto

- Simulate a realistic data environment with customer, transaction, and campaign information.
- Calculate metrics such as RFM, LTV, churn rate, and inactivity periods.
- Identify customer segments based on behavioral and response patterns.
- Visualize the customer journey from acquisition to reactivation.


- Simular um ambiente de dados com informações realistas de clientes, transações e campanhas.
- Calcular métricas como RFM, LTV, taxa de churn e períodos de inatividade.
- Identificar segmentos de clientes com base no comportamento de uso e resposta.
- Visualizar a jornada do cliente da aquisição à reativação.


## Business Questions / Perguntas de Negócio

- Which customers have the highest Lifetime Value (LTV)?
- What profiles respond better to marketing campaigns?
- What are the early signals of churn?
- How can we segment customers for more effective actions?
- What is the average retention time by acquisition channel or region?

- Quais clientes possuem maior valor ao longo do tempo (LTV)?
- Quais perfis respondem melhor a campanhas de marketing?
- Quais sinais indicam churn precoce?
- Como segmentar os clientes para ações mais eficazes?
- Qual é o tempo médio de permanência por canal de entrada ou região?

## Tech Stack / Tecnologias Utilizadas

- Python: Pandas, NumPy, Faker, Seaborn, Matplotlib
- SQL: SQLite (simulated database environment / ambiente de banco de dados simulado)
- Streamlit: interactive dashboard / dashboard interativo
- GitHub: version control and documentation / versionamento e documentação

## Project Structure / Estrutura do Projeto

crm-lifecycle-analysis/
├── data/
│   ├── clientes.csv         # Customer database / Base de clientes
│   ├── transacoes.csv       # Monthly transactions / Transações mensais
│   └── campanhas.csv        # Campaigns and responses / Campanhas e respostas
├── notebooks/
│   └── eda.ipynb            # Exploratory analysis / Análise exploratória
├── streamlit_app/
│   └── dashboard.py         # Interactive dashboard / Dashboard interativo
├── insights/
│   └── segments.txt         # Segment descriptions / Descrição de segmentos
└── README.md

## Author / Autor

Daniel Borges  
Software Developer and Data Analyst / Desenvolvedor de Software e Analista de Dados  
LinkedIn: https://www.linkedin.com/in/daniel-fborges/
GitHub: https://github.com/DanielBorgesDev

## License / Licença

This project is licensed under the MIT License.  
Este projeto está licenciado sob a Licença MIT.