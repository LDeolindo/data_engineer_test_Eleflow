# Data_Engineer_Test_Eleflow

Testes realizados para o processo seletivo Eleflow.

## Teste - BigData Airlines

### Pré Requisitos
Para o desenvolvimento foi utilizado a linguagem [Python](https://www.python.org/) com as bibliotecas:
* [Requests](https://requests.readthedocs.io/en/master/);
* [Json](https://docs.python.org/3/library/json.html);
* [Pandas](https://pandas.pydata.org/docs/);
* [SQLAlchemy](https://docs.sqlalchemy.org/en/14/);
* [Jupyter](https://docs.jupyter.org/en/latest/).

Obs: é fornecido o arquivo: requiriments.txt com as bibliotecas e versões utilizadas.

### Começando
Primeiramente, abra o terminal no diretório do teste e instale as dependências:
* `$ pip install -r requirements.txt`

### Executando
Para rodar a aplicação é só rodar cada arquivo do jupyter seguindo a ordem:

- Carregar os dados de VRA:
    * `de_test_csv.ipynb`

- Carregar dos dados de AIR_CIA:
    * `de_test_json.ipynb`

- Criar nova tabela aerodromos:
    * `de_test_api.ipynb`

- Criar as seguintes views:
  - Para cada companhia aérea trazer a rota mais utilizada com as seguintes informações:
    * `view_companhia_area_rota_mais_utilizada.ipynb`

  - Para cada aeroporto trazer a companhia aérea com maior atuação no ano com as seguintes informações:
    * `view_aeroporto_companhia_aerea_maior_atuacao.ipynb`

- Extras
    * `extra.ipynb`


