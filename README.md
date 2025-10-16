# 📝 Task Manager API

Uma API RESTful para gerenciamento de tarefas e usuários. Ideal para equipes, grupos ou indivíduos que desejam organizar suas atividades de forma eficiente, com controle de acesso, atribuição de responsabilidades e acompanhamento do progresso.

---

# 🧠 Desafio
*O desafio é desenvolver uma API de gerenciamento de tarefas e usuários que possa ser utilizada por qualquer equipe, grupo ou indivíduo que deseje organizar suas atividades de forma eficiente. O sistema deve permitir o controle completo do ciclo de vida das tarefas, a gestão de usuários com diferentes níveis de acesso e a visualização clara do progresso das atividades.*

---

# 🎯 Objetivos do Sistema
*Criar e gerenciar usuários com autenticação segura.*

*Permitir a criação, consulta, atualização e exclusão de tarefas.*

*Controlar o status das tarefas (ex: pendente, em andamento, concluída).*

*Garantir segurança e integridade dos dados.*

---

## 📌 Escopo do Projeto

### ✅ Pré-requisitos

Este projeto tem como objetivo fornecer uma API simples e funcional para o gerenciamento de tarefas e usuários, com foco exclusivo nas operações básicas de CRUD (Create, Read, Update, Delete). Ele é ideal para fins educacionais, testes de integração, prototipagem de sistemas ou como base para projetos mais complexos.

Não há sistema de autenticação ou controle de acesso implementado, todas as rotas estão abertas para facilitar o uso e a integração com outras aplicações ou front-ends em desenvolvimento.

---

### 🔧 Requisitos Funcionais

- **Criar Usuário**  
  Permitir o cadastro de novos usuários com informações como nome, e-mail e função. Cada usuário pode ser associado a uma ou mais tarefas.

- **Listar Usuários**  
  Retornar uma lista de todos os usuários cadastrados, com seus respectivos dados e tarefas atribuídas (se houver).

- **Atualizar Usuário**  
  Permitir a edição dos dados de um usuário existente, como nome ou e-mail.

- **Deletar Usuário**  
  Remover um usuário do sistema. Caso ele tenha tarefas associadas, essas podem ser excluídas ou mantidas conforme a lógica de negócio definida.

---

### 🛠️ Requisitos Não Funcionais

- **Performance**  
  A API deve responder às requisições em até 2 segundos, mesmo com grande volume de dados.

- **Segurança**  
  Autenticação via JWT e proteção das rotas com middleware de autorização.

- **Disponibilidade**  
  Sistema acessível 24/7, com tolerância a falhas e logs de erro.

- **Backup Automático**  
  Cópia de segurança diária do banco de dados em ambiente externo ou cloud.

- **Usabilidade da API**  
  Endpoints bem definidos e documentados com Swagger para facilitar integração.

---

## 📅 Planejamento de Entregas  

- **SPRINT 1:** 18/09 a 25/09 ✅  
- **SPRINT 2:** 25/09 a 02/10 ✅  
- **SPRINT 3:** 02/10 a 09/10 ✅

---

## 🚀 Tecnologias Utilizadas

- HTML (Estrutura)
- CSS (Estilização)
- MySQL (Banco de Dados)
- PHP (Movimentação de Informação de forma dinâmica)

---

## 📂 Metodologia Utilizada  

- **Metodologia Ágil:** Framework Scrum/Kanban</a>

---



