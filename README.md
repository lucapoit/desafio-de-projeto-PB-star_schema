# Desafio de Projeto - Modelando um Dashboard de E-commerce com Power BI Utilizando Fórmulas DAX

Este projeto tem como objetivo entender como modelar usando o STAR SCHEMA no Power BI. Seguindo os passos da instrutura, conclui a criação desse modelo.

## Estrutura do Projeto

1. **Importação dos Dados** 
2. **Transformação e criação de tabelas** Partindo da Tabela Financials, que está escondida no modelo, separamos os dados em uma tabela fato e 4 tabela dimensões para criar o modelo.
3. **Criação da tabela Calendário:** Usando a função CALENDAR(MIN(F_Vendas[Date]),MAX(F_Vendas[Date]))

## Tecnologias Utilizadas

- **Power BI**

## Resultado Final

O esquema foi criado da maneira indicada na sessão "entendendo o Desafio".
Menciono por acreditar que algumas inconcsistências foram mantidas, como a relação entre D_Produto_Detalhes e F_Vendas e uma relação many-to-many entre D_Descontos e F_Vendas.

## Contribuição

Este projeto foi desenvolvido como parte de um exercício educacional. Fique à vontade para sugerir melhorias ou utilizar como base para seus próprios projetos.
