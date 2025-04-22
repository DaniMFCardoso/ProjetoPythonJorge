## Projeto Python Jorge
**Grupo:** Joshua, Daniela e Emely

### 📂 Projeto Apache Spark com Delta Lake

Projeto desenvolvido para demonstração do Apache Spark local (PySpark), gravando arquivos no formato **Delta Lake** de forma local. O projeto contempla:

- Criação de modelo entidade-relacionamento (ER),
- Geração de imagens e códigos DDL,
- Uso de fonte de dados públicos,
- Evidenciação e explicação, com exemplos, dos comandos `INSERT`, `UPDATE` e `DELETE`.

#### 🗂️ Modelo ER - Delta

![Modelo ER - Delta](https://github.com/user-attachments/assets/4b98ee3d-5d8c-4b24-b5ad-2a157668a7c9)

Para o projeto, utilizamos este modelo ER para as seguintes tabelas:

- `carro_delta`
- `cliente_delta`
- `vendas_delta`

#### ⚙️ Comandos Utilizados

O projeto Python foi inicializado com o gerenciador **uv**.

Comandos utilizados para configurar o ambiente:

```bash
uv init
uv venv
source .venv/bin/activate
uv add pyspark==3.5.3 delta-spark==3.2.0 jupyterlab ipykernel
```
[Ver arquivo de  INSERT, UPDATE e DELETE nas tabelas Delta](https://github.com/DaniMFCardoso/ProjetoPythonJorge/blob/main/spark-delta/spark-delta-lake.ipynb)

#### 🗂️ Modelo ER - Iceberg

![Modelo ER - Iceberg](https://github.com/user-attachments/assets/273b273a-1f55-424c-81b4-b1c9720504eb)

Para o projeto, utilizamos este modelo ER para as seguintes tabelas:

- `carro_iceberg`
- `cliente_iceberg`
- `vendas_iceberg`

#### ⚙️ Comandos Utilizados

O projeto Python foi inicializado com o gerenciador **uv**.

Comandos utilizados para configurar o ambiente:

```bash
uv init
uv venv
source .venv/bin/activate
uv add pyspark==3.5.3 jupyterlab ipykernel
```

[Ver arquivo de  INSERT, UPDATE e DELETE nas tabelas Iceberg](https://github.com/DaniMFCardoso/ProjetoPythonJorge/blob/main/spark-iceberg/spark-iceberg.ipynb)
