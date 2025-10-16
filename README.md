# task-manager-api

## 🧠 Desafio
*O desafio é desenvolver uma API de gerenciamento de tarefas e usuários que possa ser utilizada por qualquer equipe, grupo ou indivíduo que deseje organizar suas atividades de forma eficiente. O sistema deve permitir o controle completo do ciclo de vida das tarefas, a gestão de usuários com diferentes níveis de acesso e a visualização clara do progresso das atividades.*

---

# 🎯 Objetivos do Sistema
*Criar e gerenciar usuários com autenticação segura.*

*Permitir a criação, consulta, atualização e exclusão de tarefas.*

*Controlar o status das tarefas (ex: pendente, em andamento, concluída).*

*Garantir segurança e integridade dos dados.*

---

# 📝 Task Manager API

Uma API RESTful para gerenciamento de tarefas e usuários. Ideal para equipes, grupos ou indivíduos que desejam organizar suas atividades de forma eficiente, com controle de acesso, atribuição de responsabilidades e acompanhamento do progresso.

---

## 📌 Escopo do Projeto

### ✅ Pré-requisitos

---

### 🔧 Requisitos Funcionais

- **Cadastro de Usuários**  
  Criar, editar, listar e excluir usuários com campos como nome, e-mail, senha e tipo de acesso.

- **Autenticação e Autorização**  
  Login com geração de token JWT e controle de permissões por perfil (ex: admin, colaborador).

- **CRUD de Tarefas**  
  Criar, editar, listar e excluir tarefas com título, descrição, status, prioridade, prazo e responsável.

- **Atribuição de Tarefas**  
  Associar tarefas a usuários específicos e permitir reatribuições.

- **Filtros e Busca**  
  Consultar tarefas por status, usuário, prioridade ou intervalo de datas.

- **Histórico de Atualizações**  
  Registrar alterações nas tarefas (ex: mudança de status, edição de prazo).

- **Comentários nas Tarefas**  
  Permitir que usuários adicionem observações ou atualizações nas tarefas.

- **Notificações Internas**  
  Alertar usuários sobre novas tarefas ou mudanças relevantes.

- **Relatórios Simples**  
  Gerar listagens de tarefas por usuário, status ou período.

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

## 🚀 Tecnologias Utilizadas

- HTML
- CSS
- MySQL
- PHP


---



