# turn2c-tech-challenge

Desafio técnico - Pleno
## Pleno
* Crie uma aplicação a partir do <a href="https://start.spring.io/">spring.initializer</a>
* Utilize as dependências desejadas caso ache necessário, mas importe as necessárias maven e outras para criar rest api´s
* Utilize um banco de dados, sugestão H2
  ## Desafio:
    * Crie uma aplicação em camadas
    * Implemente um crud
        * Crie 4 objetos, sendo Usuario, Vendedor, Cliente e Master
            * Cada objeto deve possuir atributos semelhantes, alguns deve possuir atributos diferentes
            * Utilize atributos como nome, email para Usuario, apenas o Vendedor e Cliente possuem atributos diferentes, porem ambos são um Usuario
            * O Master, alem de ser um Usuario, pode ter perfis de Vendedor e Cliente
        * Construa um serviço rest que recebe um dto, mapeie a request para o dominio construido.
        * Realize tratamentos para cada exceção que possa ocorrer
        * Persista os dados em base dados
        * Crie outros seviços para ler os dados cadastrados, ler o dado via parametro, atualizar e deletar
    * Crie testes unitários para válidar os serviços disponíveis
    * Crie a documentação dos serviços rest com Swagger OpenApi
    * Realize a construção da aplicação utilizando boas práticas de desenvolvimento.
    * Utilize no minimo 3 patterns, sendo um deles builder
    * Utilize Solid e clean code
    * Suba o projeto em seu repositório, nele, precisa conter o README.md,
        explique de forma resumida o que sua aplicação faz e quais beneficios de um código limpo e a arquititura em cadamas utilizada.

    Poderá criar mais features, melhorias, patterns etc ... caso ache necessário, mas os itens acima precisam ser atendidos.
