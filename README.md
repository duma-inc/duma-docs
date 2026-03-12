# 📚 DUMA - Documentação do Sistema

## 🏫 O que é o DUMA?

DUMA é uma **EdTech AI-First** que unifica o melhor do aprendizado tradicional com tecnologia de ponta.

O produto DUMA é uma junção de métodos de aprendizagem pensados para proporcionar uma experiência mais **acelerada e assertiva**, unindo:
- 👥 Encontros práticos ao vivo em grupo
- 🤖 IA como centralizadora das atividades
- 🧑‍🏫 Mentores humanos para motivação e dúvidas complexas
- 🎮 Gamificação
- 📹 Cursos pré-gravados
- 📊 Acompanhamento de progresso humano + IA

### 🧠 Método
Baseado no **Kumon** (elevação gradual de nível) e **Duolingo** (repetição espaçada), com personalização contínua via IA.

### 📚 Habilidades Suportadas
Idiomas, música, xadrez, tecnologia, matérias escolares, concursos e vestibulares.

---

## 🏗️ Repositórios

| Repositório | Descrição |
|-------------|-----------|
| [`duma-backend`](../duma-backend) | API principal em Spring Boot (Java 21) |
| [`duma-frontend-ava`](../duma-frontend-ava) | Frontend do aprendiz em Next.js |
| [`duma-frontend-adm`](../duma-frontend-adm) | Frontend de gestão em Next.js |
| [`duma-infra`](../duma-infra) | Infraestrutura Docker, Nginx, scripts |
| [`duma-docs`](.) | Documentação geral do sistema |

---

## 📄 Documentos

| Arquivo | Descrição |
|---------|-----------|
| [`agents.md`](./agents.md) | Agentes de IA planejados e arquitetura do microsserviço |

---

## 🧱 Stack Tecnológica

| Camada | Tecnologia |
|--------|-----------|
| **Backend** | Java 21 + Spring Boot 3 |
| **Frontend AVA** | Next.js + React |
| **Frontend ADM** | Next.js + React |
| **Microsserviço IA** | JS/Python (LangChain) |
| **Banco Relacional** | PostgreSQL 16 |
| **Banco Não Relacional** | MongoDB 7 (trilhas, exercícios) |
| **Cache** | Redis 7 |
| **Mensageria** | RabbitMQ 3 |
| **Gateway** | Nginx Alpine |
| **Containerização** | Docker + Docker Compose |
