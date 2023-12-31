# Projeto Análise de Dados de Vendas e Lucro

Este projeto consiste em uma análise de um conjunto de dados de uma empresa contendo informações de vendas e lucro, classificadas por segmento de mercado e país/região. Os dados foram obtidos no Kaggle e podem ser encontrados aqui [Kaggle](https://www.kaggle.com/datasets/atharvaarya25/financials/code).

# Objetivo do Projeto

O objetivo deste projeto é realizar o tratamento dos dados, garantindo que estejam limpos e prontos para análise, e, em seguida, responder a várias perguntas importantes relacionadas às vendas e lucro. Algumas das principais questões que buscamos responder incluem:

* Como as vendas e o lucro evoluíram ao longo do tempo?
* Qual é o produto mais vendido?
* Qual produto gera o maior lucro médio?
* Quais segmentos de mercado têm as maiores vendas?
* Qual é o lucro médio por segmento?
* Quais países ou regiões têm as maiores vendas?
* Qual é o produto mais vendido em cada segmento?

# Tratamento dos Dados
Durante o tratamento dos dados, foram realizadas as seguintes ações:

Verificação detalhada das colunas em busca de possíveis erros.
Remoção de espaços nos nomes das colunas, símbolos como '$' e '-'.
Conversão dos tipos de dados para inteiros, tornando-os adequados para análise numérica.

# Dicionário

| Coluna             | Descrição                                                  |
|--------------------|------------------------------------------------------------|
| `Segment`          | O segmento de mercado ao qual o produto pertence.         |
| `Country`          | O país ou região onde as vendas ocorreram.                |
| `Product`          | O nome do produto.                        |
| `Discount Band`    | A faixa de desconto aplicada ao produto.                  |
| `Units Sold`       | O número de unidades vendidas do produto.                 |
| `Manufacturing Price` | O preço de fabricação do produto.                        |
| `Sale Price`       | O preço de venda do produto.                               |
| `Gross Sales`      | As vendas brutas, ou seja, o total de vendas antes de descontos. |
| `Discounts`        | O valor total dos descontos aplicados.                     |
| `Sales`            | As vendas líquidas após a aplicação de descontos.          |
| `COGS`             | O custo dos produtos vendidos (Cost of Goods Sold).       |
| `Profit`           | O lucro obtido com as vendas.                              |
| `Date`             | A data da transação de venda.                              |
| `Month Number`     | O número do mês da transação.                              |
| `Month Name`       | O nome do mês da transação.                                |
| `Year`             | O ano da transação.                                       |


# Dependências
Este projeto requer as seguintes bibliotecas Python:

* Pandas
* Numpy
* Matplotlib
* Seaborn

# Resultados e Conclusões
Os resultados e conclusões desta análise podem ser encontrados no notebook de análise de dados. Lá, você encontrará gráficos e informações detalhadas sobre as questões levantadas.

# Licença
Este projeto está sob a licença Database Contents License (DbCL).

# Contato
Se você tiver alguma dúvida ou comentário sobre este projeto, sinta-se à vontade para entrar em contato através do meu e-mail: suelymesssias@gmail.com









