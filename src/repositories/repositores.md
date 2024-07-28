**Repositório**

É uma camada (classe) que será responsável por fazer toda a manipulação de dados da nossa aplicação
Os repositories serão responsável por fazer o acesso a banco de dados, os inserts, toda manipulação com o banco de dados.

**Routes** -> vai chamar o repositório e ele será responsável pela inserção no banco de dados, select.

A rota chama o repositório e a mesma retorna o que ele precisa.

**DTO** => Data Transfer Object => É um conceito de criar um objeto que será responsável por fazer a transferência de dados
entre uma classe e outra.

Toda vez que criarmos um objeto, recebermos informações da rota, criaremos um DTO pra pegar esses valores da rota e
recebermos do repositório.
