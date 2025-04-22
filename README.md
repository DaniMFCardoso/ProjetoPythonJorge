
## ProjetoPythonJorge
Grupo: Joshua, Daniela e Emely

### 📂 Projeto Apache Spark com Delta Lake
Projeto desenvolvido para demonstração do Apache Spark Local (pyspark) gravando arquivos no formato Delta Lake também de forma local criando modelo ER, imagens e códigos DDL - e da fonte de dados utilizada (dados públicos) e evidenciando e explicando, 
com exemplos, os comandos de INSERT, UPDATE e DELETE.

####  Modelo ER - Delta

![image](https://github.com/user-attachments/assets/4b98ee3d-5d8c-4b24-b5ad-2a157668a7c9)

Para o projeto nós utilizamos este modelo ER para as tabelas de carro_delta, cliente_delta e vendas_delta.

#### Comandos Utilizados

Projeto python inicializado com o UV.

Comandos utilizados para setup do ambiente:

```bash copy
uv init
uv venv
source .venv/bin/activate
uv add pyspark==3.5.3 delta-spark==3.2.0 jupyterlab ipykernel
```
[Ver arquivo de  INSERT, UPDATE e DELETE nas tabelas Delta](./spark-delta/spark-delta.ipynb)

####  Modelo ER - Iceberg

![image](https://github.com/user-attachments/assets/273b273a-1f55-424c-81b4-b1c9720504eb)

Para o projeto nós utilizamos este modelo ER para as tabelas de carro_iceberg, cliente_iceberg e vendas_iceberg.

#### Comandos Utilizados

Projeto python inicializado com o UV.

Comandos utilizados para setup do ambiente:

```bash copy
uv init
uv venv
source .venv/bin/activate
uv add pyspark==3.5.3 jupyterlab ipykernel
```

[Ver arquivo de  INSERT, UPDATE e DELETE nas tabelas Iceberg](./spark-iceberg/spark-iceberg.ipynb)
