# Análise Exploratória de Dados — Catálogo da Netflix

## Visão Geral

Este projeto realiza uma **Análise Exploratória de Dados (Exploratory Data Analysis - EDA)** utilizando o dataset **Netflix Movies and TV Shows**.

O objetivo é responder perguntas de negócio por meio da análise de dados, aplicando técnicas de limpeza, transformação, visualização e interpretação dos resultados, simulando o fluxo de trabalho de um Analista de Dados.

---

# Objetivos

Este projeto busca responder perguntas como:

- O catálogo da Netflix é composto majoritariamente por filmes ou séries?
- Quais países produzem mais conteúdo?
- Quais são os gêneros mais frequentes?
- Como o catálogo evoluiu ao longo dos anos?
- Qual é a duração média dos filmes?
- Existem filmes com duração atípica (outliers)?
- Quais atores aparecem com maior frequência no catálogo?

---

# Dataset

**Netflix Movies and TV Shows**

Arquivo principal:

```text
data/raw/netflix_titles.csv
```

---

# Tecnologias Utilizadas

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Missingno
- Jupyter Notebook
- Git
- GitHub

---

# Estrutura do Projeto

```text
netflix-eda/
│
├── data/
│   ├── raw/
│   └── processed/
│
├── notebooks/
│
├── images/
│
├── requirements.txt
├── README.md
├── LICENSE
└── .gitignore
```

---

# Metodologia

Este projeto foi desenvolvido seguindo a metodologia **CRISP-DM (Cross Industry Standard Process for Data Mining)**.

### 1. Entendimento do Negócio

Definição dos objetivos e das perguntas de negócio.

### 2. Entendimento dos Dados

Exploração da estrutura do dataset, identificação dos tipos de dados e avaliação da qualidade das informações.

### 3. Preparação dos Dados

- Tratamento de valores ausentes
- Remoção de duplicatas
- Conversão de tipos de dados
- Criação de novas variáveis
- Engenharia de atributos

### 4. Análise Exploratória

Construção de gráficos e análises para responder às perguntas de negócio.

### 5. Comunicação dos Resultados

Interpretação dos resultados e elaboração dos principais insights.

---

# Principais Análises

Durante o projeto foram realizadas análises como:

- Limpeza e preparação dos dados
- Identificação de valores ausentes
- Tratamento de duplicatas
- Distribuição entre filmes e séries
- Evolução do catálogo ao longo dos anos
- Países com maior número de produções
- Gêneros mais frequentes
- Diretores mais presentes
- Atores com maior número de participações
- Distribuição das classificações indicativas
- Distribuição da duração dos filmes
- Identificação de outliers
- Comparação entre filmes e séries

---

# Principais Insights

A análise permitiu identificar diversos padrões no catálogo da Netflix, entre eles:

- O catálogo é composto predominantemente por filmes.
- Os Estados Unidos são o principal país produtor de conteúdo.
- Houve uma forte expansão do catálogo entre 2016 e 2019.
- Drama é um dos gêneros mais frequentes.
- A maior parte dos filmes possui duração entre 80 e 120 minutos.
- Existem poucos filmes com duração extremamente elevada, caracterizando possíveis outliers.
- O catálogo apresenta forte concentração em alguns países e gêneros.

---

# Exemplos de Visualizações

## Distribuição entre Filmes e Séries

```text
images/content_type_distribution.png
```

---

## Países com Maior Número de Produções

```text
images/top_producing_countries_corrected.png
```

---

## Distribuição da Duração dos Filmes

```text
images/movie_duration_histogram.png
```

---

## Evolução das Adições ao Catálogo

```text
images/titles_added_per_year.png
```

> Após publicar o projeto no GitHub, substitua os blocos acima pelas imagens:

```markdown
![Distribuição](images/content_type_distribution.png)

![Países](images/top_producing_countries_corrected.png)

![Duração](images/movie_duration_histogram.png)

![Crescimento](images/titles_added_per_year.png)
```

---

# Como Executar o Projeto

### 1. Clone o repositório

```bash
git clone https://github.com/SEU-USUARIO/netflix-eda.git
```

---

### 2. Entre na pasta

```bash
cd netflix-eda
```

---

### 3. Crie um ambiente virtual

Windows

```bash
python -m venv venv
```

---

### 4. Ative o ambiente virtual

PowerShell

```powershell
venv\Scripts\Activate.ps1
```

Prompt de Comando (CMD)

```cmd
venv\Scripts\activate.bat
```

---

### 5. Instale as dependências

```bash
pip install -r requirements.txt
```

---

### 6. Execute o Jupyter Notebook

```bash
jupyter notebook
```

Abra os notebooks na pasta:

```text
notebooks/
```

---

# Melhorias Futuras

Algumas evoluções possíveis para este projeto:

- Desenvolvimento de dashboard interativo utilizando Plotly.
- Construção de dashboard em Power BI.
- Desenvolvimento de sistema de recomendação de conteúdo.
- Aplicação de modelos de Machine Learning.
- Análise de sentimentos utilizando a descrição dos filmes.
- Automatização do processo de análise.

---

# Autor

**Rodrigo Furlan**

Projeto desenvolvido para compor portfólio profissional na área de **Análise de Dados**.

---

# Licença

Este projeto está licenciado sob a licença **MIT**.