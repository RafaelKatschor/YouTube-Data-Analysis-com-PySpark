#  YouTube Data Analysis com PySpark


##  Funcionalidades
- Upload e leitura de arquivos CSV (`videos-stats.csv` e `comments.csv`)  
- Visualização inicial dos dados e esquemas  
- Inferência automática de tipos de dados  
- Conversão e salvamento em formato **Parquet**  
- Criação de tabelas no catálogo do Spark (`tb_videos`)  
- Consultas com **Spark SQL**  
- Integração de múltiplos datasets para análise  

##  Tecnologias utilizadas
- Google Colab  
- PySpark  
- Spark SQL  
- Formatos de dados: **CSV** e **Parquet**

##  Estrutura do Projeto

├── videos-stats.csv
├── comments.csv
├── notebooks/
│   └── youtube_analysis.ipynb
├── README.md


##  Passos principais do notebook
1. Upload dos arquivos CSV para o Colab  
2. Leitura dos dados sem e com inferência de esquema  
3. Visualização dos registros e estrutura dos dados  
4. Conversão para formato **Parquet**  
5. Criação de tabela `tb_videos` no catálogo Spark  
6. Execução de consultas SQL  
7. Análise dos comentários (`comments.csv`)  

##  Como executar
1. Clone este repositório:
   ```bash
   git clone https://github.com/seu-usuario/youtube-pyspark-analysis.git

2. Abra o notebook no Google Colab.

3. Faça upload dos arquivos videos-stats.csv e comments.csv.

4. Execute célula por célula para acompanhar o fluxo de análise.

 Objetivo
Servir como exemplo prático e didático de manipulação de grandes volumes de dados com PySpark, explorando diferentes formatos de armazenamento e consultas SQL, aplicável a cenários de análise de dados em plataformas digitais como o YouTube.


---

 

