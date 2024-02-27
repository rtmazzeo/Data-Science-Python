# O Projeto
Projeto de Análise Exploratória de Dados resultado do Módulo de Estatística do Bootcamp "Vem Ser Tech - Dados" - Ifood. O objetivo foi promover o desenvolvimento dos alunos em relação aos aspectos fundamentais de uma EDA. O dataset utilizado foi de um conjunto de informações resumidas sobre o número de voos pontuais, atrasados, cancelados e desviados aparecem no Relatório Mensal do Consumidor de Viagens Aéreas [https://www.kaggle.com/datasets/giovamata/airlinedelaycauses](https://www.kaggle.com/datasets/giovamata/airlinedelaycauses). Tinhamos que (i) Realizar uma análise descritiva por completo da base (Variáveis discretas e contínuas); (ii) Avaliar a distribuição de probabilidade de variáveis contínuas. Abordando os seguinte critérios: 
(i) Qualidade e Profundidade da Análise de Dados, (ii) Criatividade, (iii) Apresentação e Visualização de Dados. 

# O Dataset
Foram avaliados 1936758 Registro de Voos × 28 parâmetros

# Exploratory Data Analysis (FCCD)

1. Análise descritiva dos dados numéricos contínuos:

A análise descritiva dos parâmetros é uma etapa crucial na compreensão e interpretação dos dados relacionados ao desempenho de voos de companhias aéreas. Cada um desses parâmetros oferece insights valiosos sobre diferentes aspectos das operações de voo e do sistema de transporte aéreo como um todo. A tabela que agrega todos os parâmetros de resultados da análise oferece uma visão consolidada das principais estatísticas descritivas, permitindo uma fácil comparação e identificação de tendências e padrões nos dados. Essas informações são essenciais para tomada de decisões informadas, planejamento estratégico e melhoria contínua no setor de aviação.

<p align="center">
  <img src="https://github.com/rtmazzeo/Data-Science-Python/blob/main/projeto_estatistica/imagens/metricas.png">
</p>

2. Análise da Hora da Partida e Hora da Chegada Real e Hora da Partida Prevista. 

A análise dos dados da hora da partida e da chegada real em comparação com a hora da partida prevista é fundamental para entender e avaliar o desempenho das companhias aéreas e o funcionamento geral do sistema de transporte aéreo.

<p align="center">
  <img src="https://github.com/rtmazzeo/Data-Science-Python/blob/main/projeto_estatistica/imagens/hora_partida.png">
</p>

3. Análise da Quantidade de Voos Cancelados e Desviados 

A quantidade de voos cancelados e desviados é um indicador importante da confiabilidade do serviço prestado pelas companhias aéreas. Voos cancelados e desviados podem causar grandes transtornos para os passageiros, afetando seus planos de viagem e compromissos.

<p align="center">
  <img src="https://github.com/rtmazzeo/Data-Science-Python/blob/main/projeto_estatistica/imagens/cancelados_desviados.png">
</p>



3. Análise da Quantidade de Voos por mês, por dia e por dia da semana


A análise da quantidade de voos por mês, por dia e por dia da semana é fundamental para entender e avaliar o desempenho do sistema de transporte aéreo em termos de pontualidade e eficiência. O conjunto de dados fornecido pelo Departamento de Transportes dos Estados Unidos (DOT) e pela Bureau of Transportation Statistics (BTS) oferece uma visão abrangente do funcionamento dos voos domésticos operados por grandes companhias aéreas. Primeiramente, a análise mensal da quantidade de voos permite identificar padrões sazonais e tendências ao longo do ano.

<p align="center">
  <img src="https://github.com/rtmazzeo/Data-Science-Python/blob/main/projeto_estatistica/imagens/voo_mes.png">
</p>

<p align="center">
  <img src="https://github.com/rtmazzeo/Data-Science-Python/blob/main/projeto_estatistica/imagens/voo_dia.png">
</p>

<p align="center">
  <img src="https://github.com/rtmazzeo/Data-Science-Python/blob/main/projeto_estatistica/imagens/voo__semana.png">
</p>

4. Análise BoxPlot:

O boxplot é uma ferramenta visual poderosa para analisar a distribuição e identificar padrões em um conjunto de dados. No contexto do tempo de voo e atrasos em voos domésticos operados por grandes transportadoras aéreas nos Estados Unidos, o uso de boxplots pode oferecer insights valiosos sobre a pontualidade e os possíveis fatores que contribuem para atrasos.

**Tempo Real de Voo por Minuto, Tempo Previsto de Voo em Minuto, Tempo de Voo em Minuto:** Essas variáveis fornecem informações sobre a duração real, prevista e efetiva dos voos. O boxplot desses dados pode revelar a consistência entre o tempo previsto e o tempo real de voo, além de destacar eventuais outliers que indiquem voos excepcionalmente longos ou curtos.

<p align="center">
  <img src="https://github.com/rtmazzeo/Data-Science-Python/blob/main/projeto_estatistica/imagens/tempo_voo.png">
</p>

**Atraso na Chegada e Partida em Minutos:** Os atrasos na chegada e partida são fatores críticos na experiência do passageiro e podem ter várias causas, desde problemas técnicos até congestionamentos nos aeroportos. O boxplot dessas variáveis permite identificar a magnitude e a frequência dos atrasos, bem como distinguir entre atrasos menores e atrasos significativos que podem afetar o planejamento de viagens.

<p align="center">
  <img src="https://github.com/rtmazzeo/Data-Science-Python/blob/main/projeto_estatistica/imagens/boxplot_atraso.png">
</p>

**Tempo Gasto Taxiando Após o Voo e Antes da Decolagem:** O tempo gasto em manobras de taxiamento pode contribuir para atrasos operacionais e impactar a eficiência geral do serviço de transporte aéreo. O boxplot desses dados pode destacar padrões de tempo de taxiamento e discrepâncias entre diferentes aeroportos ou companhias aéreas.

<p align="center">
  <img src="https://github.com/rtmazzeo/Data-Science-Python/blob/main/projeto_estatistica/imagens/boxplot_tempo_taxiando.png">
</p>

**Atrasos Causados pela Companhia Aérea, Clima e Sistema de Tráfego Aéreo:** Esses são os principais fatores que contribuem para atrasos em voos comerciais. Ao plotar os atrasos atribuídos a cada uma dessas categorias em um boxplot separado, é possível avaliar a eficácia das operações da companhia aérea, bem como o impacto das condições meteorológicas e do controle de tráfego aéreo nos atrasos de voo.

<p align="center">
  <img src="https://github.com/rtmazzeo/Data-Science-Python/blob/main/projeto_estatistica/imagens/boxplot_atraso2.png">
</p>

**Atrasos Causados por Questões de Segurança e Atrasos Causados por Chegada Tardia da Aeronave Anterior:

<p align="center">
  <img src="https://github.com/rtmazzeo/Data-Science-Python/blob/main/projeto_estatistica/imagens/boxplot_atraso3.png">
</p>

Ao analisar os boxplots desses dados em conjunto, podemos obter insights sobre a pontualidade do serviço, identificar áreas de melhoria operacional e compreender melhor os fatores externos que afetam o desempenho do transporte aéreo. Essa análise informada pode ajudar a otimizar os procedimentos operacionais, melhorar a eficiência e a confiabilidade dos voos e, em última análise, aprimorar a experiência de viagem para todos os envolvidos.

5. Histograma: Ao construir um histograma , podemos visualizar a distribuição dos dados e identificar padrões e tendências significativas. 

<p align="center">
  <img src="https://github.com/rtmazzeo/Data-Science-Python/blob/main/projeto_estatistica/imagens/histograma.png">
</p>

6. Análise de Correlação

A análise de correlação é uma ferramenta estatística poderosa utilizada para entender a relação entre duas variáveis. Quando lidamos com conjuntos de dados, é crucial compreender como essas variáveis estão interconectadas. No contexto do conjunto de dados fornecido pelo Departamento de Transporte dos Estados Unidos sobre o desempenho de voos domésticos operados por grandes transportadoras aéreas, a análise de correlação pode nos oferecer insights valiosos sobre as relações entre diferentes aspectos do desempenho de voos.

**Correlação de Pearson:** A correlação de Pearson mede a relação linear entre duas variáveis contínuas. Ela assume que as variáveis seguem uma distribuição normal e que a relação entre elas é linear. Este método é ideal quando estamos interessados na força e na direção da relação linear entre as variáveis. 

**Correlação de Spearman:** A correlação de Spearman, por outro lado, não requer a suposição de uma relação linear entre as variáveis. Em vez disso, ela avalia a relação monotônica entre duas variáveis, ou seja, se, à medida que uma variável aumenta, a outra também aumenta (ou diminui). Esta medida é mais robusta do que a correlação de Pearson quando a relação entre as variáveis não é linear ou quando os dados não seguem uma distribuição normal. 

<p align="center">
  <img src="https://github.com/rtmazzeo/Data-Science-Python/blob/main/projeto_estatistica/imagens/correlacao.png">
</p>

**Comentário:**
Entre ActualElapsedTime, CRSElapsedTime, AirTime e Distance: Estas variáveis estão relacionadas ao tempo de voo, então é importante entender como elas se correlacionam. Uma forte correlação entre elas pode indicar uma boa precisão no planejamento dos voos.
Entre AirDelay e DepDelay: Estas variáveis estão relacionadas aos atrasos de voo, sendo crucial entender sua relação para identificar padrões e possíveis causas de atrasos.
Portanto, ao aplicar tanto a correlação de Pearson quanto a de Spearman a este conjunto de dados, podemos obter uma compreensão abrangente das relações entre as diferentes medidas de desempenho de voo, ajudando assim a melhorar a eficiência e a confiabilidade dos serviços de transporte aéreo.
