# Spring Boot JPA Project
[![NPM](https://img.shields.io/npm/l/react)](https://github.com/gabrielreisresende/springboot-jpa/blob/main/LICENSE)

Este projeto é um exemplo simples de uma aplicação Spring Boot com o uso do Spring Data JPA.

## Descrição

Este projeto demonstra a configuração básica de uma aplicação Spring Boot que utiliza o Spring Data JPA para persistência de dados em um banco de dados relacional.

## Tecnologias Utilizadas

- Java 8
- Spring Boot
- Spring Data JPA
- Maven

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
