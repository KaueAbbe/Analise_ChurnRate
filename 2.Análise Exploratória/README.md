
![Capa2](https://user-images.githubusercontent.com/68445400/170519710-c8ad6c3e-e359-4465-b47c-a74ff6ec2a67.jpg)

![Badge em Desenvolvimento](https://img.shields.io/static/v1?label=STATUS&message=CONCLUIDO&color=<COLOR>)


<h1 align ="center">Resumo dos Resultados</h1>

Realizei análises estatísticas descritivas e inferenciais que resultaram em análises de features para dois grupos de clientes: evasores e remanescentes. Fazendo essa análise bivariada, destaquei as diferenças dos grupos em cada feature que apresentou diferença significativa pós teste de hipótese. Criei gráficos que expõem as diferenças entre os grupos, passando por features como idade do cliente, tipo de contrato, forma de pagamento, produtos usados, gastos dos clientes. E baseado nas análises sugeri como alternativa realizar um Marketing focado no público mais velho, que incentive a troca de serviços, como trocar a internet de DSL por fibra ótica, obtenção da assinatura de TV ou Streaming. Também incentivar a troca do tipo de contrato de mensal para anual, ou criar o tipo semestral. Esses incentivos podem ser feitos a partir de descontos por um período de tempo maior que 3 meses, já que bastante cliente evade com 2 meses e em sua maioria gastam mais que os remanescentes.


<h1 align ="center">Discussão dos Resultados</h1>

De início, analisei a quantidade de dados na variáveis target para verificar se haviam dados suficientes para realizar análises estatísticas, e a quantidade de dados possibilitou continuar com as análises. 
Primeiro realizei testes de hipótese para cada feature, visando descubrir quais features apresentavam diferenças significativas entre os grupos evasor e remanescente. Os teste tiverem confiança de 99%.

Listei as features que apresentavam diferenças e realizei análises dessas features. As variáveis significativas foram: <b>Ter mais de 65 anos, ter parceiro, ter dependencia, tipo de contrato, ter ou não fatura online, método de pagamento, qual o serviço de internet, assinatura de tv e assinatura de filme.</b>


<h2 align= "Left"> 1 . Data Visualization de features Qualitativas</h2>

A visualização de dados foi feita com gráficos de barras contendo a porcentagem de clientes nas categorias de cada feature. O objetivo foi compreender as diferenças dos grupos e visualizar qual o comportamento de cada grupo. 

  <br> Para fazer of gráficos busquei responder a mesma pergunta: <i>o que os evasores mais fazem ou deixam de fazer?</i><br>Os resultados e alternativas estão destacadas nos gráficos apresentados abaixo.

<div align= "left">
  
1. Alternativa é realizar um Marketing focado neste grupo

![Diferença entre idosos e Jovens para grupos sim e não](https://github.com/KaueAbbe/Challenge_ChurnRate/assets/68445400/b082e54a-b93e-4a72-ab35-62428d98935e)
  
2.

![Diferença entre ter ou não parceiro para grupos sim e não](https://github.com/KaueAbbe/Challenge_ChurnRate/assets/68445400/07109b88-ce81-4c2f-9633-7b10456c0ed4)
  
3.
![Diferença entre ter ou não dependencia para grupos sim e não](https://github.com/KaueAbbe/Challenge_ChurnRate/assets/68445400/19e5a970-d62d-4dc1-9f69-822bf74726c7)

  
4. Fazer um processo para que os cliente mudem o tipo de contrato pode reter os clientes por mais tempo.

![Diferença entre Tipo de Contrato para grupos sim e não em porcentagem](https://github.com/KaueAbbe/Challenge_ChurnRate/assets/68445400/c9f9ab3e-298a-435c-a636-db6b5ca0418f)
  
5.
![Diferença entre ter ou não fatura online para grupos sim e não](https://github.com/KaueAbbe/Challenge_ChurnRate/assets/68445400/a89f0a36-7992-42bc-bc6f-6d60e3639105)

  
6. Pode ser feito um incentivo para os clientes utilizarem outros métodos de pagamentos

![Diferença entre os grupos para os métodos de pagamento](https://github.com/KaueAbbe/Challenge_ChurnRate/assets/68445400/ab5c8df1-7a23-497e-8525-8b9bbf8e13a9)

  
7. Pode ser realizado um incentivo para que clientes troque o serviço de internet por um mais atual

![Diferença entre os grupos para os serviço de internet](https://github.com/KaueAbbe/Challenge_ChurnRate/assets/68445400/4c7703e5-9057-4881-84c8-d5248020628c)

8. Incentivo para o cliente se tornar assinante de TV

![Diferença entre os grupos para assinatura de TV](https://github.com/KaueAbbe/Challenge_ChurnRate/assets/68445400/bdc9a774-d360-474c-8925-643bc84f87d5)

  
9.Incentivo para o cliente se tornar assinante de Streaming

![Diferença entre os grupos para assinatura de Streaming](https://github.com/KaueAbbe/Challenge_ChurnRate/assets/68445400/f6d5560e-e81e-48cc-bd75-d8fd8a53e139)
  
</div>


<h2 align= "Left"> 2. Visualização de Dados de Features Quantitativas</h2>

Analisando features quantitativas o pensamento foi analisar a distribuição da variável, e separar os clientes quanto os quartis, desse jeito obtendo as concentrações dos clientes. Neste momento apenas foi feito um teste estatístico não paramétrico, o de mann-whitney, para assegurar que não havia igualdade no valor das médias de gastos diários para os dois grupos. E, como o valor dos gastos diários foi calculado a partir do gasto mensal assegurou-se também a diferença para a média do gasto mensal.

<div align = "left">
  
  1. Incentivo de permanência, como desconto no primeiro semestre ou trimestre.
  
  ![Distribuição das contagens por meses de contrato para grupos](https://github.com/KaueAbbe/Challenge_ChurnRate/assets/68445400/4dae9d42-4790-4e72-a04a-29b1753073e9)

  2. Criar um pacote de desconto
  
  ![Distribuição das contagens por Gasto Mensal de contrato para grupos](https://github.com/KaueAbbe/Challenge_ChurnRate/assets/68445400/4b188f32-ba24-4869-9851-0d3738d3ae57)
  3.
  
  ![Distribuição das contagens por Gasto Total de contrato para grupos](https://github.com/KaueAbbe/Challenge_ChurnRate/assets/68445400/914ab138-a538-4c5e-ab78-ff7befd12419)

  4.Criar um pacote de desconto
  
  ![Distribuição das contagens por Gasto Diário de contrato para grupos](https://github.com/KaueAbbe/Challenge_ChurnRate/assets/68445400/36c532e6-83de-4c6e-b034-30774c90617e)

  </div>

<h2 align= "Center">Conclusão</h2>

Portanto, apresentei aqui os resultados da minha análise exploratória quanto ao comportamento dos clientes no grupo de evasores e no grupo de remanescente, destacando
a diferença entre esses dois e priorizando a compreensão do comportamento do grupo evasor. Os evasores, em sua maioria, são idosos, não possuem parceiros nem dependencias. O tipo de contrato é mensal, pagamento por transferência bancária e que possuem fatura online, com serviço de internet de DSL. Em sua maioria, também são clientes que não assinam filmes e serviço de streaming.<br> O comportamento dos evasores é permanecer pouco tempo na AluraVoz, tem média de gasto diário de 2.5, maior que o grupo remanescente. E por consequência tem baixo gasto total.

Como alternativa podemos realizar um Marketing focado no público mais velho, que incentive a troca de serviços, como trocar a internet de DSL por fibra ótica, obtenção da assinatura de TV ou Streaming. Também incentivar a troca do tipo de contrato de mensal para anual, ou criar o tipo semestral. Esses incentivos podem ser feitos a partir de descontos por um período de tempo maior que 3 meses, já que bastante cliente evade com 2 meses e em sua maioria gastam mais que os remanescentes.


<h1 align ="center">Detalhes do Notebook</h1>

<h2 align ="center">Aviso do Notebook</h2>
Os gráficos feitos aqui são da biblioteca interativa Plotly, e por este motivo os gráficos não aparecem se for visto no Github.<br> 
<b>Para analisar os gráficos coloquei eles em ordem logo abaixo no README, ou você pode abrir o notebook pelo Colab, clique em Runtime e depois em runall. Todos os gráficos irão aparecer, junto com os códigos.</b>

<h2 align ="center"> Quais bibliotecas foram usadas?</h2>
1. Leitura dos Dados: Pandas 🐼
2. Testes estatísticos: Numpy, Scipy e StatsModels
3. Visualização dos Dados: Plotly

<h2 align ="center"> Detalhes de Arquivos</h2>

- [X]  Arquivo **Análise Exploratória** contém as análises das variáveis. Nele realizei:
* Análise da variável target, visualização da distribuição
* Comparação entre grupos de clientes evasores e não evasores
* Visualização dos dados

<h2 align ="center"> Comentando o Processo</h2>

1. A leitura do arquivo não houve problema, pois já havia sido tratado e salvo para que fosse lido nesta semana e na próxima.

2. Foi feito de início vários testes estatísticos de Chi Quadrado para todas as variáveis quantitativas com intuito de
averigurar se havia diferença entre os grupos que evadiram e que não evadiram. Assim separou-se quais as variáveis que eram significativa para 
compreender a evasão dos clientes.<br>

3. Sabendo quais variáveis informavam sobre as evasões foi realizando um estudo visual(gráficos) com foco em averiguar qual grupo tinha mais ou menos de algo e quanto era
a diferença entre os grupos.

4. Para as variáveis qualitativas foi feito histogramas para compreender o comportamento dos clientes dos dois grupos e verificar qual era 
o padrão dos gastos dos clientes.
<br>

<h2 align ="center">Referências e leituras</h2>

* Teste Chi Quadrado: https://sosestatistica.com.br/teste-chi-quadrado-pearson/
* Teste Mann-Whitney: http://www.inf.ufsc.br/~vera.carmo/Testes_de_Hipoteses/Testes_nao_parametricos_Mann-Whitney.pdf
* Documentação Plotly: https://plotly.com/python/bar-charts/
* Artigo Alura | Ambientes Virtuais: https://www.alura.com.br/artigos/ambientes-virtuais-em-python

