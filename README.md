## 🚀 ProjectREST - API REST com Spring Boot
Uma API REST completa desenvolvida com Spring Boot para gerenciamento de usuários, demonstrando boas práticas de desenvolvimento backend e arquitetura limpa.

## 📋 Sobre o Projeto

Esta é uma aplicação backend que fornece endpoints RESTful para operações CRUD (Create, Read, Update, Delete) de usuários, implementando uma arquitetura em camadas com separação de responsabilidades.

## 🛠 Tecnologias Utilizadas

Java 17 - Linguagem de programação

Spring Boot 3.5.6 - Framework principal

Spring Data JPA - Persistência de dados

Spring Web - API REST

MySQL - Banco de dados relacional

Maven - Gerenciamento de dependências

Spring Boot DevTools - Desenvolvimento

## 🏗 Arquitetura do Projeto

<img width="383" height="220" alt="image" src="https://github.com/user-attachments/assets/d8450979-481e-4a50-a15c-8067ffd5cf68" />

## 📁 Estrutura de Camadas

Controller: Camada de apresentação (REST endpoints)

Service: Camada de negócio e regras de aplicação

Repository: Camada de acesso a dados (Spring Data JPA)

Model: Camada de entidades de domínio

## 🚀 Como Executar

#### Pré-requisitos

Java 17

MySQL

Maven

### Configuração do Banco de Dados

CREATE DATABASE projectrest;

### Configuração da Aplicação

Edite src/main/resources/application.properties:

spring.datasource.url=jdbc:mysql://localhost:3306/projectrest
spring.datasource.username=seu_usuario
spring.datasource.password=sua_senha

## Executando a Aplicação

### Clonar o repositório
git clone https://github.com/seu-usuario/projectrest.git

### Navegar para o diretório
cd projectrest

### Executar com Maven
./mvnw spring-boot:run

### Ou compilar e executar
./mvnw clean package
java -jar target/projectrest-0.0.1-SNAPSHOT.jar

A aplicação estará disponível em: http://localhost:8080
