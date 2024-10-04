# 📊 Projeto: Análise de Leads e Veículos 🛠️
Neste projeto, realizei uma análise completa de leads e veículos para entender melhor o comportamento dos nossos clientes. O objetivo foi criar uma série de queries SQL para extrair informações detalhadas de um banco de dados e visualizar os dados de maneira clara em um dashboard criado no Excel.

![image](https://github.com/user-attachments/assets/efcf9585-3089-4744-a05c-fddf471ae1ec)


## 👩‍💻 Ferramentas Utilizadas:
PostgreSQL para a manipulação dos dados.
PgAdmin como interface para executar as queries SQL.
Excel para visualizar os resultados das queries em um dashboard interativo.

## 🔍 O que foi feito:
### Gênero dos Leads: 👫
Identifiquei a quantidade de leads masculinos e femininos. Aqui usamos um LEFT JOIN com a tabela de gêneros para cruzar os nomes dos leads e classificá-los.

### Status Profissional: 💼
Classifiquei os leads por status profissional (freelancer, estudante, CLT, etc.), usando CASE para traduzir os dados e calcular a porcentagem de leads em cada categoria.

### Faixa Etária dos Leads: 🎂
Agrupei os leads em faixas etárias com a função AGE e calculamos a distribuição percentual.

### Faixa Salarial: 💰
Dividi os leads em faixas de renda com base na coluna income, usando CASE para categorizar as faixas e ordenar os dados.

### Classificação dos Veículos: 🚗
Classifiquei os veículos visitados como novos ou seminovos, com base no ano do modelo e na data da visita ao site, usando WITH para subconsultas.

### Idade dos Veículos Visitados: 🕒
Segmentei os veículos visitados por faixas de idade e calculamos a porcentagem de visitas, facilitando o entendimento da preferência dos leads.

### Veículos Mais Visitados: 🏎️
Identifiquei as marcas e modelos mais populares, usando GROUP BY e ORDER BY para listar os 10 veículos mais visitados.

## 📈 Dashboard no Excel:
Após executar as queries no PostgreSQL, os resultados foram exportados para o Excel. A partir disso, criei um dashboard interativo que facilita a visualização dos insights de forma simples e direta.

[Projeto 2. Dashboard_Leads.xlsx](https://github.com/user-attachments/files/17251278/Projeto.2.Dashboard_Leads.xlsx)
