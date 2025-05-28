# 🖥️ To-do Front-end

Interface web para o gerenciamento de tarefas, conectada à [To-do API]([https://github.com/Matheus-Figueiredo-Dev/Todo-Api]). Esta aplicação consome os dados da API para listar, criar, editar e remover tarefas. O front-end não foi desenvolvido por mim originalmente, mas realizei modificações para integrá-lo com a minha API em Node.js + TypeScript.

---

## ⚙️ Tecnologias Utilizadas

- **React**
- **Axios** — Requisições HTTP
- **Vite** — Bundler leve e rápido
- **styled-components** — Estilização de componentes
- **Hooks (useState, useEffect, useRef, useNavigate)**

---

## 🔧 Funcionalidades

- Listagem de tarefas;
- Criação de nova tarefa;
- Edição de tarefas existentes;
- Remoção de tarefas;

---

🧠 Observações
Este projeto foi utilizado como base visual e adaptado para se conectar com minha própria API. A lógica de integração, endpoints e testes de comunicação foram feitos por mim como exercício de back-end e consumo de APIs REST.

![image](https://github.com/user-attachments/assets/8ccb753d-443a-45a7-adac-90168d3c8acb)

## 🚀 Como rodar

### 1. Clone o repositório

```bash
git clone https://github.com/Matheus-Figueiredo-Dev/Todo-Interface

2. Instale as dependências
npm install
3. Configure a URL da API
Edite o arquivo onde a URL base da API está definida (http://localhost:5173/) e aponte para o back-end:

4. Inicie o projeto
npm run dev
