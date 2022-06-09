![Capa3](https://user-images.githubusercontent.com/68445400/170520115-4fda6530-0a31-403c-a95a-f769ba26d833.jpg)



![Badge em Desenvolvimento](https://img.shields.io/static/v1?label=STATUS&message=DESENVOLVIMENTO&color=<COLOR>)

<h2 align ="center"> Quais bibliotecas foram usadas?</h2>
1. Para ler e tratar os dados: Pandas 🐼 |
2. Matemática: Numpy |
3. Fazer os Modelos: Sklearn |

<h2 align ="center"> Detalhes de Arquivos</h2>

- [X]  Arquivo **ModeloMachineLearning** contém a criação dos modelos de Machine Learning. Nele realizei:
* Leitura e preparação dos dados
* Modelo baseado em LinearSVC
* Modelo baseado em DecisionTree
* Aplicação de métrica para avaliação do modelo

<h2 align ="center"> Desenvolvido</h2>

Comecei realizando o balanceamento do dataset, pelo método de undersampling, e retirando os dados apenas categóricos para realizar o primeiro modelo. Posteriormente adiciono os dados quantitativos neste modelo. O primeiro modelo foi o modelo de <b>Classificação</b>, e para avalia-lo utilizei o valor da acurácia comparado ao valor da acurácia de um modelo base, Dummy.

<div div style="display: inline_block"><br>
<img src="https://user-images.githubusercontent.com/68445400/171195033-39fc9e61-cd5a-4add-b882-de24ef1a8520.png" width = "500">
<img src="https://user-images.githubusercontent.com/68445400/171204087-8a5cad0f-3b18-4cec-afb7-d9ee90cff25a.png" width = "500">
</div>

Adicionei os valores quantitativos classificando os clientes com característica abaixo de determinado valor como parte do grupo de evasores e acima como parte parte do grupo permanecente. Com esta adição aos dados do modelo de classificação refiz o modelo. 

<img src ="https://user-images.githubusercontent.com/68445400/171204441-f5e5dab8-1224-401a-a1e1-562a2ae9bc0f.png" width ="750">

Após obter este resultado criei outro modelo baseado em Árvore de Decisão. Foi feita as devidas alterações no dataset para criar este modelo. Novamente utilizo a acurácia e a comparação com o Dummy para avaliar o modelo.

<img src="https://user-images.githubusercontent.com/68445400/171205124-145272b4-5ee8-40f1-ba21-e00bb694effa.png" width = "750">

<h2 align ="center"> Conclusão</h2>

* O modelo Dummy usado como base para aceitar nosso modelo teve uma taxa de acerto de 50.25%.
* O modelo baseado no LinearSVC com criação de grupos das variáveis quantitativas obteve uma taxa de acerto de 77.77%.
* O modelo baseado no DecisionTreeClassification teve uma taxa de acerto igual a 75.53%.
<b>Com base nesses dados escolho como melhor modelo o baseado no LinearSVC, modelo de classificação</b>

<h2 align ="center"> A Desenvolver</h2>

* Irá ser realizado a otimização do modelo escolhido 
* Criação de outros modelos para comparação.





