# Guia de Análise de Dados: BigQuery

O BigQuery é o data warehouse de baixo custo, totalmente gerenciado e sem servidor (serverless) do Google para análise de dados em escala de petabytes.

### Criando um Dataset (Conjunto de Dados)
Diferente das VMs, no BigQuery começamos criando um "Dataset" para organizar nossas tabelas. Utilize o comando abaixo no Cloud Shell:

```bash
bq mk --location=US meu_conjunto_de_dados
```
Após criar o dataset, você pode carregar arquivos CSV ou JSON para iniciar suas análises utilizando **SQL padrão**.
