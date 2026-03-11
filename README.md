# Roadmap de Desenvolvimento — 36 Meses
Objetivo: Data Engineer especializado em IA para o contexto de people analytics

Considerando que seu objetivo seja essa eu teria um plano por mes, dividido em 3 anos.
Não se atente apenas a tecnologia, mas principalmente a teoria que está por trás. 
Qual o conceito de orquestração? Para que serve? 
Coloquei no roadmap para esse exemplo Airflow, mas pode ser Azure Data Factory, Databricks Pipelines,etc.
Invariavelmente para alguns conceitos vc vai ter uma ferramenta que é mais conhecida mas o que mais importa é o conceito fundamental do que aquela tecnologia vem para resolver. Lembre-se ferramenta é apenas um facilitador para resolver o problema.

# Roadmap 36 Meses — Engenharia de Dados

| Mês | Foco | Tecnologias | Projeto Prático |
|----|----|----|----|
| 1 | Python básico | Python | Script analisando salários por área <br> • ler CSV <br> • calcular média salarial <br> • gerar relatório |
| 2 | Estruturas de dados | Python | Processar CSV de funcionários <br> • listas e dicionários <br> • limpar dados <br> • gerar métricas de RH |
| 3 | Manipulação de dados | Pandas | Pipeline simples de limpeza de dados <br> • tratamento de nulos <br> • normalização de colunas |
| 4 | SQL básico | SQL, PostgreSQL | Criar banco de dados de funcionários <br> • criar tabelas <br> • inserir dados <br> • consultas básicas |
| 5 | SQL intermediário | SQL | Queries analíticas de RH <br> • JOINs <br> • agregações <br> • métricas de headcount |
| 6 | SQL avançado | SQL | Análise temporal <br> • window functions <br> • CTE <br> • otimização de queries |
| 7 | Data visualization | Power BI | Dashboard de turnover <br> • métricas de RH <br> • gráficos de evolução |
| 8 | Versionamento | Git, GitHub | Criar repositório de projetos <br> • versionamento <br> • documentação |
| 9 | Linux básico | Linux | Automatizar execução de pipelines <br> • bash scripts <br> • agendamento |
| 10 | APIs | Python, JSON | Pipeline consumindo API pública <br> • ingestão de dados <br> • salvar em banco |
| 11 | ETL básico | Python, SQL | Pipeline ETL <br> • ingestão CSV <br> • transformação <br> • carga no banco |
| 12 | Projeto final ano 1 | Python, SQL, BI | Pipeline completo <br> • ingestão <br> • transformação <br> • dashboard |
| 13 | Modelagem de dados | SQL | Modelar warehouse de RH <br> • dimension tables <br> • fact tables |
| 14 | Data warehouse | PostgreSQL | Criar star schema <br> • modelagem analítica |
| 15 | Transformações de dados | dbt | Pipeline de transformação <br> • staging <br> • marts |
| 16 | Big Data | Apache Spark | Processar dataset grande <br> • Spark DataFrames |
| 17 | Spark avançado | Apache Spark | Pipeline distribuído <br> • particionamento <br> • otimização |
| 18 | Plataforma de dados | Databricks | Pipeline no Databricks <br> • notebooks <br> • jobs |
| 19 | Data Lake | Delta Lake | Criar data lake <br> • ingestão raw <br> • bronze layer |
| 20 | Orquestração | Apache Airflow | Automatizar pipelines <br> • DAGs <br> • agendamento |
| 21 | Streaming | Spark Streaming | Pipeline de eventos <br> • ingestão contínua |
| 22 | Cloud storage | AWS S3 / Azure Data Lake | Pipeline cloud <br> • ingestão para data lake |
| 23 | Cloud compute | AWS Glue / Azure Databricks | Processamento distribuído |
| 24 | Projeto final ano 2 | Spark, Databricks | Lakehouse de People Analytics <br> • bronze <br> • silver <br> • gold |
| 25 | Data governance | Data Catalog | Catalogar datasets <br> • metadados |
| 26 | Data quality | Great Expectations | Validação de dados |
| 27 | Observabilidade de dados | Logging | Monitoramento de pipelines |
| 28 | Infraestrutura como código | Terraform | Provisionar infraestrutura de dados |
| 29 | Containers | Docker | Containerizar pipelines |
| 30 | CI/CD | GitHub Actions | Pipeline de deploy de dados |
| 31 | Segurança de dados | IAM | Controle de acesso |
| 32 | Otimização de pipelines | Spark | tuning de jobs |
| 33 | Arquitetura de dados | Lakehouse | arquitetura moderna |
| 34 | Arquitetura completa | Data engineering | pipeline end-to-end |
| 35 | Portfólio | GitHub | documentar arquitetura |
| 36 | Projeto final | Databricks, Spark | Plataforma completa de dados |

Alguns datasets públicos para vc explorar e ir aprimorando seu conhecimento
# APIs e Datasets Públicos para Projetos de People Analytics

| API / Dataset | Tipo de Dados | Exemplos de Variáveis | Link | Projeto Sugerido |
|---|---|---|---|---|
| IBM HR Analytics Attrition Dataset | Dados de RH internos (sintéticos) | idade, departamento, salário, anos na empresa, attrition | https://www.kaggle.com/datasets/pavansubhasht/ibm-hr-analytics-attrition-dataset | Previsão de turnover |
| HR Analytics: Job Change of Data Scientists | Mobilidade de carreira | experiência, treinamento, mudança de emprego | https://www.kaggle.com/datasets/arashnic/hr-analytics-job-change-of-data-scientists | Modelo de previsão de job change |
| Adzuna Jobs API | Vagas de emprego | título da vaga, salário, empresa, localização | https://developer.adzuna.com/ | Skill Demand Dashboard |
| Adzuna Global Jobs Dataset | Dataset de vagas globais | salário mínimo/máximo, descrição da vaga, geolocalização | https://www.kaggle.com/datasets | Análise de demanda por skills |
| O*NET Web Services API | Skills e ocupações | habilidades, tarefas, requisitos educacionais | https://services.onetcenter.org/ | Skill Gap Analysis |
| Eurostat API | Mercado de trabalho europeu | emprego por setor, salários, demografia | https://ec.europa.eu/eurostat/web/main/data/web-services | European Labor Market Dashboard |
| World Bank Open Data API | Indicadores globais | taxa de emprego, educação, PIB | https://datahelpdesk.worldbank.org/knowledgebase/articles/889392-about-the-indicators-api-documentation | Global Workforce Analytics |
| IPOD Occupation Dataset | Títulos de cargos e ocupações | job titles, senioridade, domínio de trabalho | https://github.com/junhua/ipod | Career trajectory analysis |
| JobHop Career Trajectory Dataset | trajetórias de carreira | experiências profissionais, transições de carreira | https://arxiv.org/abs/2505.07653 | Career mobility modeling |
| UK ONS Data API | Estatísticas de emprego e população | emprego, salários, demografia | https://developer.ons.gov.uk/ | Workforce economic analysis |


Adicionaria aqui nesse plano de estudo algumas certificações para vc tirar também.

1. O Caminho das Certificações Microsoft (Azure + Power BI)
https://learn.microsoft.com/en-us/training/career-paths/data-engineer
A Microsoft possui uma trilha muito bem definida para quem quer ser Data Engineer.

Fase 1: Fundamentos (Meses 1-6)
Certificação: PL-300: Microsoft Power BI Data Analyst

Por que: Para People Analytics, o dado só tem valor se o RH conseguir ler. Dominar o Power BI logo cedo te dá o "output" necessário para validar seus estudos de SQL e Python.

Certificação: AZ-900: Azure Fundamentals

Por que: Entender o que é Cloud, Tenant, Resource Groups e Billing antes de sair criando recursos caros.

Fase 2: O Coração da Engenharia (Meses 12-24)
Certificação: DP-203: Azure Data Engineer Associate

O que estuda: Azure Data Factory (Orquestração), Azure Synapse Analytics, Azure Databricks e Azure Data Lake Storage Gen2.

Foco em IA: Aqui você aprende a arquitetura que suportará os modelos de Machine Learning (como o Azure Machine Learning service).

Fase 3: Especialista em IA e Governança (Meses 24-36)
Certificação: DP-600: Microsoft Fabric Analytics Engineer Associate

Por que: O Fabric é a evolução do ecossistema de dados da Microsoft. Ele une Data Factory, Synapse e Power BI em uma única plataforma SaaS. É o futuro imediato.

Certificação: AI-102: Designing and Implementing an Azure AI Solution

Foco: Integrar serviços de IA (como Azure OpenAI para análise de sentimentos em feedbacks de funcionários) no seu pipeline de dados.

2. O Caminho Databricks (O Motor de Big Data)
http://customer-academy.databricks.com/learn
Como você terá o Databricks no centro do seu roadmap, as certificações oficiais deles são diferenciais gigantescos:

Databricks Certified Data Engineer Associate: Foca em Lakehouse, Delta Lake e ETL com PySpark. (Ideal para o Mês 18).

Databricks Certified Data Engineer Professional: Foca em segurança avançada, monitoramento e otimização de performance (Tuning). (Ideal para o Mês 32).

3. Trilhas DataCamp (Conceitual e Prática)
https://www.datacamp.com/certification/data-engineer
O DataCamp é excelente para a parte de Python e Teoria. Eu recomendo seguir estas trilhas específicas ("Career Tracks"):

Data Engineer with Python: (28 cursos) - Cobre desde o básico de Python até Airflow e Spark. É a base para os primeiros 18 meses.

Data Engineering in Azure: (Focado especificamente em ferramentas Azure).

Data Quality & Governance: Fundamental para People Analytics (onde dados de salários e saúde são sensíveis).


Além disso os cursos de pós graduações de Big data, People analytics, Análise de dados, IA em universidades conceituadas e com preferência para cursos presenciais. Recomendo PUC-PR
