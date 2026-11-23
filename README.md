# Banco Digital API (`banco-digital-api`)

Uma aplicação web full-stack de banco digital desenvolvida em Java, projetada para simular operações financeiras essenciais com foco em segurança, desempenho e arquitetura limpa sem dependência de frameworks pesados.

---

## Funcionalidades

- **Gestão de Usuários:** Cadastro de novos clientes (`cadastro.html`) com validação de dados e armazenamento seguro de credenciais.
- **Autenticação e Segurança:** Login (`login.html`) protegido com criptografia de senhas via **BCrypt** e geração de tokens **JWT (JSON Web Token)** para controle de sessão.
- **Painel do Cliente (`dashboard.html`):** Interface para consulta de saldo, acompanhamento de movimentações e execução de operações bancárias.
- **API RESTful:** Rotas estruturadas para comunicação entre o front-end e a camada de persistência.

---

## 🛠️ Tecnologias Utilizadas

- **Back-end:** Java, [Javalin](https://javalin.io/) (Micro-framework web)
- **Segurança:** JWT (JSON Web Token) & BCrypt
- **Persistência de Dados:** JDBC (Java Database Connectivity)
- **Front-end:** HTML5, CSS3, JavaScript (páginas `index`, `cadastro`, `login` e `dashboard`)
- **Gerenciador de Dependências:** Maven
