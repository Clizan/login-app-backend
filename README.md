# login-app-backend

Backend para autenticação e gerenciamento de usuários.

## Tecnologias Utilizadas

- Java
- Spring Boot
- Maven

## Como Rodar

### Pré-requisitos

- Java 17+ instalado
- Maven instalado (ou utilize o wrapper `mvnw` incluso no projeto)
- (Opcional) Docker, caso queira rodar o backend em container

### Passos para execução

1. **Clone o repositório:**
   ```sh
   git clone https://github.com/Clizan/login-app-backend.git
   cd login-app-backend
   ```

2. **Execute com Maven:**
   ```sh
   ./mvnw spring-boot:run
   ```
   Ou, se preferir:
   ```sh
   mvn spring-boot:run
   ```

3. **A API estará disponível em:**  
   ```
   http://localhost:8080
   ```

## Integração com o Frontend (login-page)

Se você preferir, pode clonar o frontend chamado **login-page**, siga os passos abaixo para rodar ambos juntos:

1. Clone o repositório do frontend:
   ```sh
   git clone https://github.com/Clizan/login-page.git
   cd login-page
   ```

2. Siga as instruções do README do frontend para rodá-lo (geralmente com `npm install` e `npm start`).

3. Certifique-se de que o frontend esteja configurado para se comunicar com o backend em `http://localhost:8080` (ajuste as variáveis de ambiente do frontend se necessário).

## Estrutura do Projeto

- `src/` - Código fonte da aplicação
- `pom.xml` - Configurações do Maven
- `mvnw`, `mvnw.cmd` - Maven Wrapper para facilitar build

## Contribuição

Pull requests são bem-vindos! Sinta-se livre para abrir issues e sugerir melhorias.

## Licença

[MIT](LICENSE) (Atualize para a licença apropriada)
