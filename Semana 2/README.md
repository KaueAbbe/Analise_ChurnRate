![semana2](https://user-images.githubusercontent.com/68445400/170348845-eefb26dc-6677-4649-887f-b882f8f0cd91.jpg)

![Badge em Desenvolvimento](https://img.shields.io/static/v1?label=STATUS&message=CONCLUIDO&color=<COLOR>)

<h2 align ="center"> IMPORTANTE</h2>
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
<h2 align ="center"> Apresentação dos Resultados</h2>

<h3 align= "center">Gráficos das variáveis Qualitativas</h3>

Logo de início foi feito vários testes estatísticos de Chi Quadrado para todas as variáveis quantitativas com intuito de
averigurar se havia diferença entre os grupos que evadiram e que não evadiram.Todos os testes estatísticos tem 99% de confiança.Assim separou-se quais as variáveis que eram significativa para 
compreender a evasão dos clientes. À essas variáveis foram feitas análises visuais com gráficos de barras para compreender qual era o comportamento de diferença entre os grupos evasores e permanecentes, além de visualizar qual padrão especifício do grupo evasor.<br>
  As variáveis significativas foram: <b>Ter mais de 65 anos, ter parceiro, ter dependencia, tipo de contrato, ter ou não fatura online, método de pagamento,
  qual o serviço de internet, assinatura de tv e assinatura de filme.</b>
  
  <br> Para fazer of gráficos busquei responder a mesma pergunta: <i>o que os evases mais fazem ou deixam de fazer?</i><br>Os resultados e conclusões estão destacadas nos gráficos apresentados abaixo.

<div align= "center">
  
1.
![Diferença entre idosos e Jovens para grupos sim e não](https://user-images.githubusercontent.com/68445400/170505087-381b33e1-18d4-4f84-9b58-2bab412d1f8e.png)
  
2.
![Diferença entre ter ou não parceiro para grupos sim e não](https://user-images.githubusercontent.com/68445400/170505127-a551bf2e-a628-4053-a017-66531a7fcd02.png)
  
3.
![Diferença entre ter ou não dependencia para grupos sim e não](https://user-images.githubusercontent.com/68445400/170505233-195e33c2-005e-44df-96a7-fe19cf8d0c9c.png)
  
4.
![Diferença entre Tipo de Contrato para grupos sim e não em porcentagem](https://user-images.githubusercontent.com/68445400/170505160-5e09b6c5-5be9-4831-93a2-4ab1778ca725.png)
  
5.
![Diferença entre ter ou não fatura online para grupos sim e não](https://user-images.githubusercontent.com/68445400/170505310-7bec0035-d010-4580-a3c6-bd6270006174.png)
  
6.
![Diferença entre os grupos para os métodos de pagamento](https://user-images.githubusercontent.com/68445400/170505558-063fbc81-e25e-4974-9801-9f9b2e83db69.png)
  
7.
![Diferença entre os grupos para os serviço de internet](https://user-images.githubusercontent.com/68445400/170509675-b06dfa56-21d5-4981-8758-23c5f2d35679.png)

  
8.
![Diferença entre os grupos para assinatura de Streaming](https://user-images.githubusercontent.com/68445400/170505646-caee2f53-9cc1-4046-b8fe-15fd8d2cad5f.png)
  
9.
![Diferença entre os grupos para assinatura de TV](https://user-images.githubusercontent.com/68445400/170505655-629915a0-c5fe-4540-8738-652ace9c7fc3.png)
  
</div>

<h3 align= "center">Gráficos das variáveis Quantitativas</h3>

Para as variáveis quantitativas busquei entender a faixa de concentração dos grupos, e com isto compreender qual o comportamento dos clientes e identificar as diferenças e semelhanças. Neste momento apenas foi feito um teste estatístico não paramétrico, o de mann-whitney, para assegurar que não havia igualdade no valor das médias de gastos diários para os dois grupos.. E, como o valor dos gastos diários foi calculado a partir do gasto mensal assegurou-se também a diferença para a média do gasto mensal

<div align = "center">
  
  1.
  ![Distribuição das contagens por meses de contrato para grupos](https://user-images.githubusercontent.com/68445400/170511817-3fa32c0c-215f-4bf0-8a98-be4e85f4539d.png)

  2.
  ![Distribuição das contagens por Gasto Mensal de contrato para grupos](https://user-images.githubusercontent.com/68445400/170511848-81ef0ccb-7959-401b-af8d-e39617a098f0.png)

  3.
  ![Distribuição das contagens por Gasto Total de contrato para grupos](https://user-images.githubusercontent.com/68445400/170511870-222032c2-201d-4c12-88b1-feadc28a1841.png)

  4.
  ![Distribuição das contagens por Gasto Diário de contrato para grupos](https://user-images.githubusercontent.com/68445400/170511887-1ce838bf-dd1b-495e-855a-21af3e9224f8.png)

  </div>

<h2 align= "center">Conclusão</h2>

Portanto, apresentei aqui os resultados da minha análise exploratória quanto ao comportamento dos clientes no grupo de evasore e no grupo de permanecentes, destacando
a diferença entre esses dois e priorizando a compreensão do comportamento do grupo evasor. Os evasores, em sua maioria, são idosos, que não possuem parceiros nem dependencias. O tipo de contrato é mensal, pagamento por transferência bancária e que possuem fatura online, com serviço de internet de fibra óptica. Em sua maioria, também são clientes que não assinam filmes e serviço de streaming.<br> O comportamento dos evasores é permanecer pouco tempo na AluraVoz, tem média de gasto diário de 2,5, maior que o grupo permanecente. E por consequência tem baixo gasto total.

<h2 align ="center">Referências e leituras</h2>

* Teste Chi Quadrado: https://sosestatistica.com.br/teste-chi-quadrado-pearson/
* Teste Mann-Whitney: http://www.inf.ufsc.br/~vera.carmo/Testes_de_Hipoteses/Testes_nao_parametricos_Mann-Whitney.pdf
* Documentação Plotly: https://plotly.com/python/bar-charts/
* Artigo Alura | Ambientes Virtuais: https://www.alura.com.br/artigos/ambientes-virtuais-em-python

