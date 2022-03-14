# Objetivo 🟢


- Geral: Proteger os recursos da aplicação.

- Específico: Restringir a execução do servlet: ProcessarServlet apenas aos usuários autorizados. Solicitar a autenticação de credenciais para liberação do recurso protegido.

# Ferramentas ⛏

- Java 8
- Apache Tomcat 8.5
- IntelliJ IDEA 2021.3.2 (Ultimate Edition)

# Procedimentos 👇

- Foram definidos usuários com suas respectivas senhas, já considerando seu tipo/nível de acesso;

- Solicitar ao usuário a inserção de suas credenciais;


📢 Cada servidor, possui seu modo especifico de configurção, neste projeto foi considerado para o Apache Tomcat 8.5.


# Configurando a autenticação no Tomcat

- Ir no diretório em que está localizado os arquivos do servidor: C:\apache-tomcat-8.5.76\conf e acessar o arquivo: tomcat-users.xml para inserção do usuario e role.


# Configurando a autenticação na aplicação

- Configurar no arquivo web.xml conforme o código fonte.
