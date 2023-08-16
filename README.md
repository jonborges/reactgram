# ReactGram

# Miniblog - Projeto do Curso "Hora de Codar"

Este projeto é um miniblog desenvolvido como parte do curso "Hora de Codar", com o objetivo de praticar o desenvolvimento web com React e Node.js.

## Funcionalidades

- Registro de usuários
- Autenticação de usuários
- Visualização de posts
- Criação, edição e exclusão de posts (apenas usuários autenticados)
- Adição e remoção de comentários em posts
- Pesquisa de posts por título

## Tecnologias Utilizadas

- Frontend:
  - React
  - React Router
 
- Backend:
  - Node.js
  - MongoDB (banco de dados)
## Como Executar o Projeto

1. Clone este repositório: `git clone https://github.com/seu-usuario/nome-do-repositorio.git`
2. Navegue até a pasta do projeto: `cd nome-do-repositorio`
3. Configure as variáveis de ambiente no arquivo `.env` (consulte o arquivo `.env.example`)
```bash
# Crie um arquivo .env e configure as váriaveis de ambiente
# API
REACT_APP_API_URL=http://localhost:5000/api
REACT_APP_API_UPLOADS=http://localhost:5000/uploads
```

```bash
# Crie um arquivo .env e configure as váriaveis de ambiente
PORT=5000
WEB_HOST=http://localhost:3000

# MongoDB
DB_USER=
DB_PASS=

# JWT
JWT_SECRET=

4. Instale as dependências do frontend: `cd client && npm install`
5. Instale as dependências do backend: `cd server && npm install`
6. Inicie o servidor backend: `cd server && npm start`
7. Inicie o aplicativo frontend: `cd client && npm start`
8. Acesse a aplicação no seu navegador: `http://localhost:3000`

## Licença

Este projeto é licenciado sob a [MIT License](LICENSE).

---

Projeto desenvolvido como parte do curso "Hora de Codar". Saiba mais em: [https://www.horadecodar.com.br](https://www.horadecodar.com.br)

@https://github.com/jonborges






# reactgram
