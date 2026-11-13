# Olá, eu sou o Samuel Ribeiro 👋

**Analista de Sistemas Júnior | Engenharia de Dados & Backend**
Transformo processos manuais de negócio em pipelines, APIs e dashboards que rodam sozinhos.

## Sobre mim

Graduando em Sistemas de Informação (IFMG). Há mais de 2 anos construo automação e BI dentro de uma operação real de transporte e logística (Grupo Seday).

- ⚡ Automatizei a conciliação fiscal entre sistemas corporativos, **reduzindo o ciclo de 1 semana para 1 dia**.
- 📊 Atuo com BI: Oracle SQL, Power BI, DAX e Power Query (M).
- 🎯 Foco atual: Engenharia de Dados e Backend com Java/Spring Boot.

## Tech Stack

| Área | Tecnologias |
|---|---|
| Backend | ![Java](https://img.shields.io/badge/Java-ED8B00?logo=openjdk&logoColor=white) ![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?logo=springboot&logoColor=white) ![FastAPI](https://img.shields.io/badge/FastAPI-009688?logo=fastapi&logoColor=white) |
| Dados / ETL | ![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white) ![Pandas](https://img.shields.io/badge/Pandas-150458?logo=pandas&logoColor=white) ![Airflow](https://img.shields.io/badge/Airflow-017CEE?logo=apacheairflow&logoColor=white) |
| Bancos | ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?logo=postgresql&logoColor=white) ![Oracle](https://img.shields.io/badge/Oracle-F80000?logo=oracle&logoColor=white) ![MySQL](https://img.shields.io/badge/MySQL-4479A1?logo=mysql&logoColor=white) |
| BI | ![Power BI](https://img.shields.io/badge/Power_BI-F2C811?logo=powerbi&logoColor=black) DAX · Power Query (M) · Tabular Editor |
| Infra | ![Docker](https://img.shields.io/badge/Docker-2496ED?logo=docker&logoColor=white) ![Git](https://img.shields.io/badge/Git-F05032?logo=git&logoColor=white) GitHub Actions |

## Projetos em destaque

### 🔄 Automação fiscal: Klaus Fiscal × Oracle Globus *(repositório privado)*
Pipeline de conciliação entre o Klaus Fiscal e o ERP Oracle Globus.
- **Stack:** Python, Pandas, Airflow, FastAPI, Docker
- **Arquitetura:** camadas em estilo medalhão (bruto → tratado → pronto para consumo), orquestradas por DAGs do Airflow e expostas via API FastAPI
- **Impacto:** conciliação financeira de **1 semana para 1 dia**

### 📦 [Controle de Estoque](https://github.com/Samuelriber/Controle-de-Estoque): API REST
Backend completo de controle de estoque.
- **Stack:** Java 21, Spring Boot, Spring Data JPA, MySQL 8, Bean Validation, Swagger (springdoc)
- **Arquitetura:** camadas Controller → Service → Repository, DTOs de entrada e saída e `GlobalExceptionHandler` com erros padronizados
- **Regras de negócio:** validação de limites mín/máx, integridade referencial (409 ao excluir produto com estoque) e transações com `@Transactional`

### 🦺 [Painel de Segurança do Trabalho](https://github.com/Samuelriber/painel-seguranca)
Substitui planilhas dispersas por uma aplicação com alertas de vencimento (treinamentos NR, ASOs, CNHs).
- **Stack:** Python, Streamlit, SQLite, Pandas
- **Destaques:** importação de Excel com detecção de duplicatas, KPIs e exportação CSV para Power BI

### 📐 [Tabular Editor Scripts](https://github.com/Samuelriber/tabular-editor-scripts)
Script C# que documenta automaticamente modelos Power BI (código M, medidas DAX e relacionamentos).

### 🚗 [Sistema de Agendamento de Estética Automotiva](https://github.com/Samuelriber/trabalho-final-poo)
Aplicação Java com MVC e DAO genérico (`IDAO<T>`), polimorfismo e persistência em arquivo.

## Outros projetos

- [alpa-web](https://github.com/Samuelriber/alpa-web): portal de ONG em React/TypeScript (frontend; backend Spring Boot planejado)
- [Salarios-Europa-](https://github.com/Samuelriber/Salarios-Europa-): web scraping (BeautifulSoup), análise com Pandas/Matplotlib e dashboard em Streamlit
- [Mesclando-pdfs](https://github.com/Samuelriber/Mesclando-pdfs): utilitário Python para mesclar PDFs
- [ceps](https://github.com/Samuelriber/ceps): script Python de consulta de CEPs
- [site-seday](https://github.com/Samuelriber/site-seday), [site-avapex](https://github.com/Samuelriber/site-avapex) e [BLOG-GRUPO-SEDAY](https://github.com/Samuelriber/BLOG-GRUPO-SEDAY): sites institucionais

## Contato

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?logo=linkedin&logoColor=white)](https://linkedin.com/in/samuel-ribeiro-14b780213)
[![Email](https://img.shields.io/badge/Email-D14836?logo=gmail&logoColor=white)](mailto:samuelriber16@gmail.com)
