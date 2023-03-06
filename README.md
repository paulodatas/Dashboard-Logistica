# Projeto: Dashboard-logistica
## Introdução
Esse Projeto foi um desafio feito pela DSA, onde eles nos deram um dashboard que precisava ser reconstruído,
afim de identificar e corrigir os erros e problemas que o mesmo continha, entregando uma nova versão.
<br>
ps: Todos os erros e problemas precisavam ser justificados.
<br>
As perguntas de négocios que precisavam ser respondidas:
* Qual é o total de entregas por canal de entrega ?
* Qual é o Percentual de Entregas por equipe ?
* Qual é o total de entregas por mês ?
* Qual é o total de entregas dos Top 5 vendedores ?
* Qual é o total de entregas com atrazo por cidade ?
* Qual é o percentual de entregas por status de entrega ?

## Ferramentas utilizadas:
Power Bi

## Diagrama dos dados
![diagramadsa](https://user-images.githubusercontent.com/124627259/223005279-b9ba279d-db9e-4c01-a8f7-acfa25572baf.PNG)


## Dashboard apresentado pela DSA para a correção
![errodsa](https://user-images.githubusercontent.com/124627259/223004733-4933447f-3cd9-4949-82fd-2c1693e1d09f.PNG)



## Resolução dos problemas:
* Primeiramente foi corrigido o erro de "alterações pendentes" o caminho para a base de dados estava incorreto, nessecitando a correção para a pasta certa
* O primeiro gráfico a ser corrigido foi de <strong>Total de entregas no prazo por canal de entrega</strong> onde o mesmo estava fazendo a contagem do status de entrega e não a somatória, foi criado uma medida dax com a soma das entregas feitas no prazo para que o erro fosse corrigido.
* O gráfico <strong>Percentual de entregas por equipe</strong> estava com os dados corretos, porém apresentado no gráfico de pizza deixava as informações confusas, deixei as informações sendo apresentadas em um gráfico de linhas clusterizado para uma análise mais fácil ao usuário.
* O gráfico <strong>Total de entregas por mês</strong> não estava sendo filtrado somente por mês das entregas, e sim todos os períodos como: mês, trimestre, dia.
corrigi o erro deixando os dados do mês e ano.
* O gráfico <strong>Total de entregas dos top 5 vendedores</strong> estava mostrando além dos 5 vendedores que mais venderam e em um gráfico de rosca deixando 
informações não legíveis e a mais do que necessário, deixei em formato de tabela o ranking dos 5 top vendedores criando também um rating que facilita a visualização e análise das informações.
* O gráfico de <strong>Total de entregas com atraso por cidade</strong> não estava sendo filtrado somente as entregas com atraso, e também não estava bem apresentado em um gáfico de barras, tive que tomar a decisão de deixa-lo em forma de tabela, pois a quantidade de informação solicitada não estava sendo bem representada por nenhum tipo de gráfico.
* Por fim o gráfico de <strong>Percentual por status de entrega</strong> não estava em formato de porcentagem, onde foi feita a correção do mesmo.
* Criei três cards com informações relevantes e de rápida visualização e também uma segmentação de anos para uma melhor análise anual.

## Resultado das correções 
E esse foi o resultado obtido após a finalização do desafio
![resultadodsa](https://user-images.githubusercontent.com/124627259/223010563-43e11b63-83f7-41ef-9b2a-e6bf200d622d.PNG)

## Diagrama após correções
![diagramacorrigido](https://user-images.githubusercontent.com/124627259/223011137-3770f299-409f-44e5-96b4-706d94c09562.PNG)
