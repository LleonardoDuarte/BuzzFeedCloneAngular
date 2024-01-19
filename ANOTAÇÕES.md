# BANCO DE DADOS

-Nosso banco de dados ficticio será no formado JSON por isso precisamos antes de fazer qualquer incremento, ir no arquivo jsconfig.json e adicionar os seguintes parametros dentro do compileOptions:
"resolveJsonModule": true,
"allowSyntheticDefaultImports": true,

- Estes arquivos servem para que voce possa importar arquivos JSON diretamente, sem estes arquivos ele nao ira entender.

- Para que possamos trazer os dados do nosso banco de dados ficticio deveremos importar o banco de dados dentro do nosso componente, assim conseguimos usar os dados do mesmo.

- Para calcular os resultados iremos usar o reduce, o reduce serve justamente para poder realizar a verificação do array atravez do primeiro elemento quantos elementos possui daquele index e quantos nao são desse index, assim conseguimos realizar o calculo facilmente.
