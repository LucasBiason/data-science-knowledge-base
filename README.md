# Data Science Knowledge Base

**Engenharia analítica e análise de dados documentadas a partir de prática real e projetos aplicados.**

Este repositório faz parte da iniciativa **Engineering Knowledge Base**. O objetivo não é criar um curso de Data Science, mas documentar prática contínua em análise de dados, transformando dados brutos em insights acionáveis.

O conteúdo reflete estudos aplicados, projetos reais e decisões técnicas documentadas.

---

## Sobre este repositório

Este repositório documenta minha prática contínua em análise de dados, focando em engenharia analítica, não em modelagem de Machine Learning.

**Este repositório não é:**
- Um curso de Data Science
- Material gerado automaticamente
- Um playground solto de notebooks
- Foco em modelagem de ML (isso fica no IA/ML KB)

**Este repositório é:**
- Documentação de análise de dados real
- Projetos que partem de problemas reais
- Decisões técnicas justificadas
- Base de referência para engenharia de dados

---

## Objetivo

Consolidar conhecimento sobre análise de dados através de:

- Fundamentos técnicos (NumPy, Pandas, Polars)
- Análise exploratória de dados (EDA)
- Visualização e comunicação de insights
- Projetos práticos com impacto de negócio

---

## O que você vai encontrar aqui

### Camada 1: Fundamentos (Base Técnica)

- **NumPy** - Operações numéricas e arrays
- **Pandas** - Manipulação e análise de dados
- **Polars** - Processamento de dados de alto desempenho
- **Data Cleaning** - Limpeza e preparação de dados
- **Tipos de Dados** - Compreensão de tipos e estruturas
- **Performance** - Otimização e boas práticas

### Camada 2: Análise (Pensamento Analítico)

- **EDA (Exploratory Data Analysis)** - Análise exploratória
- **Estatística Aplicada** - Estatística descritiva e inferencial
- **Visualização** - Comunicação visual de dados
- **Correlações** - Identificação de relações
- **Hipóteses** - Formulação e teste de hipóteses

### Camada 3: Projetos (Valor de Negócio)

- **Sales Analysis** - Análise de vendas
- **A/B Testing** - Testes estatísticos
- **Dashboards** - Visualizações interativas
- **Customer Segmentation** - Segmentação de clientes

---

## O que você NÃO vai encontrar

- Modelagem de Machine Learning (isso fica no IA/ML KB)
- Conteúdo gerado automaticamente
- Tutoriais genéricos
- Projetos sem contexto de negócio

---

## Estrutura

```
data-science-knowledge-base/
├── foundations/               # Base técnica
│   ├── numpy/                 # NumPy
│   ├── pandas/                # Pandas
│   ├── polars/                # Polars
│   ├── data-cleaning/         # Limpeza de dados
│   └── README.md
│
├── analysis/                  # Pensamento analítico
│   ├── eda/                   # Análise exploratória
│   ├── statistics/            # Estatística aplicada
│   ├── visualization/         # Visualização
│   └── README.md
│
├── projects/                  # Valor de negócio
│   ├── sales-analysis/        # Análise de vendas
│   ├── ab-testing/            # Testes A/B
│   ├── dashboards/            # Dashboards
│   └── README.md
│
├── docs/                      # Documentação adicional
│   └── roadmap.md
│
└── templates/                 # Templates
    └── notebook-template.ipynb
```

---

## Público-alvo

- Engenheiros de dados
- Analistas de dados
- Engenheiros de software trabalhando com dados
- Profissionais de produto interessados em análise

---

## Como este conteúdo é produzido

- **Escrita manual e incremental:** Cada notebook é escrito manualmente
- **Projetos reais:** Conteúdo baseado em problemas reais
- **Decisões documentadas:** Justificativas técnicas explícitas
- **Evolução contínua:** Conteúdo cresce ao longo do tempo

---

## Relação com o Ecossistema

Este repositório faz parte do **Engineering Knowledge Base**.

- **Pré-requisito para:** IA/ML Knowledge Base
- **Conecta com:**
  - Programming KB (algoritmos para processamento de dados)
  - IA/ML KB (análise de dados é base para ML)
- **Aplica em:**
  - Projetos de portfólio (análise de dados de vendas)
  - Hackathon Threat Modeling (análise de métricas de segurança)

---

## Como usar

### Instalação

```bash
# Clone o repositório
git clone https://github.com/LucasBiason/data-science-knowledge-base.git
cd data-science-knowledge-base

# Crie um ambiente virtual
python -m venv .venv
source .venv/bin/activate  # Linux/Mac
# ou
.venv\Scripts\activate  # Windows

# Instale as dependências
pip install -r requirements.txt
```

### Executar Notebooks

```bash
# Inicie o Jupyter
jupyter notebook

# Ou use JupyterLab
jupyter lab
```

---

## Stack Utilizada

- **Python 3.9+** - Linguagem principal
- **NumPy** - Operações numéricas
- **Pandas** - Manipulação de dados
- **Polars** - Processamento de alto desempenho
- **Matplotlib/Seaborn** - Visualização
- **Plotly** - Visualizações interativas
- **Jupyter Notebook** - Ambiente de desenvolvimento

---

## Status

**Em desenvolvimento contínuo.**

Conteúdo é adicionado incrementalmente conforme projetos e estudos avançam.

**MVP:** NumPy, Pandas, EDA e 2 projetos bem feitos (Sales Analysis, A/B Testing)

---

## Outros repositórios da Knowledge Base

- **[Engineering Knowledge Base](../engineering-knowledge-base/)** - Hub central do ecossistema
- **[Programming Knowledge Base](../programming-knowledge-base/)** - Fundamentos algorítmicos
- **[Microservices Knowledge Base](../microservices-knowledge-base/)** - Arquitetura de sistemas distribuídos
- **[IA/ML Knowledge Base](../ia-ml-knowledge-base/)** - Inteligência Artificial aplicada

---

## Licença

Este projeto está licenciado sob a [MIT License](LICENSE).

---

*Desenvolvido por Lucas Biason para consolidar conhecimentos em análise de dados e criar uma base de referência prática.*

