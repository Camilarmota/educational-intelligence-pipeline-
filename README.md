# 🧠 Educational Intelligence Pipeline

**From Raw Data to Strategic Insights (SQL + Python + Power BI)**

---

## 🎯 Objetivo

Este projeto tem como objetivo analisar fatores que impactam o desempenho acadêmico de estudantes, identificando padrões, desigualdades e alunos em risco, a fim de apoiar decisões estratégicas na área educacional.

---

## 📊 Dataset

* UCI Student Performance Dataset

O dataset contém informações sobre estudantes, incluindo:

* Notas em matemática, leitura e escrita
* Gênero
* Nível de educação dos pais
* Participação em curso preparatório
* Outras variáveis socioeconômicas

---

## 🏗️ Arquitetura do Projeto

```
Raw Data → SQL (Staging) → SQL (Analytics) → Python (EDA) → Dashboard → Insights
```

---

## ⚙️ Tecnologias Utilizadas

* SQL (modelagem, limpeza e análise de dados)
* Python (Pandas, Matplotlib, Seaborn)
* Power BI
* Excel (análises complementares)

---

## 📁 Estrutura do Projeto

```
educational-intelligence-pipeline/
│
├── data/
│   ├── raw/
│   ├── processed/
│   └── external/
│
├── sql/
├── notebooks/
├── scripts/
├── dashboards/
├── reports/
└── docs/
```

---

## 🔄 Pipeline de Dados

1. Coleta de dados (CSV público)
2. Armazenamento em banco de dados (SQLite/PostgreSQL)
3. Limpeza e padronização (SQL)
4. Criação de métricas e indicadores (SQL)
5. Análise exploratória (Python)
6. Visualização de dados (Power BI)
7. Geração de insights e recomendações

---

## 📌 Principais KPIs

* Média geral dos alunos
* Taxa de alunos em risco
* Impacto do curso preparatório no desempenho
* Diferença de desempenho por contexto socioeconômico

---

## 🔍 Análises Realizadas

* Avaliação do impacto do curso preparatório nas notas
* Análise da influência da educação dos pais
* Identificação de alunos com baixo desempenho (alto risco)
* Comparação de desempenho entre grupos

---

## 📊 Dashboard

O dashboard interativo foi desenvolvido no Power BI e inclui:

* Visão geral de desempenho acadêmico
* Análise de fatores de impacto
* Monitoramento de alunos em risco

📁 Arquivo disponível em: `/dashboards`

---

## 💡 Principais Insights

* Alunos que participaram de cursos preparatórios apresentam melhor desempenho médio
* Existe correlação entre nível educacional dos pais e desempenho acadêmico
* Matemática apresenta maior variabilidade de notas entre os alunos
* Um grupo relevante de estudantes pode ser classificado como “alto risco”, exigindo atenção estratégica

---

## 📈 Recomendações

* Expandir o acesso a cursos preparatórios
* Criar programas de suporte para alunos em risco
* Monitorar indicadores de desempenho continuamente
* Desenvolver estratégias para reduzir desigualdades educacionais

---

## 🧾 Documentação

* Definição de métricas disponível em `/docs`
* Queries SQL documentadas na pasta `/sql`
* Análises exploratórias disponíveis em `/notebooks`

---

## 🚀 Como Executar o Projeto

1. Clonar o repositório
2. Instalar dependências:

```
pip install -r requirements.txt
```

3. Executar script de carga de dados
4. Rodar queries SQL
5. Abrir notebook de análise
6. Visualizar dashboard no Power BI

---

## 💼 Sobre este Projeto

Este projeto simula um cenário real de análise de dados em contexto educacional, cobrindo todo o ciclo analítico:

* Engenharia leve de dados
* Modelagem analítica
* Análise exploratória
* Visualização
* Geração de insights estratégicos

---

## 👩‍💻 Autor

Camila Mota
📊 Foco em Análise de Dados | SQL | Python | BI

---
