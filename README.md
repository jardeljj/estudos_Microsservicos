# 📌 Estudos sobre Microsserviços com Padrão Saga e Transações Distribuídas

## 📖 Sobre o Projeto
Este repositório tem como objetivo estudar e aplicar conceitos avançados de arquitetura de microsserviços, com foco em transações distribuídas e implementação do padrão Saga, tanto na abordagem orquestrada quanto coreografada. Através de um projeto prático com Java 17, Spring Boot 3, Apache Kafka, PostgreSQL e MongoDB, são exploradas boas práticas e estratégias para garantir consistência e resiliência em sistemas distribuídos.

## 🚀 Tecnologias Utilizadas
- ☕ Java 17
- 🌱 Spring Framework 3
- 🎨 Thymeleaf
- 🐳 Docker & Docker Compose
- 📬 Apache Kafka
- 🐘 PostgreSQL
- 🍃 MongoDB

## O que será aplicado

- 📚 Conceitos e estratégias para tratamento de transações distribuídas
- 🤖 Implementação do padrão Saga Orquestrado com Java, Spring Boot e Kafka
- 🎭 Diferenças entre os padrões Orquestrado vs. Coreografado
- 🧱 Boas práticas na arquitetura de microsserviços
- 🔀 Utilização de Apache Kafka na orquestração de eventos
- 🗃️ Integração com bancos de dados PostgreSQL e MongoDB
- 🧪 Tratamento de falhas em ambientes distribuídos
- 🛠️ Utilização do padrão Outbox
- 🎁 Seção bônus com implementação do padrão Saga Coreografado

## 🏗️ Arquitetura
O projeto contempla a construção de 5 microsserviços, sendo:

  - 1 microsserviço orquestrador da saga
  - 2 microsserviços participantes
  - 3 microsserviço de realização de pedido

Toda a arquitetura é gerenciada via Docker Compose para facilitar a execução e o isolamento dos serviços.

## ▶️ Como Rodar o Projeto
1. **📥 Clone o repositório**
   ```sh
   git clone https://github.com/jardeljj/estudos_Microsservicos.git
   cd estudos_Microsservicos
   ```

2. **🐳 Suba os containers**
   ```sh
   docker-compose up --build
   ```

3. **🌍 Acesse os serviços**
   Os microsserviços estarão disponíveis nas portas definidas no docker-compose.yml. Certifique-se de que as portas não estejam em uso no seu ambiente local.

## 📚 Referências
- [📜 Documentação do Spring](https://docs.spring.io/spring-framework/docs/current/reference/html/)
- [📌 Guia do Spring MVC](https://docs.spring.io/spring-framework/docs/current/reference/html/web.html)
- [🐘 PostgreSQL Docs](https://www.postgresql.org/docs/)
- [🍃 MongoDB Docs](https://www.mongodb.com/pt-br/docs/)

## 🚧 Status do Projeto
🚀 Em andamento 🚧

-JardelDev

