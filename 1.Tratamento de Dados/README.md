
![Capa1](https://user-images.githubusercontent.com/68445400/170519891-8307709a-93d4-4e5c-8728-135b963b096d.jpg)


![Badge em Desenvolvimento](https://img.shields.io/static/v1?label=STATUS&message=CONCLUIDO&color=<COLOR>)

<h1 align ="center">Resumo dos Resultados</h1>

Realizei tratamento dos dados. Este processo contou as etapas de leitura dos dados, obtenção de informações básicas do dataset, buscando inconsistênicias como valores duplicados e faltantes. Correções foram feitas nas inconsitências encontradas. Como se trata de uma empresa brasileira foi feita a tradução dos dados do inglês para o português. Também alterei tipos de dados  e criei o gasto diário do cliente. Salvei os dados tratados para utilizar no processo de análise exploratória.

<h1 align ="center">Discussão dos Resultados</h1>

O tratamento de dados foi um processo de buscar inconsitências e preparar os dados para utilizar na análise exploratória e criação do modelo de classificação.

<h2 align= "Left"> 1 . Leitura e obtenção de informação</h2>

Utilizando biblioteca *Pandas* li os dados em formado json, e utilizei método *info* para obter informações básicas como: tipo de dados, valores faltantes, análise univariadas para saber como estão os dados. 

<h2 align= "Left"> 2 . Inconsistências</h2>

1. Valores duplicados: não foram encontrados
2. Valores Missing foram encontados: Os valores missing encontrados estavam vazios. Para tratar estes valores investiguei qual motivo estavam faltando, e no caso da coluna de pagamentos totais foi encontrado que não haviam valores porque os clientes tinham menos de 1 mês de contrato, e por isso alterou o valor para 0.
No caso de valores faltantes na feature Churn existiam poucos valores faltantes, por isso e porque se trata de uma feature target foram retirados os dados faltantes.
3. Tipo de dado errado: A feature pagamentos totais estava no tipo object e representava valores numéricos, então realizei a alteração de object para float.

<h2 align= "Left"> 3 . Tradução e Salvar os dados</h2>

Como as labels das features e valores estavam na língua inglesa realizei a tradução para a língua portuguesa. Desta forma a língua usada ficou na língua natural da empresa AluraVoz. Após utilizei o *Pandas* para salvar os dados para utilizar na análise exploratória e criação do modelo.

<h2 align= "Center">Conclusão</h2>

Portanto, apresentei aqui os resultados do tratamento dos dados. Foi feito a leitura e preparação do dataset, depois partindo para a compreensão dos tipos de dados e features do dataset. Realizei a investigação de tratamento de dados duplicados, nulos e faltantes, descobrindo que os dados faltantes da coluna gastos totais se dava pela pouco tempo de contrato, e retirando dados faltantes da coluna Churn. Após a tradução dos dados da língua inglesa para portuguesa salvei os dados para as próximas etapas.


<h2 align ="center"> Quais bibliotecas foram usadas?</h2>
1. Para ler, tratar e salvar os dados: Pandas 🐼



<h2 align ="center"> Algumas Transformações</h2>



<img src="https://user-images.githubusercontent.com/68445400/171190530-10913fdc-64c7-4544-94b5-10036695c48c.png" width = "750">



2.

<img src="https://user-images.githubusercontent.com/68445400/171192912-cb2e32d4-adef-4663-9344-d9ea74f7f378.png" width = "750">



3. 

<img src ="https://user-images.githubusercontent.com/68445400/171193713-cc0a6e40-58ba-467d-a30e-26a0ccc6f9f0.png" width = "750">


<br>
