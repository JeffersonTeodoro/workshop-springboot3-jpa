# Workshop Spring Boot 3 com JPA

![Spring Boot](https://img.shields.io/badge/Spring%20Boot-3.0-green?style=flat-square) ![Java](https://img.shields.io/badge/Java-17-blue?style=flat-square) ![JPA](https://img.shields.io/badge/JPA-Hibernate-orange?style=flat-square)

## 🚀 Visão Geral

Este projeto é uma iniciativa de estudo que explora o uso do **Spring Boot 3** em conjunto com **JPA (Java Persistence API)** para criar um sistema de gerenciamento de pedidos e produtos. O foco está em aplicar práticas modernas de desenvolvimento Java, utilizando as últimas versões dessas tecnologias.

## 🛠️ Tecnologias Utilizadas

* **Java 17**: Linguagem de programação principal do projeto.
* **Spring Boot 3**: Framework para criação de aplicativos Java baseados em Spring.
* **JPA (Hibernate)**: API Java para gerenciamento de persistência de dados.
* **Maven**: Gerenciador de dependências e build.

## 📦 Funcionalidades Implementadas

* **Gerenciamento de Pedidos e Produtos**: Criação, leitura, atualização e exclusão (CRUD) de pedidos e produtos utilizando entidades e repositórios JPA.
* **Perfis de Execução**: Configuração de diferentes perfis para ambientes de desenvolvimento e produção.
* **Manipulação de Datas e Timestamps**: Implementação de rastreamento de criação e atualização de registros.
* **Relacionamentos de Entidades**: Estabelecimento de relacionamentos entre pedidos e produtos.
* **Tratamento de Exceções**: Implementação de tratamento de exceções personalizado para uma API robusta.

## ⚙️ Como Executar o Projeto

### Pré-requisitos

* JDK 17 ou superior instalado.
* Maven 3.8 ou superior instalado.

### Passos para Execução

1. Clone o repositório:

   ```bash
   git clone https://github.com/JeffersonTeodoro/workshop-springboot3-jpa.git
   cd workshop-springboot3-jpa
   ```

2. Compile e execute o projeto:

   ```bash
   ./mvnw spring-boot:run
   ```

3. Acesse a aplicação em [http://localhost:8080](http://localhost:8080).

## 🗂️ Estrutura do Projeto

```plaintext
workshop-springboot3-jpa/
├── .gitignore
├── LICENSE
├── mvnw
├── mvnw.cmd
├── pom.xml
└── src/
    └── main/
        ├── java/
        │   └── com/
        │       └── exemplo/
        │           ├── controller/
        │           ├── model/
        │           ├── repository/
        │           └── service/
        └── resources/
            ├── application.properties
            └── application-dev.properties
```

## 📘 Documentação Adicional

Para mais detalhes sobre o Spring Boot 3 e JPA, consulte a documentação oficial:

* [Spring Boot 3 Documentation](https://docs.spring.io/spring-boot/docs/current/reference/html/)
* [Java Persistence API (JPA) Documentation](https://docs.oracle.com/javaee/7/tutorial/persistence-intro.htm)

---

Este README fornece uma visão clara e profissional do projeto, destacando suas tecnol
