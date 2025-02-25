# API de Produtos

Este é um projeto para a criação de uma aplicação CRUD de produtos, onde serão avaliados conhecimentos em React, JavaScript, Java e Spring Framework. A aplicação terá uma API REST para manipulação de produtos e categorias, e um frontend para gerenciamento e visualização das informações.

## Objetivo

A aplicação permite o gerenciamento de **produtos** e suas **categorias**, possibilitando que o usuário:

- Crie, leia, atualize e exclua produtos.
- Veja todos os produtos listados em uma tabela com filtros (por nome, preço, categoria).
- Manipule os dados de forma simples e eficiente.

## Estrutura do Projeto

### Backend (Spring Boot + Java)

- **Spring Boot** será utilizado para a criação da API REST.
- **Banco de Dados**: O projeto utilizará o **PostgreSQL** para armazenar as informações de produtos e categorias.
- **Requisitos**:
  - CRUD para produtos e categorias.
  - Relacionamento entre **Produto** e **Categoria** (N-1).
  - Relacionamento entre **Pedido** e **Produto** (N-1).

### Frontend (React + JavaScript)

- **React** será utilizado para a criação do frontend da aplicação.
- A interface permitirá visualizar a tabela de produtos, com filtros e opções de edição.
- A aplicação fará chamadas à API REST para realizar as operações de CRUD.
- **Funcionalidades**:
  - Tabela com a listagem dos produtos.
  - Filtros para buscar produtos por nome, preço e categoria.
  - Formulários para adicionar, editar e excluir produtos.

## Critérios Avaliados

1. **Legibilidade**:
   - O código deve ser bem estruturado e fácil de entender.
   - Nomes de variáveis e funções devem ser claros e descritivos.

2. **Controle de versão**:
   - O uso de **git** para versionamento do código será fundamental.
   - É importante que as alterações sejam feitas de forma organizada, com commits claros e frequentes.

3. **Simplicidade do código**:
   - O código deve ser simples, objetivo e sem complexidade desnecessária.
   - A aplicação deve ser fácil de entender, com a menor quantidade de código possível para atingir o objetivo.

4. **Manipulação com o banco de dados**:
   - As operações de CRUD devem ser feitas corretamente, utilizando **JPA** ou **Spring Data** para interação com o banco de dados.
   - A manipulação das entidades **Produto** e **Categoria** deve ser feita de forma eficiente e sem erros.

5. **Manipulação da API REST**:
   - A API deve ser bem estruturada e as rotas (endpoints) devem seguir boas práticas RESTful.
   - A comunicação entre o frontend e o backend deve ser eficiente, com o uso adequado de métodos HTTP (GET, POST, PUT, DELETE).

6. **Conceitos de Frontend**:
   - A aplicação deve ser responsiva, utilizando boas práticas de **React**.
   - O uso de componentes deve ser modular, reutilizável e de fácil manutenção.
   - A interface deve ser clara e simples, com foco na usabilidade.

7. **Tempo para resolver o problema**:
   - A solução deve ser entregue dentro de um prazo razoável. O foco está na qualidade do código, mas também no tempo de desenvolvimento.

8. **Programação Orientada a Objetos (POO)**:
   - As entidades e lógicas de negócio devem ser bem definidas e organizadas usando conceitos de POO.
   - O código deve ser modular, reutilizável e fácil de manter.
