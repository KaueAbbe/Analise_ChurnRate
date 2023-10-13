<h1 align="center"> Bem vinda(o) a Análise de Churn Rate😊 </h1>

# Churn Rate

Previsão de evasão de clientes, com tratamento e análises de dados, e criação e avaliação de modelo de Machine Learning.

| :placard: Vitrine.Dev |    [Minha Vitrine](https://cursos.alura.com.br/vitrinedev/kaueabbehausen)   |
| -------------  | --- |
| :sparkles: Nome        | **Churn Rate**
| :label: Tecnologias | Python, Data Science, Machine Learning, Storytelling, Análise Churn Rate
| :rocket: URL         | https://github.com/KaueAbbe/Challenge_ChurnRate/tree/main
| :fire: Desafio     | https://www.alura.com.br/challenges/data-science
<!-- Inserir imagem com a #vitrinedev ao final do link -->
![Twitter post - 1](https://user-images.githubusercontent.com/68445400/201387909-3af468e1-aad1-48eb-99de-02b129b35330.png#vitrinedev)



## Detalhes do projeto

![Badge em Desenvolvimento](https://img.shields.io/static/v1?label=STATUS&message=DESENVOLVIMENTO&color=<COLOR>)

<h1 align ="center"> Objetivo do Challenge: Predição de Churn Rate 🤔</h1>

Eu atuo como cientista de dados pela operadora de telecomunicações Alura Voz. Na reunião inicial com as pessoas responsáveis pela área de vendas da empresa, foi explicada a importância de se reduzir a Taxa de Evasão de Clientes, conhecido como **Churn Rate**. Basicamente, o **Churn Rate indica o quanto a empresa perdeu de receita ou clientes em um período de tempo.**

Eu sugeri, como passo inicial, a identificação de clientes que teriam uma maior chance de deixar a empresa. Para isso, expliquei que é interessante investigar algumas características de clientes ou dos planos de clientes para tentar CLASSIFICAR estas pessoas como potenciais candidatas a deixar a empresa ou não.

Assim, solicitei o conjunto de dados para começar a explorar, tratar e modelar a partir de agora. Em seguida, o foco será na otimização de cada um dos modelos com a finalidade de obter o melhor resultado para a tomada de decisão da Alura Voz.

<h1 align ="center"> Resumos das Etapas</h1>

<h2 align ="left"> Tratamento dos Dados</h2>

Realizei tratamento dos dados. Este processo contou as etapas de leitura dos dados, obtenção de informações básicas do dataset, buscando inconsistênicias como valores duplicados e faltantes. Correções foram feitas nas inconsitências encontradas. Como se trata de uma empresa brasileira foi feita a tradução dos dados do inglês para o português. Também alterei tipos de dados e criei o gasto diário do cliente. Salvei os dados tratados para utilizar no processo de análise exploratória.

* Leitura, organização e compreensão dos dados
* Análise de tipo de dados
* Procura e correção das inconsistências
* Tradução de colunas e valores
* Criação de novo arquivo json para uso futuro

<h2 align ="left"> Análise Exploratória e Explanatória</h2>

Realizei análises estatísticas descritivas e inferenciais que resultaram em análises de features para dois grupos de clientes: evasores e remanescentes. Fazendo essa análise bivariada, destaquei as diferenças dos grupos em cada feature que apresentou diferença significativa pós teste de hipótese. Criei gráficos que expõem as diferenças entre os grupos, passando por features como idade do cliente, tipo de contrato, forma de pagamento, produtos usados, gastos dos clientes. E baseado nas análises sugeri como alternativa realizar um Marketing focado no público mais velho, que incentive a troca de serviços, como trocar a internet de DSL por fibra ótica, obtenção da assinatura de TV ou Streaming. Também incentivar a troca do tipo de contrato de mensal para anual, ou criar o tipo semestral. Esses incentivos podem ser feitos a partir de descontos por um período de tempo maior que 3 meses, já que bastante cliente evade com 2 meses e em sua maioria gastam mais que os remanescentes.

* Análise da variável target, visualização da distribuição
* Análise de dados qualitativos e quantitativos
* Análise bivariada entre grupos evasores e não evasores
* Data visualization
* Testes de hipóteses
* Storytelling

<h2 align ="left"> Criação do Modelo Classificação</h2>
Realizei a criação de um modelo de classificação que classifica com 81% de Recall os clientes em evasores ou não evasores. Inicei o processo com pré-processamento dos dados, fazendo encoding, balanceamento e normalizando. Separei os dados para treinar, testar e validar o modelo. Foi criado baseline e utilizado FeatureImportances para determinar quais features importam na classificação. Seis modelos de classificação foram treinados e testados, utilizando Recall e métrica de Bussines como fator de decisão. Após, dois modelos passaram pelo processo de otimização por Hiperparâmetros, e o melhor modelo foi verificado com 81% de Recall e 6% de perda clientes evasores.

* Pré-Processamento dos Dados
* Sepração dados treino, teste e validação
* Definição de Recall e Métrica de Bussines para avaliação
* Criação de um modelo Dummy e LogisticRegresion como Baseline
* Criação de seis modelos de machine learning
* Otimização por Hiperparâmetros do melhor modelo

<h2 align ="center"> Quais bibliotecas usei durante o Challenge?</h2>

1. Tratamento: Pandas 🐼|
2. Análise Exploratória: Pandas, Numpy, scipy, StatsModels, Plotly |
3. Criação do Modelo: Pandas, Numpy, Sklearn, YellowBrick, Pickle, seaborn, matplotlib |



<h2 align ="center">Autor 🚀</h2>
<a>
<img style = "border-radius: 50%;" src = https://github.com/KaueAbbe/Analise_ChurnRate/assets/68445400/bd4b5b79-4826-4d72-91e4-5fc7532ac19b width="250px;" alt=""/>

 <sub><b></b></sub></a> 

<h4> Feito com 💙 por Kaue Hermann Abbehausen 👋🏽 
<br/> 
 
 1. Formado em Física na Universidade Federal de Uberlândia
 
 2. Mestrando em Física Estatística na Universidade de Brasília
    
 3. Aprofundando como Cientista de Dados</h4>
<h4> Entre em contato por</h4>
<div align = "center"> 
   <a href="https://www.linkedin.com/in/kaue-abbehausen-5b1922165/" target="_blank"><img src="https://img.shields.io/badge/-LinkedIn-%230077B5?style=for-the-badge&logo=linkedin&logoColor=white" target="_blank"></a> 
  <a href="https://www.instagram.com/cienciaeanimacao/" target="_blank"><img src="https://img.shields.io/badge/-Instagram-%23E4405F?style=for-the-badge&logo=instagram&logoColor=white" target="_blank"></a>
  <a href = "mailto:kaueabbehausen@hotmail.com"><img src="https://img.shields.io/badge/Microsoft_Outlook-0078D4?style=for-the-badge&logo=microsoft-outlook&logoColor=white" target="_blank"></a>
</div>
