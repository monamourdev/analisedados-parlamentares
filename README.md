# Análise de Dados da Câmara dos Deputados

Neste projeto, foi feita a análise de gastos e proposições dos partidos durante a legislatura 54, utilizando dados abertos de parlamentares.

## Objetivos

O objetivo central é entender o montante gasto por cada partido ao longo da legislatura 54 e determinar a quantidade real de proposições feitas por cada um. A abordagem envolve a classificação de parlamentares por partido, agregando os valores de interesse no contexto partidário.

## Dependências
Certifique-se de ter as seguintes dependências instaladas para executar o programa:

- **Biblioteca de leitura de arquivos xlsx:**
`sudo pip install xlrd`


- **Biblioteca para plotar gráficos (opcional, requer autenticação):**
`sudo pip install plotly`

- **Método de escrita em arquivos xlsx:**
`sudo pip install XlsxWriter`


## Execução
Execute o programa utilizando o seguinte comando no terminal:

`python analiseDados.py` 


## Observações
- Os dados utilizados são públicos e foram obtidos diretamente do site oficial da Câmara dos Deputados.
- O resultado da análise é disponibilizado em um arquivo xlsx.

## Insights Interessantes
- Observou-se que parlamentares tendem a aumentar a quantidade de proposições no último ano de seus mandatos.
- Os maiores gastos dos parlamentares estão associados a passagens aéreas e divulgações.
- Por outro lado, os menores gastos são destinados a capacitações e pesquisas.

