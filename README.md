# Spring Boot JPA Project
[![NPM](https://img.shields.io/npm/l/react)](https://github.com/gabrielreisresende/springboot-jpa/blob/main/LICENSE)

## Descrição

Projeto para gerenciar o processo de pagamento de um produto utilizando Spring Boot para desenvolvimento e MySQL como base de dados. A aplicação conta com desenvolvimento em camadas Repositories, Services e Controllers, diversos relacionamentos entre as entidades e endpoints importantes para o usuário.

## Tecnologias Utilizadas

- Java 8
- Spring Boot
- Spring Data JPA
- Maven
- MySQL

## Funcionalidades

- Cadastro de entidades no banco de dados
- Consulta de entidades
- Atualização de entidades
- Exclusão de entidades

## Pré-requisitos

Antes de executar este projeto, certifique-se de ter o seguinte instalado em sua máquina:

- Java Development Kit (JDK) 8 ou superior
- Maven

## Como executar

1. Clone este repositório para o seu ambiente local:

   ```bash
   git clone https://github.com/gabrielreisresende/springboot-jpa.git

2. Navegue até o diretório raiz do projeto:
   ```bash
   cd springboot-jpa
  
3. Compile o projeto utilizando o Maven:
   ```bash
   mvn clean install

4. Execute o aplicativo:
   ```bash
   mvn spring-boot:run

5. O aplicativo será iniciado e estará disponível em http://localhost:8080.

## Configuração do banco de dados
Este projeto utiliza um banco de dados relacional para persistência dos dados. Certifique-se de configurar corretamente as propriedades do banco de dados no arquivo application.properties.
