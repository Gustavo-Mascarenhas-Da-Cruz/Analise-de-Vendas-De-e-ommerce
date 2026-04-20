# 📊 E-commerce Data Pipeline (ETL)

Pipeline de dados desenvolvido em Python para automatizar o processo de
Extração, Transformação e Carga (ETL) de datasets de e-commerce.

O projeto lê múltiplos arquivos CSV, trata problemas de encoding,
normaliza os dados e envia as tabelas para um banco PostgreSQL.

---

## 🚀 Tecnologias

- Python
- Pandas
- NumPy
- PostgreSQL
- SQLAlchemy
- Psycopg2
- Deep Translator
- Chardet
- Python-dotenv

---

## 🔄 Fluxo do Pipeline

CSV  
↓  
Detectar Encoding  
↓  
Limpeza de Dados  
↓  
Tradução dos datasets  
↓  
Criação de DataFrames  
↓  
Carga no PostgreSQL

---

## ▶️ Execução

1. Clone o repositório
2. Configure o arquivo `.env`
3. Instale as dependências


pip install pandas numpy sqlalchemy psycopg2 deep-translator chardet python-dotenv


4. Execute o pipeline


python pipeline_etl.py


---

## 📊 Resultado

O pipeline cria automaticamente as tabelas no banco PostgreSQL:

- clientes
- pedidos
- produtos
- vendedores
- pagamentos\_de\_pedidos
- revisoes\_de\_pedidos
- geolocalizacao
- itens_do_pedido
- traducao\_do\_nome\_da\_categoria\_do\_produto

---

## 📄 Apresentação visual

Veja a versão visual do projeto em:

`index.html`

---

## 🎯 Objetivo

Projeto desenvolvido para estudo de **Engenharia de Dados**, focando em:

- ETL
- ingestão de dados
- tratamento de encoding
- automação de pipelines
