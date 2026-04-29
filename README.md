# 🧠 Educational Intelligence Pipeline

**From Raw Data to Strategic Insights (SQL + Python + Power BI)**

🇧🇷 Portuguese version below ↓

---

## 🎯 Objective

This project analyzes the key factors that influence students' academic performance, identifying patterns, inequalities, and at-risk students to support data-driven decision-making in the education sector.

---

## 📊 Dataset

* UCI Student Performance Dataset

The dataset includes:

* Scores in math, reading, and writing
* Gender
* Parental level of education
* Test preparation course participation
* Socioeconomic-related variables

---

## 🏗️ Project Architecture

```text id="arch_en"
Raw Data → SQL (Staging) → SQL (Analytics) → Python (EDA) → Dashboard → Insights
```

---

## ⚙️ Technologies

* SQL (data cleaning, transformation, and analysis)
* Python (Pandas, Matplotlib, Seaborn)
* Power BI
* Excel (support analysis)

---

## 📁 Project Structure

```text id="struct_en"
educational-intelligence-pipeline/
│
├── data/
├── sql/
├── notebooks/
├── scripts/
├── dashboards/
├── reports/
└── docs/
```

---

## 🔄 Data Pipeline

1. Data collection (public CSV dataset)
2. Data storage in a relational database (SQLite/PostgreSQL)
3. Data cleaning and transformation (SQL)
4. Feature engineering and metric creation (SQL)
5. Exploratory Data Analysis (Python)
6. Data visualization (Power BI)
7. Insights generation and recommendations

---

## 📌 Key KPIs

* Average student performance score
* Percentage of at-risk students
* Impact of test preparation course
* Performance gap across socioeconomic factors

---

## 🔍 Analysis

* Impact of test preparation on performance
* Influence of parental education level
* Identification of low-performing (at-risk) students
* Performance comparison across different groups

---

## 📊 Dashboard

An interactive dashboard was built using Power BI, including:

* Overall performance overview
* Impact factor analysis
* At-risk student monitoring

📁 Available in: `/dashboards`

---

## 💡 Key Insights

* Students who completed test preparation courses tend to achieve higher average scores
* There is a correlation between parental education level and student performance
* Math shows the highest variability among subjects
* A significant portion of students can be classified as "at risk", requiring targeted intervention

---

## 📈 Recommendations

* Expand access to test preparation programs
* Develop targeted support for at-risk students
* Continuously monitor performance indicators
* Implement strategies to reduce educational inequalities

---

## 🧾 Documentation

* Metric definitions available in `/docs`
* SQL queries documented in `/sql`
* Exploratory analysis available in `/notebooks`

---

## 🚀 How to Run

1. Clone the repository
2. Install dependencies:

```bash id="run_en"
pip install -r requirements.txt
```

3. Run data loading scripts
4. Execute SQL queries
5. Open the analysis notebook
6. Explore the dashboard in Power BI

---

## 💼 About the Project

This project simulates a real-world data analytics workflow in an educational context, covering the full data lifecycle:

* Data ingestion and preparation
* Analytical modeling
* Exploratory analysis
* Data visualization
* Strategic insights generation

---

## 👩‍💻 Author

Camila Mota
Data Analytics | SQL | Python | Business Intelligence

---

# 🇧🇷 Versão em Português

---

## 🎯 Objetivo

Este projeto analisa os principais fatores que influenciam o desempenho acadêmico dos estudantes, identificando padrões, desigualdades e alunos em risco, com o objetivo de apoiar a tomada de decisão baseada em dados na área educacional.

---

## 📊 Dataset

* UCI Student Performance Dataset

O dataset inclui:

* Notas em matemática, leitura e escrita
* Gênero
* Escolaridade dos pais
* Participação em curso preparatório
* Variáveis socioeconômicas

---

## 🏗️ Arquitetura do Projeto

```text id="arch_pt"
Dados Brutos → SQL (Staging) → SQL (Analytics) → Python (EDA) → Dashboard → Insights
```

---

## ⚙️ Tecnologias

* SQL (limpeza, transformação e análise de dados)
* Python (Pandas, Matplotlib, Seaborn)
* Power BI
* Excel (análises complementares)

---

## 📁 Estrutura do Projeto

```text id="struct_pt"
educational-intelligence-pipeline/
│
├── data/
├── sql/
├── notebooks/
├── scripts/
├── dashboards/
├── reports/
└── docs/
```

---

## 🔄 Pipeline de Dados

1. Coleta de dados (dataset público em CSV)
2. Armazenamento em banco de dados (SQLite/PostgreSQL)
3. Limpeza e transformação dos dados (SQL)
4. Criação de métricas e indicadores (SQL)
5. Análise exploratória (Python)
6. Visualização de dados (Power BI)
7. Geração de insights e recomendações

---

## 📌 Principais KPIs

* Média geral dos alunos
* Percentual de alunos em risco
* Impacto do curso preparatório no desempenho
* Diferença de desempenho por fatores socioeconômicos

---

## 🔍 Análises

* Impacto do curso preparatório no desempenho
* Influência da escolaridade dos pais
* Identificação de alunos com baixo desempenho (em risco)
* Comparação de desempenho entre grupos

---

## 📊 Dashboard

Dashboard interativo desenvolvido no Power BI com:

* Visão geral do desempenho acadêmico
* Análise de fatores de impacto
* Monitoramento de alunos em risco

📁 Disponível em: `/dashboards`

---

## 💡 Principais Insights

* Alunos que fizeram curso preparatório apresentam melhor desempenho médio
* Existe correlação entre escolaridade dos pais e desempenho acadêmico
* Matemática apresenta maior variabilidade de notas
* Um grupo relevante de alunos pode ser classificado como “em risco”

---

## 📈 Recomendações

* Expandir o acesso a cursos preparatórios
* Criar programas de suporte para alunos em risco
* Monitorar continuamente os indicadores
* Desenvolver estratégias para reduzir desigualdades educacionais

---

## 🧾 Documentação

* Definição de métricas disponível em `/docs`
* Queries SQL documentadas na pasta `/sql`
* Análises exploratórias disponíveis em `/notebooks`

---

## 🚀 Como Executar

1. Clonar o repositório
2. Instalar dependências:

```bash id="run_pt"
pip install -r requirements.txt
```

3. Executar scripts de carga de dados
4. Rodar queries SQL
5. Abrir notebook de análise
6. Visualizar dashboard no Power BI

---

## 💼 Sobre o Projeto

Este projeto simula um fluxo real de análise de dados no contexto educacional, cobrindo todo o ciclo analítico:

* Ingestão e preparação de dados
* Modelagem analítica
* Análise exploratória
* Visualização
* Geração de insights estratégicos

---

## 👩‍💻 Autor

Camila Mota
Análise de Dados | SQL | Python | Business Intelligence

---
