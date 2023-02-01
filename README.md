# Challenge de Data Science | 2ª edição
O trabalho tem por fim reformular os sistemas de recomendação e venda de imóveis da imobiliária InsightPlaces, tornando-os mais eficientes. Utilizando tecnologia Apache PySpark, inicialmente é feito um trabalho de engenharia de dados para tratamento do dataset. Posteriormente são criados modelos de machine learning de regressão e clusterização/recomendação.

| :placard: Vitrine.Dev |     |
| -------------  | --- |
| :sparkles: Nome        | **Challenge-Data-Science-Alura-2ed**
| :label: Tecnologias | PySpark, spark-mllib, spark-sql, pandas, Python
| :fire: Desafio     | [Página do desafio](https://www.alura.com.br/challenges/data-science-2?utm_source=ActiveCampaign&utm_medium=email&utm_content=%5BChallenge+Data+Science%5D+Um+novo+projeto+de+DS+para+seu+portf%C3%B3lio+%F0%9F%A4%A9&utm_campaign=%5BChallenges%5D+%28Dados+2a+ed+%29+Divulga%C3%A7%C3%A3o+para+base+de+alunos&vgo_ee=uW58UIGWuy1MfM%2BLWXlW8GQOP8ZXmRzMvz3Yw%2BcA7gI%3D)

<div align="center">
<img src="https://i.imgur.com/Tnj84r9.jpg#vitrinedev" width="800px" />
</div>

O desafio teve duração de quatro semanas de encontros e metas a serem cumpridas utilizando metologia ágil. 
Consistiu de um caso simulado de uma imobiliária fictícia:

A imobiliária InsightPlaces, situada na cidade do Rio de Janeiro, está enfrentando dificuldades para alugar e vender imóveis. Em uma pesquisa de como empresas semelhantes operam no mercado, a InsightPlaces percebeu que esse problema pode estar relacionado aos valores dos imóveis e às recomendações realizadas em seu site. Dentro desse contexto, é preciso definir de forma eficiente os preços dos imóveis lidando com grandes volumes de dados.

São as etapas deste projeto: 
- Ler e fazer o tratamento do histórico dos preços de imóveis no Rio de Janeiro
- Construir um modelo de regressão para precificar imóveis
- Criar um recomendador de imóveis. 
 
Para cada uma dessas etapas, é utilizada a ferramenta PySpark, que oferece uma melhor performance ao trabalhar-se com grandes volumes de dados.

## Semana 1

Transformações iniciais nos dados, deixando-os mais estruturados:

Utilizaram-se os recursos do PySpark para explorar a base de dados, realizar transformações em colunas e aplicar filtros específicos para obtenção de informações que interessam para a análise. Os dados foram, ao final, convertidos em formato parquet.

## Semana 2

Tratamento dos dados e a criação de modelos de regressão para precificação dos imóveis:

Foi feita a importação dos dados que foram salvos no final da semana anterior, realização da exploração, do tratamento e da remoção de dados faltantes. Após esses tratamentos, prepararam-se os dados para a criação de modelos de machine learning do PySpark. Salvaram-se os dados já preparados para ML no formato parquet para utilização futura.

## Semanas 3 e 4

Melhoramento do sistema de recomendação:

A base de dados utilizada foi a preparada surante semana 2, após transformar as variáveis categórica em variáveis binárias e antes de ser aplicada a vetorização. Utilizaram-se técnicas de padronização e redução de dimensionalidade nos dados. Foi possível criar clústeres e uma função capaz de realizar uma melhor recomendação dos imóveis.
