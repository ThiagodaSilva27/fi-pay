# 🏦 Fi-Pay

🚀 **Sistema de gerenciamento de pagamentos e análise de dados para Growth Marketing, utilizando Vue.js, Nuxt.js, Node.js, MySQL, AWS e Kibana.**

---

## 📌 Tecnologias Utilizadas

- **Frontend**: Vue.js, Nuxt.js, HTML, CSS
- **Backend**: Node.js, TypeScript, Express
- **Banco de Dados**: MySQL
- **Infraestrutura**: Linux, Docker, AWS (SQS, S3)
- **Monitoramento**: Kibana
- **SEO & Marketing**: Google Analytics, Tag Manager
- **Testes Automatizados**: Jest, Vitest, Cypress
- **Versionamento**: Git (seguindo um fluxo organizado)
- **Diferencial**: Integração com WordPress e PHP

---

## ⚙️ Como Rodar o Projeto Localmente

### 1️⃣ Clone o repositório:
```bash
 git clone https://github.com/ThiagodaSilva27/fi-pay.git
 cd fi-pay
```

### 2️⃣ Instale as dependências:
```bash
 npm install
```

### 3️⃣ Configure as variáveis de ambiente:
Crie um arquivo `.env` e defina as configurações necessárias:
```env
DATABASE_URL=mysql://usuario:senha@localhost:3306/fi_pay
AWS_ACCESS_KEY_ID=xxx
AWS_SECRET_ACCESS_KEY=xxx
```

### 4️⃣ Execute o backend:
```bash
 npm run dev
```

### 5️⃣ Execute o frontend:
```bash
 cd frontend
 npm install
 npm run dev
```

---

## 📂 Estrutura do Projeto
```
fi-pay/
│── backend/        # Código do servidor (Node.js, Express)
│── frontend/       # Aplicação frontend (Vue.js, Nuxt.js)
│── database/       # Scripts de migração do banco de dados
│── tests/          # Testes automatizados (Jest, Vitest, Cypress)
│── docker/         # Configuração do Docker e Compose
│── .gitignore      # Arquivos ignorados no versionamento
│── README.md       # Documentação do projeto
```

---

## 🔥 Principais Funcionalidades
✅ Emissão e gestão de pagamentos via API RESTful  
✅ Dashboard com análise de dados para Growth Marketing  
✅ Integração com serviços da AWS (S3 para armazenar arquivos, SQS para filas)  
✅ Monitoramento com Kibana para logs e métricas  
✅ Integração opcional com WordPress e PHP  
✅ Testes automatizados garantindo a robustez do código  

---

## 🚀 Fluxo de Commits e Versionamento

1. **Criação de Branches:**
   - `main` → Versão estável
   - `dev` → Desenvolvimento
   - `feature/nome-da-feature` → Para cada funcionalidade nova

2. **Padrão de Commits:**
   - `feat:` Nova funcionalidade
   - `fix:` Correção de bug
   - `refactor:` Refatoração de código
   - `test:` Adição ou alteração de testes

Exemplo:
```bash
git commit -m "feat: adicionar integração com AWS S3"
```

---

## 📜 Licença
Este projeto está sob a licença MIT.

