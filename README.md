# 👋 Olá, eu sou o Matheus Azevedo

🎓 Formado em Análise e Desenvolvimento de Sistemas  
🎓 Estudante de Ciência da Computação (UNINTER - 1º semestre)

💻 Desenvolvedor Backend focado em Java e Spring Boot  
🚀 Atualmente construindo projetos com arquitetura de microserviços

## 🧠 Sobre mim

Sou um desenvolvedor em início de carreira, focado em backend, com experiência prática no desenvolvimento de APIs REST, autenticação com JWT e construção de sistemas distribuídos.

Tenho trabalhado em projetos que simulam cenários reais de mercado, utilizando microserviços, Docker e integração entre múltiplos serviços.

## 🛠️ Tecnologias e Ferramentas

### Backend
- Java 17
- Spring Boot
- Spring Security
- JPA / Hibernate
- OpenFeign

### Banco de Dados
- PostgreSQL
- MongoDB

### APIs e Arquitetura
- APIs REST
- Autenticação com JWT
- Documentação com Swagger
- Microserviços

### Testes
- JUnit
- Mockito

### DevOps e Ferramentas
- Docker
- Docker Compose
- Git
- GitHub
- GitHub Actions (CI/CD)

## 🚀 Projetos em destaque

### 🔗 Sistema de Agendamento de Tarefas (Microserviços)
Sistema completo baseado em arquitetura de microserviços, com autenticação distribuída, comunicação entre serviços e execução via Docker Compose.

💡 Principais funcionalidades:
- Cadastro e autenticação de usuários com JWT
- Criação e gerenciamento de tarefas com data/hora
- Processamento assíncrono com job agendado
- Envio automático de notificações por e-mail

🏗️ Arquitetura:
- BFF (Backend-for-Frontend) para orquestração
- Microserviços independentes (`user`, `scheduler`, `notification`)
- Comunicação via OpenFeign
- Integração com PostgreSQL (usuários) e MongoDB (tarefas)

⚙️ Infraestrutura:
- Docker + Docker Compose (ambiente completo)
- Comunicação entre containers via DNS interno
- Variáveis de ambiente e configuração por serviço

📌 Destaques técnicos:
- Autenticação distribuída com JWT
- Integração entre múltiplos serviços
- Separação de responsabilidades por domínio
- Projeto documentado com diagramas e execução completa via Docker

➡️ [Task-Scheduler-System](https://github.com/theusazevedd/Task-Scheduler-System)

📌 O sistema é composto por múltiplos serviços independentes, cada um responsável por um domínio específico:

- `task-bff` -> camada de orquestração (Backend-for-Frontend)
- `user-service` -> gerenciamento de usuários e autenticação
- `task-scheduler-service` -> lógica de criação e agendamento de tarefas
- `notification-service` -> envio de notificações por e-mail

## 📚 Cursos e Formação Complementar

- Java Programação Orientada a Objetos - Udemy
- Treinamento Fullstack - Javanauta

## 📫 Contato

💼 LinkedIn:  
[linkedin.com/in/matheus-azevedo-292b743b5](https://www.linkedin.com/in/matheus-azevedo-292b743b5/)
