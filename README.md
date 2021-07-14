<h1>Digital Innovation: Expert Class - Desenvolvendo um sistema de gerenciamento de pessoas em API REST com Spring Boot</h1>

Uma _live coding_ em que foi desenvolvido um pequeno sistema de gerenciamento de pessoas de uma empresa através de uma API REST, criada com Spring Boot.

Durante as aulas foram desenvolvidos e abordados os seguintes tópicos:

* Setup inicial de projeto com o Spring Boot Initialzr
* Criação de modelo de dados para mapeamento de entidades em banco de dados
* Desenvolvimento de operações de gerenciamento de usuários
  * Cadastro, Leitura, Atualização e Remoção de pessoas do sistema.
* Relação de cada uma das operações acima com o padrão arquitetural REST, e a explicação de cada um dos conceitos REST envolvidos durante o desenvolvimento do projeto
* Desenvolvimento de testes unitários para validação das funcionalidades
* Implantação dos sistema na nuvem através do Heroku.

Para executar o projeto no terminal, digite o comando:

```shell script
mvn spring-boot:run
```

Com isso, o projeto pode ser visto em execução no navegador:

```uri
http://localhost:8080/api/v1/people
```

O que eu utilizei para acompanhar este projeto:

* Java 11
* Maven 3.8.1
* VSCode
* Controle de versão GIT
* Conta GITHUB para armazenamento do projeto
* Conta Heroku para deploy do projeto na nuvem
