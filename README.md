# Dashboard-de-Vendas-Globais---Basico
Atividade básica de criação de um Dashboard sobre as vendas globais de uma empresa ficticia.

## OBJETIVO
O foco dessa atividade era utilizar o PowerBI para responder 5 perguntas, sendo elas.
<br>
• Pergunta 1 - Qual o valor total vendido?
<br>
• Pergunta 2 - Quantas vendas foram realizadas por categoria de produto?
<br>
• Pergunta 3 - Quantas vendas foram realizadas por país considerando a prioridade de entrega?
<br>
• Pergunta 4 - Qual foi a média de desconto nas vendas por subcategoria de produto?
<br>
• Pergunta 5 - Quais países tiveram maior média de valor de venda? Demonstre em um mapa.
<br><br>

## Excel
<img align = "right" width="435" height="303" alt="image" src="https://github.com/user-attachments/assets/d7cb6a93-6d5f-4f40-9df5-a0adf708a5aa" />
Iniciei o projeto realizando uma análise dentro do Excel. Comecei estudando quais as colunas dentro do arquivo, quantas regiões, países, categorias, sub categorias e prioridades tinham dentro do DataSet, também observei que os dados começam na data 01/01/2011 e terminam em 31/12/2014
<br>
<br>
<br>
<br>
<br>
<br>

## Power BI
### Pergunta 1 - Qual o valor total vendido?
Para responder essa pergunta, utilizei apenas os cartões do PowerBI, porém, para a análise ser mais completa, resolvi adicionar também a Soma da Quantidade Vendida e a Média de vendas.
<br>
<img width="161" height="84" alt="image" src="https://github.com/user-attachments/assets/c0291c29-18fd-4f23-8a8e-bd32d7e216a3" />
<img width="161" height="84" alt="image" src="https://github.com/user-attachments/assets/439668ec-da72-4b1f-9906-e77fd01759ed" />
<img width="161" height="84" alt="image" src="https://github.com/user-attachments/assets/1cbdffc8-d4cc-4ce7-9e55-057a10b54e32" />
<br>

### Pergunta 2 - Quantas vendas foram realizadas por categoria de produto?
<img align = "right" width="261" height="219" alt="image" src="https://github.com/user-attachments/assets/9d97e702-4384-4621-9115-8d89716b3458" />
Para responder esse quesitonamento, utilizei um gráfico de rosca, esse gráfico foi escolhido pois na Base de Dados há apenas 3 categorias de produtos, assim facilitando a visualização de cada uma no gráfico de rosca. 
Após uma simples análise foi possível identificar que a categoria que mais realizou vendas foi a Suprimentos, logo seguida por Tecnologia e Moveis, que estão quase empatados
<br>
<br>
<br>
<br>
<br>
<br>

### Pergunta 3 - Vendas realizadas por país considerando a prioridade de entrega?
<img align = "left" width="411" height="202" alt="image" src="https://github.com/user-attachments/assets/09b51a76-1098-41be-a7db-8dda9911719c" />
Para encontrar a resposta da Pergunta 3 foi utilizado o gráfico de barras empilhadas, nele foi adicionado os dados de ID_Pedido, País e Prioridade, dessa forma foi possível identificar a resposta para a Pergunta 3, sendo os Estados Unidos o País que mais realizou vendas, logo em seguida vindo a Austrália e França.
<br>
<br>
<br>
<br>
<br>
<br>

### Pergunta 4 - Qual foi a média de desconto nas vendas por subcategoria de produto?
<img align = "right" width="205" height="224" alt="image" src="https://github.com/user-attachments/assets/df374206-c7e6-475d-af70-0f96a32cc159" /> A média de desconto por subcategoria foi simples de se encontrar, bastou utilizar um gráfico de barras e adicionar os dados de Desconto e SubCategoria. Após uma breve análise foi possível identificar que "Tables" obteve 0,29 de Média de Desconto, assim liderando o ranking, seguido de "Bindlers" com 0,18 e "Machines" com 0,17
<br>
<br>
<br>
<br>
<br>
<br>

### Pergunta 5 - Quais países tiveram maior de valor de venda? Demonstre em um mapa.
<img align = "left" width="398" height="193" alt="image" src="https://github.com/user-attachments/assets/901934e1-5c28-4815-9f46-172afcc08c10" />
A ultima pergunta a se responder utilizando a base de dados foi a Pergunta 5, e para responde-la utilizei o Mapa do PowerBI e os dados de "País" e "Total de Vendas. Através do mapa foi possível identificar que a Europa e Ásia estão indo muito bem nas vendas, seguidos logo atrás pela África, enquanto isso as Américas deixam a desejar no resultado.
<br>
<br>
<br>
<br>
<br>
<br>

### Insides
Acredito que o ideia seja identificar o mótivo das vendas dos Estados Unidos estarem perdendo para Europa e Ásia, sendo que os Estados Únidos lideram em pedido por país, isso me leva a crer que o País realmente libera muitos pedidos, porém por valores abaixo do ideal, assim ficando com um valor de venda abaixo de Europa e Ásia. 
<br>
O segundo ponto a se explorar seria a América do Sul, estando muito atrás de outros mercados, inclusive do próprio Estados Únidos, assim podendo se tornar um grande mercado futuramente.
<br>
<img align = "center" width="717" height="363" alt="image" src="https://github.com/user-attachments/assets/7a2559db-efbb-429d-bf5f-b5e50b0a1ffb" />
