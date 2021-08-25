# DevInHouse - PROJETO FINAL

Projeto fullstack realizado como tarefa de conclusão o curso DevInHouse SENAI/SC em parceria com ACATE/SC e SOFTPLAN.

<br>

## Funcionalidades

- Deverá ser documentada a **API REST** do Backend feita no **#Projeto 6**;
- Dockerizar o Frontend feito no **#Projeto 6**;
- Dockerizar o Backend feito no **#Projeto 6**;
- Criar um diagrama de integrações dos sistemas feitos até está etapa do processo, contendo as camadas de apresentação, negócio, segurança e persistência.

<br>

## Diagrama de integrações

Diagramas de integrações de aplicações contendo as camadas de apresentação, negócio, segurança e persistência.

<br>

<div align="center">
  <img  width='400' src='https://user-images.githubusercontent.com/45580434/130707396-b277b7f9-cd7e-4153-9e9e-763c645a1bc8.png' alt="diagrama das camadas e aplicação">
</div>

<br><br>

## Ferramentas/tecnologias utilizadas

<br>

### Boas práticas:

- GIT
- Clean Code
- Scrum

<br>

### No frontend:

- HTML
- CSS
- JavaScript
- React (principal biblioteca para construção do site)
- Context API (bibliotexa de gerenciamento de estado global)
- React Router (para aplicar múltiplas rotas)
- Material-UI (biblioteca de UI com Material Design)
- Formik (criação dos formulários)
- Yup (validação dos formulários)
- React Testing Library (realizar os testes unitários)
- Cypress (desenvolvimento dos testes de e2e)
- Styled Components (biblioteca que permite escrever códigos CSS no JS)
- Responsividade e adaptação de aplicação web para front
- Keycloak (para implementação da autenticação)

<br>

### No backend:

- Java
- Springboot (estrutura de projeto)
- Maven (automação e gerenciamento de projeto Java)
- versionamento de API
- métodos HTTP
- padrão de projeto MVC
- Testes unitários
- JPA (mapeamento de objeto relacional)
- H2 (SQL)
- Swagger (documentação da API REST)
- Logging
- Keycloak (para implementação da autenticação e autorização)

<br>

### Integração:

- Docker

<br><br>

# Pré-requisitos para rodar a aplicação

Instalar
- docker
- mvn

<br><br>

## Como rodar a aplicação

No terminal, clone o projeto:

```bash
git clone
```

<br>

### Backend

Entre na pasta do backend:

```bash
cd Projetos/BackEnd/
```

Build a aplicação:

```bash
mvn clean install -DskipTests=true
```

Execute a aplicação via docker-compose:

```bash
docker-compose up
```

<br>

### Frontend

Num novo terminal, entre na pasta do frontend:

```bash
cd Projetos/FrontEnd_/
```

Execute a aplicação via docker-compose:

```bash
docker-compose up
```

<br>

Pronto, basta rodar a aplicação na porta indicada no terminal: [http://localhost:3000/](http://localhost:3000/)
- a aplicação estará autenticada nessa porta


<br><br>

## Contribuição

Contribuições com o projeto são muito apreciadas. Para isso:

- Faça um Fork do projeto

- Crie uma branch para sua feature

```bash
git checkout -b feature
```

- Adicione as mudanças

```bash
git add .
```

- _Commit_ as mudanças

```bash
git commit -m 'Adicionando a feature X'
```

- Faça o push da branch

```bash
git push origin feature
```

- Abra um Pull Request

<br><br>

## Licença

The [MIT License]() (MIT)

Copyright :copyright: 2021 - Projeto Final

<br><br>

## Desenvolvedoras :octocat:

<br>

<div align="center">

| [<img src="https://avatars.githubusercontent.com/u/47026392?s=460&u=8d55f59b971be6ff3db89146f223fe6cfacbf18c&v=4" width=115><br><sub>Amanda Brugiolo</sub>](https://github.com/abrugiolo) | [<img src="https://avatars.githubusercontent.com/u/40336369?s=460&v=4" width=115><br><sub>Emanuelle</sub>](https://github.com/manubf) | [<img src="https://avatars.githubusercontent.com/u/74935208?s=460&u=e7c6909558ba5031978f43ee77810c4191e05d75&v=4" width=115><br><sub>Milena Diniz</sub>](https://github.com/milena-diniz) | [<img src="https://avatars.githubusercontent.com/u/45580434?s=460&u=07188d0258859fc94b46983bcb85c09b4d7c5daf&v=4" width=115><br><sub>Rosana Rezende</sub>](https://github.com/rosanarezende) |
| :---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------: | :-----------------------------------------------------------------------------------------------------------------------------------: | :---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------: | :------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------: |

</div>
