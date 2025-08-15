# 📚 Literalura

<div align="center">

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Java Version](https://img.shields.io/badge/Java-8%2B-blue)](https://www.java.com/)
![GitHub repo size](https://img.shields.io/github/repo-size/rodrigoborge/Literalura)
![GitHub code size in bytes](https://img.shields.io/github/languages/code-size/rodrigoborge/Literalura)

</div>

**Literalura** é uma aplicação Java desenvolvida durante o programa **ONE - Oracle Next Education** em parceria com a **Oracle** e **Alura**.  
O projeto consome dados de uma API de livros, armazena em um banco PostgreSQL e permite gerenciar essas informações via aplicação console.


## 🚀 Tecnologias Utilizadas

- **Java 8+**
- **Spring Boot**
- **Spring Data JPA**
- **PostgreSQL**
- **Maven**
- **API externa** para consulta de livros

## 📌 Funcionalidades

- Buscar livros em uma API externa  
- Armazenar e listar livros no banco de dados  
- Listar autores e filtrar por critérios  
- Exibir estatísticas de leitura  

## 📂 Estrutura do Projeto

O projeto está organizado da seguinte forma:

- **principal**: contém a classe principal responsável pela execução.  
- **model**: inclui as entidades e DTOs (`Livro`, `Autor`, `LivroDTO`, `AutorDTO`).  
- **repository**: possui as interfaces de repositório (Spring Data JPA).  
- **service**: engloba os serviços, como `ConsumoAPI` e `ConverteDados`.

## 🔧 Instalação e Execução

1. **Clone o repositório** e acesse a pasta

2. **Configure o banco de dados** no arquivo `application.properties` com sua URL, usuário e senha do PostgreSQL.

3. **Execute o projeto**:  
   `mvn spring-boot:run`

## 👤 Autor

Desenvolvido por **[Nicholas Lourenco](https://github.com/NiikeBR)**.

## 📜 Licença

Este projeto está sob a licença [MIT](LICENSE).
