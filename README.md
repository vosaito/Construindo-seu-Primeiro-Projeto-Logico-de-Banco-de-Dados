
# Projeto Ecommerce - Construindo seu Primeiro Projeto Lógico de Banco de Dados

 Realização do desafio proposto pela instrutora Juliana da Digital Innovation One.  
 Foi feito um sistema de banco de dados para um serviço de E commerce, o qual foi realizado em conjunto com a Juliana, que iniciou a modelagem e o projeto Lógico do BD.


### Escopo do Projeto
Objetivo  
* Criar/aprimorar o esquema conceitual para o contexto de E commmerce;
* Criar uma banco de dados a partir do esquema desenvolvido;
* Elaborar queries para consulta/insights a partir de dados fictícios.  
\
Diretrizes para elaboração das queries
- Recuperações simples com SELECT Statement;
- Filtros com WHERE Statement;
- Crie expressões para gerar atributos derivados;
- Defina ordenações dos dados com ORDER BY;
- Condições de filtros aos grupos – HAVING Statement;
- Crie junções entre tabelas para fornecer uma perspectiva mais complexa dos dados;
- Não há um mínimo de queries a serem realizadas;
- Os tópicos supracitados devem estar presentes nas queries;
- Elabore perguntas que podem ser respondidas pelas consultas;
- As cláusulas podem estar presentes em mais de uma query.

### Desafio Realizado
Os principais pontos feitos para a criação do esquema conceitual do sistema para oficina foram:
* Criação de uma entidade "pagamento" para cadastro de diferentes formas de pagamento por um único cliente;
* Criação de duas entidades para cadastro de clientes "Clientes PF" e "Clientes PJ" para separação de Clientes pessoa física e jurídica, pois possuem dados diferentes como nome/razão social e CPF/CNPJ;
* Criação de entidade para Entrega que seria armazanado os códigos de rastreamento e status da entrega para cada pedido/produto a depender do local de estoque.

Queries elaboradas para consulta ao banco de dados
* Status dos pedidos por Cliente PF e PJ
* Modo de pagamento dos Clientes PF e PJ
* Quantos pedidos cada cliente fez?
* Algum vendedor é fornecedor também?
* Relação de nomes dos fornecedores e nomes dos produtos
* Valor Total (produto+frete) do pedido, identificando o Cliente
* Rastreando o pedido do client, pedido número do pedido
* Consultando estoque de produto com quantidade mínima (ex: menor que 100 itens)
* Filtrando o Valor Total (produto+frete) do pedido, acima de 400 reais
