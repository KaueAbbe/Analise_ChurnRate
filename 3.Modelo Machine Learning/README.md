![Capa3](https://user-images.githubusercontent.com/68445400/170520115-4fda6530-0a31-403c-a95a-f769ba26d833.jpg)



![Badge em Desenvolvimento](https://img.shields.io/static/v1?label=STATUS&message=DESENVOLVIMENTO&color=<COLOR>)

<h1 align ="center">Resumo dos Resultados</h1>

Realizei a criação de um modelo de classificação que classifica com 81% de Recall os clientes em evasores ou não evasores. Inicei o processo com pré-processamento dos dados, fazendo encoding, balanceamento e normalizando. Separei os dados para treinar, testar e validar o modelo. Foi criado baseline e utilizado FeatureImportances para determinar quais features importam na classificação. Seis modelos de classificação foram treinados e testados, utilizando Recall e métrica de Bussines como fator de decisão. Após, dois modelos passaram pelo processo de otimização por Hiperparâmetros, e o melhor modelo foi verificado com 81% de Recall e 6% de perda clientes evasores.

<h1 align ="center">Discussão dos Resultados</h1>

<h2 align= "Left"> 1 . Pré-processamento</h2>

O pré-processamento contou com uma sequência de passo para organizar e preparar os dados para a criação do modelo. Foram os passos:
1. Tradução de Valores binários do tipo string para binários do tipo numéricos. *sim -> 1* e *não -> 0*. Usei método *Replace do Pandas*.
2. Label Encoding dos dados qualitativos com mais de três valores. Usei o método *Get_dummies do Pandas*.
3. Balanceei os dados usando OverSampler para melhorar o treinamento e não perder dados. O método usando foi *RandomOverSampler do imblearn*
4. Normalização os dados quantitativos de gastos e tempo de contrato. Usei método *StandardScaler do Sklear*

<h2 align= "Left"> 2 . Separação de Dados </h2>

A separação de dados foi feita de forma que fosse possível realizar o treinamento do modelo, testagem e validação. Abaixo explico qual momento usei os quais dataset.
1. Dados treino foram usados em todos treinamentos de modelos, usando 80% do dataset original.
2. Dados de Teste foram usados para testar perfomace dos modelos após treinamento. Usei 15% do dataset original.
3. Dados de Validação foram usados para validar a performace do modelo final otimizado. Usei 5% do dataset original

<h2 align= "Left"> 3 . Métricas Escolhidas </h2>

A métrica escolhidas foram duas: Recall e Métrica de Bussines. Explico a escolha e funcionamento das duas abaixo.
1. **Recall:** O recall foi escolhido pois é a métrica que retonar o quão correto o modelo classifica os clientes como evasores, já que estou trabalhando numa situação em que o objetivo é a diminuição da evasão dos clientes, e por isso é importante conhecer corretamente qual cliente irá evadir.
2. **Métrica de Bussines:** Nesta métrica retorna o objetivo de diminuir a evasão dos clientes, calculando qual a perda da empresa em classificar um cliente como não evasor erroneamente. Esta métrica calcula a taxa de perda de clientes por classificar erroneamente como não evasor.


<h2 align= "Left"> 4 . Baseline e Feature Importances </h2>

Duas baselines foram criadas: DummyClassifier e LogisticRegression. Porque o dummy classifica com aleatoriedade, usei como baseline principal o LogisticRegression: Uma base 78% de Recall e 20% de perda foi criada. 

O Feature Importances, da biblioteca YellowBrick, foi usado para avaliar quais features tem maior magnitude na classificação. Retirei features com menor importância e refiz a criação do modelo LogisticRegression, e como não houve diferença utilizei o treinamento dos dados com todas as features.

<h2 align= "Left"> 5 . Treinamento de Modelos </h2

Seis modelos de classificação foram treinados e avalidados com base nas métricas: DecisionTree, AdaBoost, BernoulliNB, SVC, RandomForest e GradientBoost. Todos os modelos foram treinado usando Cross_validation, com *Cross_validation* e *KFold*.
De acordo com os resultados das métricas dois modelos seguiram para o processo de otimização: *RandomForest e GradientBoost*

<h2 align= "Left"> 6 . Otimização dos Modelos</h2

A otimização dos dois modelo escolhidos foi feita com o GridSearchCV para buscar a melhor combinação de hiperparâmetros. O processo foi feita algumas vezes. Além da extensa busca pelos hiperparâmetros, fiz a testagem da melhor combinação usando *cross_val_score*. Também usei a matriz confusão para avaliar diferenças específicas nas classificações. 
Entre os dois modelos otimizados o melhor foi **RandomForest**

<h2 align= "Left"> 7 . Validação e Salvar o modelo</h2

A validação foi feita com dados de validação, sob o modelo otimizado com Hiperparâmetros encontrado. O resultado foi salvo utilizando Pickle. 
O modelo Final contém: Recall: 81% e Perda de Cliente: 6%.


<h2 align= "Center">Conclusão</h2>

Portanto, apresentei aqui os resultados da criação de um modelo de machine learing que classifica cliente em evasores ou não, com 81% de certeza em classificar como evasor e perda de 6% classificando errado como não evasor. O processo de criação contou com diversos métodos que contribuiram no label encoding, balanceamento, normalização. Dados foram separados para treinar, testar e validar o modelo durante a criação. Com o foco em diminuir os clientes evasores, como métrica utilizei o Recall e uma métrica de Bussines criada para diminuir perdas da empresas. A otimização e a validação concluiu um modelo com 81% de certeza em classificar como evasor e perda de 6% classificando errado como não evasor 

Com este modelo a empresa pode classificar os clientes em evasores ou não evasores, contribuindo com a tomada de decisão quanto a quais clientes focar suas estratégias de diminuição de Churn. 



<h2 align ="center"> Quais bibliotecas foram usadas?</h2>
1. Para ler e tratar os dados: Pandas 🐼 |
2. Matemática: Numpy |
3. Fazer os Modelos e Avalia-los: Sklearn |
4. FeatureImportances: YellowBrick |
5. Salvar Modelo: Pickle |












