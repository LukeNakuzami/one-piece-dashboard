# 🏴‍☠️ One Piece Dashboard

Este projeto é uma análise interativa do anime e mangá **One Piece**, com dashboards desenvolvidos em **Power BI** e tratamento de dados em **Python**. Visualize avaliações de episódios, publicações de capítulos e evolução de personagens ao longo do tempo.

---

## 🎯 Objetivo

Transformar dados públicos em um painel interativo que responda perguntas como:
- Quais os episódios mais bem avaliados?
- Quantos capítulos foram lançados por ano?
- Quando os personagens foram introduzidos na história?

---

## 🧪 Coleta e Processamento de Dados

### 📁 Fontes:

- 📊 [One Piece Characters and Chapters](https://www.kaggle.com/datasets/michau96/one-piece-characters-and-chapters)
- ⭐ [One Piece IMDB Ratings](https://www.kaggle.com/datasets/greninja1729/one-piece-imdb-ratings-and-votes)
- 📘 [Capas dos Volumes - One Piece Wiki](https://onepiece.fandom.com/pt/wiki/Capítulos_e_Volumes/Volumes)

### ⚙️ Ferramentas utilizadas:

- `pandas`, `kagglehub`, `os`, `chardet` – para detecção de encoding e conversão de CSV para Parquet
- `requests`, `BeautifulSoup` – para scraping das capas de volumes
- `Power BI` – para visualização e modelagem dos dados
- `Figma` – para prototipação do design visual

---

## 📊 Power BI

Importei os dados `.parquet` diretamente no Power BI. Como os dados já estavam limpos, o tratamento foi simples. A modelagem de dados seguiu o modelo relacional clássico com tabelas de episódios, capítulos, volumes e personagens.

---

## 🖼️ Dashboards

### 🔴 Avaliação de Episódios e Arcos

- Episódio mais bem avaliado: **485**
- Arco mais bem avaliado: **Marineford Arc**
- Episódio com menor nota: **336**
- Total de avaliações: **+2.3 milhões**

---

### 🟡 Publicações do Mangá

- Total de capítulos: **1013**
- Total de volumes analisados: **100+**
- Total de personagens introduzidos: **1295**
- Total de páginas mapeadas: **18.702**

---

## 🚀 Próximos Projetos

- 🧱 Desenvolver minha própria base de dados sobre o universo de One Piece, unificando informações de episódios, capítulos, personagens e sagas
- 🌐 Criar um dashboard interativo utilizando **Streamlit** ou **Dash**, com foco em performance, navegação por personagem e comparações entre arcos

---

## 📦 Arquivos do Projeto

Todos os arquivos do projeto estão disponíveis no pacote abaixo:

🔽 **Download completo**: [`one_piece_dashboard.zip`](one_piece_dashboard.zip)

O arquivo `.zip` contém:
- O arquivo `.pbix` do Power BI
- Arquivos `.parquet` prontos para uso
- Notebooks `.ipynb` com os scripts de coleta e conversão
- Designs exportados do Figma (`.png`)
- Prints dos dashboards e modelo de dados

---

## 👨‍💻 Autor

**Lucas Gomes** – Analista de Dados

[![LinkedIn](https://img.shields.io/badge/-LinkedIn-blue?style=flat-square&logo=linkedin)](https://www.linkedin.com/in/lucas-g-8a73aa136/)  
[![Email](https://img.shields.io/badge/-Email-red?style=flat-square&logo=gmail&logoColor=white)](mailto:lucas.azevedo.3721@gmail.com)

---

📌 Projeto sem fins lucrativos, feito de fã para fã com fins educacionais.
