# DNC_DataAnalisys_Python_Case1 - Análise de vendas
First case from my training in Data Analisys with Python - DNC

# Case:
Cliente solicitou as seguintes informações
- Número de vendas por dia
- Número de vendas e preço médio por departamento
- Idade média dos clientes de acordo com a bandeira comprada
- Qual a renda média dos clientes que compraram no último mês

# Detalhe sobre o banco de dados:
1. Base de vendas: descrição das vendas realizadas no período de um mês
   - ID compra
   - ID canal venda
   - Bandeira
   - Data
   - Preço
   - Preço com frete
   - Nome do departamento
   - Estado
   - Cliente LOG  
2. Base de clientes: apresenta mais informações sobre os clientes
   - Cliente
   - Idade
   - Renda

- Todos os valores nulos no campo "Estado" devem ser substituídos por "MS".
- Não é aceitável que vendas tenham o campo "Preço" maior do que o campo "Preço com frete", caso haja alguma venda nesse caso, desonsiderar.


# Execução:
Foram utilizadas as bibliotecas pandas para tratamento dos dados e plotly.express para visualização

