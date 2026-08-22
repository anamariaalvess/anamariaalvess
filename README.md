# Olá, sou Ana Maria Alves

**Cientista de Dados | Doutora em Matemática | Machine Learning | Analytics | Risco de Crédito | MLOps**

Sou **Cientista de Dados e Doutora em Matemática pela Universidade Federal de Goiás (UFG)**, com experiência em desenvolvimento de modelos de machine learning, análise e engenharia de dados, modelagem estatística, risco de crédito, Business Intelligence e monitoramento de modelos.

Minha trajetória combina uma sólida formação matemática com experiência prática na construção de soluções orientadas a dados, desde processos de ETL e desenvolvimento de dashboards até modelagem preditiva, análise de risco, qualidade de dados e estruturação de pipelines de Machine Learning.

Atualmente, aplico conhecimentos de **estatística, machine learning, analytics e engenharia de dados** na construção de soluções reproduzíveis, rastreáveis e orientadas à tomada de decisão.

> 🔐 Os projetos profissionais nos quais atuei envolvem dados, regras e informações corporativas confidenciais. Por isso, os projetos públicos deste perfil utilizam **dados públicos, fictícios ou sintéticos** para demonstrar metodologias e competências equivalentes sem expor informações das organizações.

---

# 🚀 Projetos em destaque

Os projetos abaixo representam diferentes áreas da minha atuação em dados e foram estruturados para demonstrar não apenas código, mas também **arquitetura, qualidade, documentação, reprodutibilidade e aplicação dos dados a problemas de negócio**.

## 🏪 [Análise de Varejo com Databricks](https://github.com/anamariaalvess/databricks-analise-varejo)

Projeto end-to-end de **engenharia, qualidade e análise de dados** desenvolvido no Databricks, simulando o ambiente analítico de uma distribuidora.

O projeto percorre todo o ciclo dos dados, desde a geração e ingestão até a construção de Data Marts, indicadores executivos e recomendações para tomada de decisão.

### Principais conceitos demonstrados

* arquitetura **Lakehouse**;
* **Medallion Architecture** — Landing, Bronze, Silver e Gold;
* processamento distribuído com **Apache Spark e PySpark**;
* armazenamento com **Delta Lake**;
* organização e governança com **Unity Catalog**;
* modelagem em dimensões e fatos;
* testes de qualidade de dados;
* validação de completude, unicidade, domínio e integridade referencial;
* quarentena de registros inconsistentes;
* implementação de **Quality Gate**;
* segmentação de clientes com **RFM**;
* classificação de produtos utilizando **Curva ABC**;
* análise de estoque e cobertura;
* sugestão quantitativa de compras;
* análise financeira e inadimplência;
* Databricks SQL;
* **AI/BI Dashboards**;
* exploração dos dados utilizando **Databricks Genie**.

**Stack:** `Databricks` · `Apache Spark` · `PySpark` · `Delta Lake` · `SQL` · `Unity Catalog` · `AI/BI Dashboards` · `Git`

➡️ **[Acessar projeto](https://github.com/anamariaalvess/databricks-analise-varejo)**

---

## 🤖 [Natural Language to SQL com IA Generativa](https://github.com/anamariaalvess/natural-language-to-sql)

Aplicação desenvolvida em Python para converter **perguntas escritas em linguagem natural em consultas SQL**, combinando IA Generativa com informações estruturadas sobre as fontes de dados.

A aplicação identifica automaticamente tabelas, colunas e tipos disponíveis e utiliza esses metadados como contexto para geração das consultas.

### Fluxo simplificado

```text
Pergunta do usuário
        │
        ▼
Schema + metadados das tabelas
        │
        ▼
Construção do contexto
        │
        ▼
Modelo de linguagem
        │
        ▼
Consulta SQL
```

### Principais conceitos demonstrados

* **IA Generativa e Large Language Models — LLMs**;
* Natural Language to SQL — NL2SQL;
* construção de prompts;
* utilização de contexto estruturado para LLMs;
* leitura automática de schemas;
* utilização do `information_schema`;
* manipulação de arquivos **Parquet**;
* consultas analíticas utilizando **DuckDB**;
* desenvolvimento de aplicações com **FastAPI**;
* integração com APIs externas;
* variáveis de ambiente e gerenciamento de credenciais;
* desenvolvimento de interface web;
* geração programática de dados sintéticos.

**Stack:** `Python` · `FastAPI` · `OpenAI API` · `DuckDB` · `SQL` · `Parquet` · `Pandas` · `PyArrow` · `Jinja2`

➡️ **[Acessar projeto](https://github.com/anamariaalvess/natural-language-to-sql)**

---

## 📊 [Behavior Score — Machine Learning e MLOps](https://github.com/anamariaalvess/behavior-score-mlops)

Projeto voltado à aplicação de **Machine Learning e MLOps em risco de crédito**, estruturando o ciclo de vida de um modelo de Behavior Score.

A proposta é representar, em um ambiente de portfólio, práticas relacionadas ao desenvolvimento, versionamento, disponibilização e acompanhamento de modelos de risco.

### Principais conceitos demonstrados

* preparação de dados para modelagem;
* modelagem aplicada a **risco de crédito**;
* Behavior Score;
* pipeline de Machine Learning;
* rastreabilidade de experimentos;
* gerenciamento do ciclo de vida de modelos;
* versionamento;
* scoring;
* monitoramento de performance;
* acompanhamento de estabilidade;
* identificação de **data drift e model drift**;
* aplicação de práticas de **MLOps**.

**Stack:** `Python` · `Machine Learning` · `MLflow` · `Evidently` · `Git` · `MLOps`

➡️ **[Acessar projeto](https://github.com/anamariaalvess/behavior-score-mlops)**

---

## 🔎 Portfólio em uma visão

| Projeto                              | Competências demonstradas                                                           |
| ------------------------------------ | ----------------------------------------------------------------------------------- |
| **Análise de Varejo com Databricks** | Data Engineering · Lakehouse · PySpark · Delta Lake · Data Quality · Analytics · BI |
| **Natural Language to SQL**          | IA Generativa · LLMs · Python · FastAPI · SQL · DuckDB · Parquet                    |
| **Behavior Score — MLOps**           | Machine Learning · Risco de Crédito · Model Monitoring · MLflow · MLOps             |

---

# 🎯 Principais áreas de atuação

### Machine Learning e Estatística

* Modelagem estatística
* Machine Learning
* Modelos de classificação
* Risco de crédito
* Credit Score
* Behavior Score
* Collection Score
* Segmentação de clientes
* Validação de modelos
* Backtesting e avaliação Out-of-Time
* Monitoramento de performance e estabilidade

### Data Analytics e Business Intelligence

* Análise exploratória de dados
* Construção de KPIs
* Business Intelligence
* Dashboards
* Análise financeira
* Inadimplência
* Análise de vendas
* Segmentação RFM
* Curva ABC
* Gestão de estoques
* Planejamento de compras
* Storytelling com dados

### Engenharia e Qualidade de Dados

* ETL e preparação de dados
* Integração de fontes
* Modelagem dimensional
* Arquitetura Lakehouse
* PySpark
* Delta Lake
* Data Quality
* Validação de integridade
* Data Marts
* SQL

### MLOps e IA

* MLflow
* Evidently
* Monitoramento de modelos
* Data Drift
* Model Drift
* Versionamento de experimentos
* IA Generativa
* LLMs
* Natural Language to SQL

---

# 🛠️ Tecnologias

## Linguagens

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square\&logo=python\&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square\&logo=postgresql\&logoColor=white)
![R](https://img.shields.io/badge/R-276DC3?style=flat-square\&logo=r\&logoColor=white)

## Dados e Engenharia

![Databricks](https://img.shields.io/badge/Databricks-FF3621?style=flat-square\&logo=databricks\&logoColor=white)
![Apache Spark](https://img.shields.io/badge/Apache_Spark-E25A1C?style=flat-square\&logo=apachespark\&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square\&logo=pandas\&logoColor=white)
![DuckDB](https://img.shields.io/badge/DuckDB-FFF000?style=flat-square\&logo=duckdb\&logoColor=black)
![Oracle](https://img.shields.io/badge/Oracle-F80000?style=flat-square\&logo=oracle\&logoColor=white)
![Parquet](https://img.shields.io/badge/Apache_Parquet-50ABF1?style=flat-square\&logo=apache\&logoColor=white)

## Machine Learning e Estatística

![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square\&logo=scikitlearn\&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=flat-square\&logo=tensorflow\&logoColor=white)
![Keras](https://img.shields.io/badge/Keras-D00000?style=flat-square\&logo=keras\&logoColor=white)
![Statsmodels](https://img.shields.io/badge/Statsmodels-4051B5?style=flat-square)

## MLOps e Versionamento

![MLflow](https://img.shields.io/badge/MLflow-0194E2?style=flat-square\&logo=mlflow\&logoColor=white)
![Evidently](https://img.shields.io/badge/Evidently-6C5CE7?style=flat-square)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square\&logo=git\&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square\&logo=github\&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square\&logo=docker\&logoColor=white)

## Analytics e Aplicações

![Power BI](https://img.shields.io/badge/Power_BI-F2C811?style=flat-square\&logo=powerbi\&logoColor=black)
![Plotly](https://img.shields.io/badge/Plotly-3F4F75?style=flat-square\&logo=plotly\&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557C?style=flat-square)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square\&logo=fastapi\&logoColor=white)

---

# 💼 Experiência profissional

## Cientista de Dados — Indra Group

**Abril de 2026 — Atual**

Atuação na estruturação de soluções analíticas voltadas à **gestão pública**, integrando dados sociais, econômicos e de planejamento governamental.

Principais atividades:

* estruturação de soluções orientadas a dados;
* integração e análise de diferentes fontes;
* modelagem dimensional;
* mapeamento e documentação de fontes de dados;
* padronização e validação de informações;
* qualidade de dados;
* construção de análises diagnósticas;
* apoio à definição de arquiteturas de dados;
* desenvolvimento de análises voltadas à tomada de decisão.

---

## Cientista de Dados — Sicoob UniCentro Br

**Junho de 2024 — Abril de 2026**

Atuação em projetos de Ciência de Dados aplicados ao **ciclo de crédito, risco, inadimplência e segmentação de cooperados**.

Principais atividades:

* desenvolvimento e monitoramento de modelos de **Behavior Score, Credit Score e Collection Score**;
* utilização de Regressão Logística e AdaBoost;
* definição de períodos de modelagem e validação;
* backtesting;
* avaliação fora do tempo — Out-of-Time;
* acompanhamento de performance por **AUC/ROC e KS/KSI**;
* monitoramento de estabilidade utilizando **PSI**;
* acompanhamento de indicadores de carteira;
* projeções de inadimplência;
* criação de perfis de cooperados utilizando dados históricos;
* desenvolvimento de dashboards e relatórios analíticos;
* automação de análises com Python.

**Stack:** `Python` · `SQL` · `scikit-learn` · `TensorFlow` · `MLflow` · `Evidently` · `Power BI`

---

## Cientista de Dados e DBA Oracle — DataUnique Tecnologia

**Abril de 2023 — Maio de 2024**

Atuação combinando Ciência de Dados, desenvolvimento de aplicações analíticas e administração de bancos de dados.

Principais atividades:

* desenvolvimento de aplicação para conversão de **linguagem natural em SQL**;
* integração entre aplicações e bancos de dados;
* processos de ETL;
* utilização de Python, SQL e DuckDB;
* desenvolvimento de dashboards e relatórios;
* administração de bancos de dados Oracle;
* gerenciamento de usuários, permissões e objetos;
* backups com RMAN, Export e Data Pump;
* recuperação e manutenção de ambientes Standby.

---

## Cientista de Dados — Inko Tecnologia

**Janeiro de 2022 — Março de 2023**

Atuação no desenvolvimento de soluções de **Business Intelligence e Analytics integradas ao ERP Winthor**.

Principais atividades:

* desenvolvimento do Dash360;
* dashboards de vendas e faturamento;
* indicadores de desempenho comercial;
* segmentação de clientes por **RFV**;
* análise de **Curva ABC**;
* indicadores de inadimplência;
* análises financeiras;
* gestão de estoques;
* cálculo de giro e cobertura;
* sugestão de compras;
* desenvolvimento de aplicações utilizando Python e tecnologias web.

**Stack:** `Python` · `SQL` · `JavaScript` · `HTML` · `CSS` · `Docker`

---

# 🎓 Formação acadêmica

### Especialização em Data Science e Estatística Aplicada — UFG

Formação complementar voltada à aplicação de estatística, programação, banco de dados e Big Data em problemas de Ciência de Dados.

### Doutorado em Matemática — UFG

Pesquisa em **Sistemas Dinâmicos, Teoria de Bifurcações e Campos de Vetores Suaves por Partes**, incluindo publicação de artigo científico em revista internacional e apresentação de trabalhos em eventos acadêmicos.

### Mestrado em Matemática — UFG

Pesquisa em Sistemas Dinâmicos, ciclos limites, T-singularidades e sistemas lineares suaves por partes.

### Bacharelado em Matemática — UFG

Formação sólida em matemática, lógica, equações diferenciais, geometria e fundamentos teóricos utilizados posteriormente em modelagem estatística e Ciência de Dados.

---

# 🏅 Certificações

## Databricks

* **Academy Accreditation — AI Agent Fundamentals**
* **Academy Accreditation — Generative AI Fundamentals**
* **Academy Accreditation — Databricks Fundamentals**

🔗 [Ver credenciais verificáveis](https://www.credential.net/profile/anamariaalvesdasilva132119/wallet)

## Mercado Financeiro

* **CPA-20 — ANBIMA**
* **C-Pro R — ANBIMA**

---

# 📚 Formação complementar

## 🤖 Machine Learning, Inteligência Artificial e MLOps

* [MLflow: Gestão do Ciclo de Vida de Modelos de Machine Learning](./docs/formacao_complementar/ML-Flow-Alura.pdf) — Alura
* [Implantar e Consumir Modelos com Azure Machine Learning](./docs/formacao_complementar/Modelos-com-Azure-Microsoft.pdf) — Microsoft
* [Otimizar o Treinamento de Modelos com Azure Machine Learning](./docs/formacao_complementar/Otimizar-Modelos-com-Azure-Microsoft.pdf) — Microsoft
* [Experimentar com Azure Machine Learning](./docs/formacao_complementar/Experimente-com-Azure-Microsoft.pdf) — Microsoft
* [Explorar e Configurar o Azure Machine Learning](./docs/formacao_complementar/Explorar-e-Configurar-Azure-Microsoft.pdf) — Microsoft
* [Implementar uma Solução de Ciência de Dados e Machine Learning para IA](./docs/formacao_complementar/Implementar-IA-Microsoft.pdf) — Microsoft
* [Criar um Agente de IA](./docs/formacao_complementar/Criar-um-agente-de-IA-Microsoft.pdf) — Microsoft
* [Inteligência Artificial — Fundamentos](./docs/formacao_complementar/IA-Fundamentos-DSA.pdf) — Data Science Academy

## 🗄️ Engenharia e Plataformas de Dados

* [Implementar um Lakehouse com Microsoft Fabric](./docs/formacao_complementar/Lakehouse-Fabric-Microsoft.pdf) — Microsoft
* [Data Analysis with Python](./docs/formacao_complementar/Data-Analysis-Frre-Code-Camp.pdf) — freeCodeCamp

## 📊 Analytics e Visualização de Dados

* [Power BI Aplicado a Negócios](./docs/formacao_complementar/Power-BI-Voitto.pdf) — Grupo Voitto
* [Python Interactive Dashboards with Plotly Dash](./docs/formacao_complementar/plotly-udemy.pdf) — Udemy
* [Introdução à Ciência de Dados](./docs/formacao_complementar/Intro-Ciência-de-Dados-FGV.pdf) — FGV
* [Introdução à Ciência de Dados](./docs/formacao_complementar/Introducao-ciencia-de-dados-DSA.pdf) — Data Science Academy

## 📈 Processos, Gestão e Negócios

* [Gestão de Processos](./docs/formacao_complementar/Gestao-de-Processos-Alura.pdf) — Alura
* [Gestão de Stakeholders](./docs/formacao_complementar/Gestao-de-Stakeholders-Alura.pdf) — Alura
* [Gestão da Mudança](./docs/formacao_complementar/Gestão-da-mudanca-Alura.pdf) — Alura

## 🛠️ Ferramentas e Versionamento

* [Git: do Básico ao Avançado](./docs/formacao_complementar/git-Udemy.pdf) — Udemy

---

# 📬 Contato

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Ana_Maria_Alves-0A66C2?style=flat-square\&logo=linkedin\&logoColor=white)](https://www.linkedin.com/in/anamariaalves1/)
[![GitHub](https://img.shields.io/badge/GitHub-anamariaalvess-181717?style=flat-square\&logo=github\&logoColor=white)](https://github.com/anamariaalvess)

* **LinkedIn:** [linkedin.com/in/anamariaalves1](https://www.linkedin.com/in/anamariaalves1/)
* **Currículo Lattes:** [lattes.cnpq.br/1133726890707075](http://lattes.cnpq.br/1133726890707075)
* **E-mail:** [anaalves.dscience@gmail.com](mailto:anaalves.dscience@gmail.com)

---

<p align="center">
  <b>Ciência de Dados aplicada à transformação de dados em decisões.</b>
</p>
