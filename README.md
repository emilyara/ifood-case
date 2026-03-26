# 📊 Análise de Dados de Orders

## 📌 Objetivo
Analisar um dataset de pedidos com mais de 3 milhões de registros, utilizando processamento eficiente para evitar problemas de memória.

## ⚙️ Pipeline
- Download dos dados (JSON.gz)
- Processamento em chunks
- Conversão para Parquet
- Análise exploratória

## 🚀 Como rodar

```bash
pip install -r requirements.txt
python src/data/make_dataset.py