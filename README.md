# esfera-analytics-engineer-test
Teste para vaga de Analytics Engineer.

### ETL

A biblioteca Pandas foi utilizada em um notebook para realizar o ETL por meio das seguintes etapas:

1. Extração dos arquivos CSV que se encontram no diretório 'input'.
2. Limpeza, formatação e agregação dos dados para prepará-los para análise. Foram criados dois DataFrames:
    - O primeiro é um consolidado, que além de garantir a existência de chaves únicas, facilita a análise de desempenho financeiro, identificando superávit ou déficit.
    - O segundo mantém cada registro exatamente como nas tabelas de origem, permitindo análises mais detalhadas.
3. Exportação dos DataFrames resultantes para arquivos CSV.


### Análise de dados

Para demonstrar os insights, um painel foi desenvolvido utilizando o Looker Studio:
https://lookerstudio.google.com/reporting/3b7e3635-aa9c-4f89-93c7-ff3a0940915b