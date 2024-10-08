# 📊 Análise de Vendas e Performance com SQL

## Objetivo:
O projeto visa analisar os dados de vendas de uma empresa, focando em métricas essenciais como leads, receita, conversão e ticket médio. A ideia é transformar dados em insights para tomadas de decisão estratégicas e otimizar os resultados. 🚀

## Schemas:

![image](https://github.com/user-attachments/assets/90ef25b3-3c98-4185-990d-5c39b2ee6aba)

## O que foi feito:
### Receita, leads, conversão e ticket médio mês a mês 💰

Usei SELECT para extrair as informações de leads e vendas.
Combinei as tabelas com LEFT JOIN para unir as datas de visitas e de pagamentos.
Calculei a conversão (%) e o ticket médio utilizando funções agregadas como COUNT e SUM.
Apliquei o GROUP BY para agrupar por mês e ORDER BY para organizar os dados de forma cronológica.

### Top 5 estados que mais venderam 🏆

Usei SELECT e LEFT JOIN para relacionar os dados de vendas com a tabela de clientes, e assim identificar os estados que mais venderam.
Apliquei um WHERE para filtrar as vendas dentro de um período específico e GROUP BY para agrupar os resultados por estado.
Ordenei com ORDER BY para trazer os estados com mais vendas e limitei o resultado a 5 com LIMIT.

### Top 5 marcas mais vendidas 🔝

Similar à análise dos estados, utilizei LEFT JOIN para unir vendas com a tabela de produtos e GROUP BY para agrupar por marca.
Filtrei o período com WHERE e organizei os resultados com ORDER BY e LIMIT.

### Lojas que mais venderam 🏪

Relacionei as vendas com as lojas usando LEFT JOIN, e agrupei as vendas por loja com GROUP BY.
Filtrei o período com WHERE e exibi as lojas mais vendidas com ORDER BY e LIMIT.

### Dias da semana com mais visitas ao site 📅

Extraí o dia da semana com EXTRACT e criei uma lógica de CASE para mostrar o nome dos dias (segunda, terça, etc.).
Agrupei com GROUP BY e ordenei por dia da semana para ver qual teve mais visitas.

Dashboard:
Após tratar os dados com PostgreSQL no PgAdmin, detalhei cada query para garantir que uma próxima pessoa possa atualizar os dados de forma eficiente e sem dificuldades.

Execução das Queries: Executei todas as queries no PgAdmin para gerar as tabelas e métricas desejadas.

Exportação dos Resultados: Copiei os resultados das queries para a aba “Resultados” do Excel, onde organizei os dados para facilitar o processo de visualização.

## Criação do Dashboard: 

Com os dados no Excel, criei um dashboard simples, usando gráficos e tabelas para visualizar:

Receita e conversão mês a mês.
Estados e marcas que mais venderam.
Dias com maior volume de visitas ao site.
Esse processo permite uma visualização clara e objetiva dos dados, facilitando a análise e a tomada de decisões estratégicas. O dashboard é intuitivo e pode ser facilmente atualizado com novos dados. 📊✨

## O que usei:
SQL para escrever as queries e fazer as análises.
Funções Agregadas: COUNT, SUM para calcular vendas, receita e conversão.
LEFT JOIN para unir diferentes tabelas de clientes, produtos e lojas.
Filtros com WHERE para focar em períodos específicos.
GROUP BY para agrupar as métricas por mês, estado, marca e loja.
ORDER BY para organizar os resultados e LIMIT para pegar os top 5.
Excel para consolidar os resultados e criar o dashboard de visualização.


[Projeto 1. Dashboard_Vendas.xlsx](https://github.com/user-attachments/files/17238131/Projeto.1.Dashboard_Vendas.xlsx)
