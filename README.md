# spring-mppr

Um projeto Spring Boot simples para demonstrar uma API básica.

## Descrição

Este projeto é uma aplicação Spring Boot que expõe um endpoint de API REST para fins de demonstração. Ele foi desenvolvido utilizando Java e o framework Spring.

A aplicação possui um controlador principal (`UsuarioController`) que responde a requisições na rota `/api`.

## Tecnologias Utilizadas

- **Java**: Linguagem de programação principal.
- **Spring Boot**: Framework para facilitar a criação de aplicações Spring autônomas e prontas para produção.
- **Spring MVC**: Para criação de APIs REST.
- **Maven**: Gerenciador de dependências e build (geralmente usado em projetos Spring Boot).

## Como Executar o Projeto

1.  **Pré-requisitos:**

    - JDK (Java Development Kit) instalado (versão 8 ou superior recomendada).
    - Maven ou Gradle instalado (se for gerenciar as dependências manualmente ou realizar builds específicas).

2.  **Clonar o repositório:**

    ```bash
    git clone [https://github.com/tmbottamedi/spring-mppr.git](https://github.com/tmbottamedi/spring-mppr.git)
    cd spring-mppr
    ```

3.  **Executar a aplicação:**
    A forma mais simples de executar uma aplicação Spring Boot é através da classe principal que contém o método `main`. Neste caso, é a classe `ApiApplication.java`.
    - Se você estiver usando uma IDE (como IntelliJ IDEA, Eclipse, VS Code com extensões Java), geralmente pode clicar com o botão direito na classe `ApiApplication` e selecionar "Run" ou "Debug".
    - Alternativamente, você pode usar o wrapper do Maven (se incluído) ou o Maven local:
      ```bash
      ./mvnw spring-boot:run
      ```
      ou
      ```bash
      mvn spring-boot:run
      ```

A aplicação será iniciada e estará acessível, por padrão, em `http://localhost:8080`.

## Endpoints da API

A API expõe os seguintes endpoints:

- **`GET /api/teste`**
  - **Descrição:** Retorna uma mensagem de boas-vindas.
  - **Resposta de Sucesso (200 OK):**
    ```
    Bem vindo a API
    ```
