### Informações Gerais

Projeto desenvolvido durante formação em desenvolvedor Web Full Stack pela Trybe.

---

# Boas vindas ao repositório do projeto All For One

Este projeto tem o intuito de praticar os conceitos de SQL utilizando o banco de dados `Northwind`.

Lembrando que esta aplicação corresponde aos meus esforços para melhorar minhas hard skills e soft skills, sinta-se à vontade para explorá-la! Feedbacks construtivos são sempre bem vindos!

Abaixo você poderá encontrar mais informações técnicas sobre este projeto.

# Sumário

- [Habilidades](#habilidades)
- [Intruções para fazer o fork do repositório](#intruções-para-fazer-o-fork-do-repositório)
- [Informações do projeto](#informações-do-projeto)
  - [Code Climate](#code-climate)
  - [Banco de dados Northwind](#banco-de-dados-northwind)
- [Desafios](#desafios)
  - [Desafio 1](#desafio-1)
  - [Desafio 2](#desafio-2)
  - [Desafio 3](#desafio-3)
  - [Desafio 4](#desafio-4)
  - [Desafio 5](#desafio-5)
  - [Desafio 6](#desafio-6)
  - [Desafio 7](#desafio-7)
  - [Desafio 8](#desafio-8)
  - [Desafio 9](#desafio-9)
  - [Desafio 10](#desafio-10)
  - [Desafio 11](#desafio-11)
  - [Desafio 12](#desafio-12)
  - [Desafio 13](#desafio-13)
  - [Desafio 14](#desafio-14)
  - [Desafio 15](#desafio-15)
  - [Desafio 16](#desafio-16)
  - [Desafio 17](#desafio-17)
  - [Desafio 18](#desafio-18)
  - [Desafio 19](#desafio-19)
  - [Desafio 20](#desafio-20)
  - [Desafio 21](#desafio-21)
  - [Desafio 22](#desafio-22)
  - [Desafio 23](#desafio-23)
  - [Desafio 24](#desafio-24)
  - [Desafio 25](#desafio-25)
  - [Desafio 26](#desafio-26)
  - [Desafio 27](#desafio-27)

---

# Habilidades

Nesse projeto, fui capaz de:

- Entender o que são bancos de dados
- Entender como a linguagem de consulta estruturada (SQL) é usada
- Compreender como as tabelas se encaixam no conceito de banco de dados
- Montar um ambiente de desenvolvimento local para praticar SQL
- Entender como usar o MySQL Workbench
- Compreender o que é uma query SQL e quais são seus tipos de comando
- Gerar valores com `SELECT`
- Selecionar colunas individualmente com `SELECT`
- Renomear e gerar colunas em uma consulta com `AS`
- Concatenar colunas e valores com `CONCAT`
- Remover dados duplicados em uma consulta com `DISTINCT`
- Contar a quantidade de resultados em uma consulta com `COUNT`
- Limitar a quantidade de resultados em uma consulta com `LIMIT`
- Pular resultados em uma consulta com `OFFSET`
- Ordernar os resultados de uma consulta com `ORDER BY`
- Filtrar resultados de consultas com o `WHERE`
- Utilizar operadores booleanos e relacionais em consultas
- Criar consultas mais dinâmicas e maleáveis com `LIKE`
- Fazer consultas que englobam uma faixa de resultados com `IN` e `BETWEEN`
- Encontrar e separar resultados que incluem datas.
- Inserir dados em tabelas com `INSERT`
- Atualizar dados em tabelas com `UPDATE`
- Apagar dados em tabelas com `DELETE`

---

# Instruções para fazer o fork do repositório

1. Faça o fork do repositório

2. Instale as dependências do projeto
  * Instale as dependências:
    * `npm install`

---

# Informações do projeto

### Code Climate

Para garantir a qualidade do código de forma a tê-lo mais legível, de mais fácil manutenção e seguindo as boas práticas de desenvolvimento foi utilizado neste projeto o Code Climate.

### Banco de dados `Northwind`

Instruções para instaurar o banco de dados:

1. Faça o download do arquivo de backup [aqui](northwind.sql) clicando em "Raw", depois clicando com botão direito e selecionando "Salvar como" para salvar o arquivo em seu computador.
2. Abra o arquivo com algum editor de texto, e selecione todo o conteúdo do arquivo usando `CTRL-A`.
3. Abra o MySQL Workbench.
4. Abra uma nova janela de query e cole dentro dela todo o conteúdo do arquivo `northwind.sql`.
5. Selecione todo o código com o atalho `CTRL-A` e depois clique no icone de trovão para executar a query.

    ![Restaurando o banco Northwind](images/restore_northwind.png)
6. Aguarde alguns segundos (espere em torno de 30 segundos antes de tentar fazer algo).
7. Clique no botão apontado na imagem a seguir para atualizar a listagem de banco de dados.

    ![Tabelas do banco Northwind](images/refresh_databases.png)
7. Verifique se o banco restaurado possui todas as seguintes tabelas:

    ![Tabelas do banco Northwind](images/northwind.png)
8. Clique com botão direito em cada tabela e selecione "Select Rows" e certifique-se que todas as tabelas possuem registros. Caso tenha alguma faltando, faça o passo a seguir. Caso contrário, pode ir para próxima seção.
9. Caso existam tabelas faltando, drope o banco de dados, clicando com o botão direito em cima do banco de dados northwind e selecionando "Drop Schema", e refaça os passos novamente, dessa vez aguardando um tempo maior quando executar o script de restauração.

    ![Drop Schema](images/drop_database.png)

---

# Desafios

### Desafio 1

Exiba apenas os nomes dos produtos da tabela `products`.

### Desafio 2

Exiba os dados de todas as colunas da tabela `products`.

### Desafio 3

Escreva uma query que exiba os valores da coluna que contém a primary key da tabela `products`.

### Desafio 4

Conte quantos registros existem na coluna `product_name` da tabela `products`.

### Desafio 5

Monte uma query que exiba os dados da tabela `products` a partir do quarto registro até o décimo terceiro. Tanto o quarto quanto o décimo terceiro registros, precisam aparecer na consulta. Obs.: não use `where` ou `order by`.

### Desafio 6

Exiba os dados das colunas `product_name` e `id` da tabela `products` de maneira que os resultados estejam em ordem alfabética dos nomes.

### Desafio 7

Mostre apenas os ids dos 5 últimos registros da tabela `products` (a ordernação deve ser baseada na coluna `id`).

### Desafio 8

Faça uma consulta que retorne três colunas. Na primeira coluna, exiba a soma de `5 + 6` (essa soma deve ser realizada pelo SQL). Na segunda coluna deve haver a palavra \"de\". E por fim, na terceira coluna, exiba a soma de `2 + 8` (essa soma deve ser realizada pelo SQL). A primeira coluna deve se chamar \"A\", a segunda coluna deve se chamar \"Trybe\" e a terceira coluna deve se chamar \"eh\". Não use colunas pre-existentes, apenas o que for criado na hora.

### Desafio 9

Mostre todos os valores da coluna `notes` da tabela `purchase_orders` que não são nulos.

### Desafio 10

Mostre todos os dados da tabela `purchase_orders` em ordem decrescente, ordenados por `created_by` em que o `created_by` é maior ou igual a 3. Como critério de desempate para a ordenação, ordene também os resultados pelo `id` de forma crescente.

### Desafio 11

Exiba os dados da coluna `notes` da tabela `purchase_orders` em que seu valor de \"Purchase generated based on Order\" está entre 30 e 39, incluindo tanto o valor de 30 quanto de 39.

### Desafio 12

Mostre os resultados da coluna `submitted_date` da tabela  `purchase_orders` em que a `submitted_date` é do dia 26 de abril de 2006.

### Desafio 13

Mostre o resultado da coluna `supplier_id` da tabela `purchase_orders` em que o `supplier_id` seja 1 ou 3.

### Desafio 14

Mostre os resultados da coluna `supplier_id` da tabela `purchase_orders` em que o `supplier_id` esteja entre os valores 1 e 3, incluindo tanto o 1 quanto o 3.

### Desafio 15

Mostre somente as horas (sem os minutos e os segundos) da coluna `submitted_date` de todos registros da tabela `purchase_orders`. Chame essa coluna de `submitted_hour`.

### Desafio 16

Exiba os resultados da coluna `submitted_date` da tabela `purchase_orders` que estão entre `2006-01-26 00:00:00` e `2006-03-31 23:59:59`.

### Desafio 17

Mostre os registros das colunas `id` e `supplier_id` da tabela `purchase_orders` em que os `supplier_id` sejam tanto 1, ou 3, ou 5, ou 7.

### Desafio 18

Mostre todos os registros da tabela `purchase_orders` que tem o valor na coluna `supplier_id` igual a 3 e o valor na coluna `status_id` igual a 2.

### Desafio 19

Mostre a quantidade de pedidos que foram feitos na tabela `orders` pelo `employee_id` igual a 5 ou 6, e que foram enviados através do método(coluna) `shipper_id` igual a 2. Chame a coluna de `orders_count`.

### Desafio 20

Adicione à tabela `order_details` uma linha com os seguintes dados: `order_id`: 69, `product_id`: 80, `quantity`: 15.0000, `unit_price`: 15.0000, `discount`: 0, `status_id`: 2, `date_allocated`: NULL, `purchase_order_id`: NULL e `inventory_id`: 129. Obs.: o `id` deve ser incrementado automaticamente.

### Desafio 21

Adicione, com um único `INSERT`, duas linhas à tabela `order_details` com os mesmos dados. Esses dados são novamente `order_id`: 69, `product_id`: 80, `quantity`: 15.0000, `unit_price`: 15.0000, `discount`: 0, `status_id`: 2, `date_allocated`: NULL, `purchase_order_id`: NULL e `inventory_id`: 129. O `ìd` deve ser incrementado automaticamente.

### Desafio 22

Atualize os dados na coluna `discount` da tabela `order_details` para 15. (Não é necessário utilizar o SAFE UPDATE em sua query).

### Desafio 23

Atualize os dados da coluna `discount` da tabela `order_details` para 30, onde o valor na coluna `unit_price` seja menor que 10.0000. (Não é necessário utilizar o SAFE UPDATE em sua query).

### Desafio 24

Atualize os dados da coluna `discount` da tabela `order_details` para 45, onde o valor na coluna `unit_price` seja maior que 10.0000 e o id seja um número entre 30 a 40. (Não é necessário utilizar o SAFE UPDATE em sua query).

### Desafio 25

Delete todos os dados na coluna `unit_price` da tabela `order_details` em que o valor seja menor que 10.0000.

### Desafio 26

Delete todos os dados na coluna `unit_price` da tabela `order_details` em que o valor seja maior que 10.0000.

### Desafio 27

Delete todos os dados da tabela `order_details`.

---