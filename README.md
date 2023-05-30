# 1.	INTRODUÇÃO

O Condado de King é um dos 39 condados do estado americano de Washington. No que concerne a esse assunto, tivemos uma demanda de selecionar os 5 melhores imóveis para se investir e os 5 piores imóveis que não recomendaria para o investimento.
Primeiramente se foi feito uma coleta do data frame disponibilizado com informações dos imóveis denominado "kc_house_data". Com essa coleta e ao fazer entender todos 21613 propriedades registradas e os 21 atributos já estabelecidas nela, foi visto que existe muitos dados corrompidos com linhas duplicadas ou nulas, sabendo disso é necessário que seja feito uma limpeza criteriosa no intuito de tornar esses dados de forma que se possa fazer uma análise perfeita da demanda do cliente.

2.	MANIPULAÇÃO DOS DADOS

Em análise, podemos estabelecer alguns padrões que entendemos que não fazem partes de imóveis cotidianos, assim se tendo o entendimento que esses são dados corrompidos e com isso podemos eliminarmos, pois mais atrapalha nossa análise, exemplos: imóveis sem quartos, sem banheiros, onde a área habitável é maior que o tamanho total do terreno e com número de cômodos muito fora da realidade.
Em verdade, outro aspecto para nossa análise foi a criação de novas colunas no nosso data frame, ou seja, novos atributos como a cidade que se encontra, o preço total por tamanho e o preço por área que pode ser habitada de cada propriedade. Além disso, foi usado o recurso de descrição total dos dados e descrição por cidade dos dados das propriedades. Com isso, nosso data frame tem todos os aspectos que julgamos necessários para a demanda do cliente dos 5 melhores e os 5 piores imóveis para se investir. 

3.	MELHORES INVESTIMENTOS

Concluímos então que os 5 melhores lugares para se investir são os que tivessem uma qualidade de materiais e condições dos imóveis perfeita ou o mais próximo possível disso, sem deixar de lado uma bela visão nas proximidades. Além disso, era necessário um número de quartos e banheiros superior à média geral dos imóveis, assim como o tamanho total e o tamanho da área habitável. Ademais, o tamanho total e o tamanho da área habitável desses imóveis tem que ser igual ou superior dos seus 15 imóveis mais próximos, assim temos um imovel que se destaca na sua vizinhança. Por fim, seu preço não pode ser superior à média de preço total por tamanho e por área habitável da sua cidade de origem, com isso essas propriedades são excelentes oportunidades de negócio.

4.	MELHORES INVESTIMENTOS (ID E INDEX)

	Id: 7856410430, 3914000095, 9541800190, 6116500290 e 8952900245.
Index: 5049, 5672, 15011, 15727 e 17960.

5.	PIORES INVESTIMENTOS
 
Portanto, os 5 piores lugares para se investir são os que tenham uma qualidade de materiais e condições dos imóveis ruins, ou seja, abaixo da média geral, com visão que tenha a pior nota possível. Além disso, temos um número de quartos e banheiros muito inferior à média geral dos imóveis, assim como o tamanho total e o tamanho da área habitável. Para mais, o tamanho total e o tamanho da área habitável desses imóveis tem que ser igual ou inferiores dos seus 15 imóveis mais próximos, assim temos um imovel que não tem nenhum destaque na sua vizinhança. Por fim, seu preço é superior à média de preço total por tamanho e por área habitável da sua cidade de origem, assim não valendo nem um pouco a pena investir nessas propriedades.  

6.	PIORES INVESTIMENTOS (ID E INDEX)

Id: 7325600160, 2726049071, 2767603026, 4067600255 e 1352300580.
Index: 350, 5592, 12757, 17363 e 18052.
