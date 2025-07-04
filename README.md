# Contact Book - Agenda de Contatos

Uma aplicação web fullstack para gerenciamento de contatos pessoais com React (frontend) e Node.js (backend).

![Preview da aplicação](public/screenshot.png)


## 🚀 Funcionalidades

- ✅ CRUD completo de contatos
- ✅ Autenticação de usuários
- ✅ Upload de fotos de perfil
- ✅ Busca avançada e filtros
- ✅ API RESTful
- ✅ Persistência em banco de dados


## 🛠 Tecnologias

**Frontend**:
- React.js + TypeScript
- Styled Components
- React Hook Form
- Context API
- Axios

**Backend**:
- Node.js + Express
- MongoDB (ou outro banco configurado)
- JWT para autenticação
- Multer para uploads


## ⚙️ Instalação

1. Clone o repositório:
```bash
git clone https://github.com/luizf-p/contact-book.git
cd contact-book 
```
2. Instale as dependências:
npm install

3. Configure o arquivo .env no diretório server:
CONNECTIONSTRING = sua_string_de_conexao


## 🚦 Execução

Primeiro terminal (Backend):
```bash
node server.js
```

Segundo terminal (Frontend):
npm start

### Após iniciar ambos, acesse no navegador:
#### URL do frontend
http://localhost:3000

#### Ou via linha de comando (Linux/Mac)
open http://localhost:3000  # Mac
xdg-open http://localhost:3000  # Linux


### 📝 Licença
- MIT License - Livre para uso
- © 2025 Luiz Fernando


