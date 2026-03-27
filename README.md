# Análise de impactos do teste de cupons

Teste A/B realizado entre dez/2018 e jan/2019 para medir o efeito da campanha de cupons sobre frequência de pedidos, ticket médio e receita por usuário.

## Como rodar

Instale os pacotes:
```
pip install -r requirements.txt
```

Abra `analise_resultados.ipynb` e execute todas as células na ordem. O download dos dados acontece nas primeiras células do código, o que leva alguns minutos dependendo da conexão.

Os pedidos são convertidos para Parquet via chunks e salvos localmente na pasta `data/orders` na primeira execução. Nas seguintes, o DuckDB lê direto do Parquet.

## Resultado resumido

O relatório completo está no arquivo `Analise_de_impactos_do_teste_de_cupons.pdf` na pasta `report`.
