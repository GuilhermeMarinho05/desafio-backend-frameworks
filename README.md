# Desafio Backend Frameworks

Este repositório apresenta dois projetos back-end utilizando frameworks diferentes: Node.js com Express e Java com Spring Boot. O objetivo é demonstrar a organização em camadas seguindo o modelo MVC.

## Estrutura dos Projetos

### Node.js / Express

O projeto Node.js foi organizado com as seguintes camadas:

- models: responsável pela representação dos dados.
- controllers: responsável por receber as requisições e controlar as respostas.
- routes: responsável por definir as rotas da aplicação.

### Java / Spring Boot

O projeto Spring Boot foi organizado com as seguintes camadas:

- models: representa as entidades do sistema.
- controllers: recebe as requisições HTTP.
- services: contém as regras de negócio da aplicação.

## Comparação entre Node.js/Express e Java/Spring Boot

O Express é mais simples e rápido para configurar, pois exige poucos arquivos e possui uma estrutura mais flexível. Já o Spring Boot possui uma configuração inicial mais robusta, com mais arquivos e padrões definidos.

Em relação à verbosidade, o Node.js com Express possui menos código para iniciar uma API simples. O Spring Boot exige mais código, porém oferece uma organização mais padronizada e recursos prontos para aplicações maiores.

Na gestão de dependências, o Node.js utiliza o npm e o arquivo package.json. O Spring Boot utiliza Maven ou Gradle, com dependências configuradas no pom.xml ou build.gradle.

## Comunicação entre as Camadas

Em uma aplicação back-end organizada em camadas, as rotas recebem as requisições do usuário e encaminham para os controllers. Os controllers processam a requisição e chamam os services ou models quando necessário. Os models representam os dados da aplicação.

Essa separação facilita a manutenção, organização e evolução do sistema, pois cada camada possui uma responsabilidade específica.

## Conclusão

A atividade mostra que diferentes frameworks podem seguir o mesmo princípio arquitetural. Tanto Express quanto Spring Boot permitem organizar uma aplicação em camadas, separando responsabilidades e tornando o código mais limpo e estruturado.
