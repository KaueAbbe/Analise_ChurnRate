
![Capa1](https://user-images.githubusercontent.com/68445400/170519891-8307709a-93d4-4e5c-8728-135b963b096d.jpg)


![Badge em Desenvolvimento](https://img.shields.io/static/v1?label=STATUS&message=CONCLUIDO&color=<COLOR>)

<h2 align ="center"> Quais bibliotecas foram usadas?</h2>
1. Para ler e tratar os dados: Pandas 🐼

<h2 align ="center"> Detalhes de Arquivos</h2>

- [X]  Arquivo **DataMining** contém a mineração de dados recebidos pela API da Alura Voz. Nele realizei:
* Leitura, organização e compreensão dos dados
* Análise de tipo de dados
* Procura e correção das inconsistências
* Tradução de colunas e valores para palavras em português
* Criação de novo arquivo json para uso futuro

<h2 align ="center"> Comentando o Processo</h2>

1. Houve um trabalho para transformar o arquivo de forma que fosse possível realizar os tratamentos necessários. Por ser um arquivo json há a necessidade
de realizar alterações para que se torne uma tabela de colunas e linhas com seus devidos valores. Esta ação foi feita utilizando método para tratar arquivos json
e criando pequenos DataFrames e os concatenando.

2. Houveram valores nos dados vieram faltando. As lacunas estavam preenchidas com espaços ou não tinha nada. Para realizar esta correção analisei os motivos que
levavam àquele valor estar vazio. Para um caso de valores faltando (caso na variável target) foi decidido que não haveria como utilizar esses valores durante as análises
e criação do modelo, por isso excluí estes valores.<br>
Para o segundo caso percebi que o motivo de estar com valor vazio devia ao fato de ser da coluna valor total gasto pelo cliente, e se tratava de um cliente que não estava
nem há mês no contrato. Para este caso alterou-se o valor vazio para zero.<br>


3. Demais ações no dataset foram traduzir as colunas e valores, feito com alteração do nome das colunas e mapeando os valores para trocar pela palavra traduzida. Após isto 
salvei o dataset corrigido para ser utilizado nas semanas 2 e 3.
<br>
