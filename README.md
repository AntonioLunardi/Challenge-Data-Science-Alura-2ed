# Challenge de Data Science | 2ª edição

| :placard: Vitrine.Dev |     |
| -------------  | --- |
| :sparkles: Nome        | **Challenge-Data-Science-Alura-2ed**
| :label: Tecnologias | PySpark, spark-mllib, spark-sql, pandas, Python
| :fire: Desafio     | [Página do desafio](https://www.alura.com.br/challenges/data-science-2?utm_source=ActiveCampaign&utm_medium=email&utm_content=%5BChallenge+Data+Science%5D+Um+novo+projeto+de+DS+para+seu+portf%C3%B3lio+%F0%9F%A4%A9&utm_campaign=%5BChallenges%5D+%28Dados+2a+ed+%29+Divulga%C3%A7%C3%A3o+para+base+de+alunos&vgo_ee=uW58UIGWuy1MfM%2BLWXlW8GQOP8ZXmRzMvz3Yw%2BcA7gI%3D)

<div align="center">
<img src="https://i.imgur.com/Tnj84r9.jpg#vitrinedev" width="800px" />
</div>

A imobiliária InsightPlaces, situada na cidade do Rio de Janeiro, está enfrentando dificuldades para alugar e vender imóveis. Em uma pesquisa de como empresas semelhantes operam no mercado, a InsightPlaces percebeu que esse problema pode estar relacionado aos valores dos imóveis e às recomendações realizadas em seu site. 

Dentro desse contexto, como podemos definir de forma eficiente os preços dos imóveis lidando com grandes volumes de dados? É importante recomendar imóveis utilizando outro critério? O que precisa ser feito?

Você faz parte do time de Ciência de Dados e Big Data da InsightPlaces e ficou responsável por auxiliar no processo de análise de dados dos imóveis, que estão localizados em alguns bairros da cidade do Rio de Janeiro.

Esse projeto tem algumas etapas como: ler e fazer o tratamento do histórico dos preços de imóveis no Rio de Janeiro, construir um modelo de regressão para precificar imóveis e, por último, criar um recomendador de imóveis. Para cada uma dessas etapas, vamos utilizar a ferramenta PySpark, que oferece uma melhor performance ao trabalharmos com grandes volumes de dados.

## Semana 1

Na semana 1 vamos fazer parte do trabalho de pessoas engenheiras de dados.

O time de engenharia de dados da InsightPlaces disponibilizou uma base de dados no estado bruto para trabalharmos. Durante a semana 1, ficamos responsáveis por fazer transformações mais iniciais nesses dados, de forma que eles fiquem mais estruturados. Utilizamos os recursos do PySpark para conseguirmos explorar essa base de dados, realizar transformações em algumas colunas e também aplicar filtros específicos para obtermos apenas as informações que interessam para nossa análise.

No final dessa semana, salvamos os dados transformados no formato parquet para podermos utilizá-los na semana 2.

## Semana 2

A semana 2 é dedicada ao tratamento dos dados e a criação de modelos de regressão para precificação dos imóveis.

Durante essa semana, realizamos trabalhos de pessoas cientistas de dados. Dessa forma, começamos importando os dados que foram salvos no final da semana anterior e realizamos a exploração, o tratamento e a remoção de dados faltantes dessa base de dados.

Após esses tratamentos, nós preparamos os dados para conseguirmos utilizá-los para a criação de modelos de Machine Learning do PySpark. Salvamos esses dados preparados para ML no formato parquet para utilizarmos na semana seguinte.

Feito isso, finalizamos a semana criando modelos de regressão com esses dados utilizando a biblioteca MLlib do PySpark.

## Semana 3 e 4

Durante as semanas 3 e 4, vamos focar em melhorar o sistema de recomendação da InsightPlaces.

Nosso sistema não está recebendo os clicks que esperava apenas recomendando imóveis das mesmas regiões e na mesma faixa de preço. Por isso, como parte do time de Data Science, precisamos criar uma nova mecânica de recomendação de imóveis.

O objetivo é criar um sistema de recomendação de imóveis baseado em similaridade de características. A base de dados utilizada será a base de dados tratada na semana 2, após transformarmos as variáveis categóricas em variáveis binárias e antes de aplicarmos a vetorização.

Para criarmos esse sistema de recomendação, utilizamos técnicas de padronização e redução de dimensionalidade dos nossos dados. Assim, podemos criar nossos clusters e também uma função que seja responsável pela recomendação dos melhores imóveis.
