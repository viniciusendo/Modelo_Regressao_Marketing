<h1 align="center">DNC - Desafio Modelo de Regressão para Marketing</h1>

<p align="center">
 <a href="#entendimento-do-negócio">Entendimento do negócio</a> •
 <a href="#tratamento-dos-dados">Tratamento dos dados</a> • 
 <a href="#entendimento-dos-dados">Entendimento dos dados</a> • 
 <a href="#perguntas-de-negócio">Perguntas de negócios</a> •  
 <a href="#tecnologias-utilizadas">Tecnologias utilizadas</a
</p>

## Entendimento do negócio
<p align="justify">
Esta é uma proposta de resolução para um desafio da Formação em Dados da Escola DNC. Trata-se de uma análise para verificar o desempenho de investimentos feitos em plataformas de publicidade online (Youtube, Facebook e Newspaper) e a criação de um modelo de regressão simples para estimar o retorno de vendas a partir dos investimentos em publicidade.

<p align="justify">
A empresa possuía uma base de dados contendo informações sobre os investimentos em publicidade para cada plataforma e o retorno de vendas gerado a partir destes investimentos.

## Tratamento dos dados
<p align="justify">
Para utilizarmos as informações de maneira ideal, não foi necessário fazer nenhuma manipulação da base de dados.

## Entendimento dos dados
<p align="justify">
Foi feita a análise univariada para observar a distribuição de variáveis numéricas (mín, máx, desvio padrão) afim de procurar por padrões ou tendências relevantes para o negócio. Foram utilizados também gráficos do tipo histograma e boxplot para visualização dos dados e gráficos do tipo pairplot e heatmap para buscar correlação entre variáveis.

## Perguntas de negócio
<p align="justify">
A análise dos investimentos mostrou que o retorno em vendas foi de 7,6% do total investido em publicidade nas plataformas. Além disso, a análise de correlação indicou que investimentos maiores no Youtube e Facebook tem maior chance de gerar mais retorno, enquanto investimentos em Newspaper podem ter um retorno mais imprevisível.

<p align="justify">
Para a criação do modelo de predição, optou-se por utilizar a técnica de regressão linear de maneira bem simplificada, sem otimização de hiperparâmetros uma vez que se trata de um projeto introdutório de machine learning. O modelo apresentou um R<sup>2</sup> igual a 0.87.

<p align="center">
    <img width="460" height="300" src="https://github.com/viniciusendo/dnc_desafio_regressao/assets/134152277/95e081a8-4688-4523-81d9-b168995bb08f">
</p>

## Tecnologias utilizadas
- Google Colab
- Python
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn
