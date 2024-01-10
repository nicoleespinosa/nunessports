# Nunes Sports

Este repositório contém os código-fontes de uma aplicação usando React no frontend, Spring Boot no backend e MySQL como banco de dados.

## Executando a Aplicação

### 1. Extrair os Arquivos ZIP

- Baixe o código-fonte do repositório e extraia os arquivos para um diretório de sua escolha.

### 2. Configurar o Banco de Dados MySQL

- Certifique-se de ter o MySQL instalado e em execução em sua máquina.
- Crie um banco de dados chamado `everymind`.

### 3. Configurar o Backend (Spring Boot)

- Abra o projeto Spring Boot no seu IDE favorito (por exemplo, IntelliJ, Eclipse).
- Altere as configurações do banco de dados no arquivo `application.properties` para corresponder às suas credenciais do MySQL.

```
spring.datasource.url=jdbc:mysql://localhost:3306/everymind
spring.datasource.username=seu_usuario
spring.datasource.password=sua_senha
```
Execute a classe principal NunessportsApplication para iniciar o servidor Spring Boot.
### 4. Configurar o Frontend (React)

Abra o terminal no diretório do projeto React (frontend).
Execute o seguinte comando para instalar as dependências:
```
npm install
```

Execute o seguinte comando para iniciar o servidor de desenvolvimento:
```
npm start
```
5. Acessar a Aplicação
Abra o navegador e acesse `http://localhost:3000` para visualizar a aplicação React.

## Observações Importantes
Certifique-se de que o backend esteja sendo executado antes de iniciar o frontend, pois o frontend faz chamadas à API fornecida pelo backend.
