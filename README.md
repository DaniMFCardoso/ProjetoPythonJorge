
ProjetoPythonJorge
Grupo: Joshua, Daniela e Emely

📂 Projeto Apache Spark com Delta Lake
Projeto desenvolvido para demonstração do Apache Spark Local (pyspark) gravando arquivos no formato Delta Lake também de forma local criando modelo ER, imagens e códigos DDL - e da fonte de dados utilizada (dados públicos) e evidenciando e explicando, 
com exemplos, os comandos de INSERT, UPDATE e DELETE.

Modelo ER

![image](https://github.com/user-attachments/assets/2db97451-4e3b-4d59-a299-eb615a818200)

Para o projeto nós utilizamos este modelo ER para as tabelas de carro_spark, cliente_spark e vendas_spark.

Comandos Utilizados
Projeto python inicializado com o UV.

Comandos utilizados para setup do ambiente:

bash copy
uv init
uv venv
source .venv/bin/activate
uv add pyspark==3.5.3 delta-spark==3.2.0 jupyterlab ipykernel

