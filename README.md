# Projeto de API para Tela de Cadastro

Este projeto faz parte de um checkpoint proposto pelo professor de BackEnd, **Fábio Amaral**. O objetivo é desenvolver uma API para uma tela de cadastro, utilizando Node.js e MongoDB para armazenar as informações de cadastro.

## Tecnologias Utilizadas

- Node.js - Servidor backend
- MongoDB - Banco de dados para armazenamento
- Express - Framework para rotas e middleware no Node.js
- Prisma - ORM para trabalhar com o banco de dados de maneira mais eficiente
- Thunder Client - Ferramenta para testar as rotas HTTP (usada no desenvolvimento)
- React - Frontend (disponível em outro repositório)

## Como Utilizar

1. Clone este repositório (Backend):
   ```bash
   git clone <URL-deste-repositorio>
   ```
2. Clone o repositório do Frontend (React):
   O frontend foi desenvolvido separadamente, utilizando React. Para isso, clone o repositório correspondente:
   ```bash
   `git clone <URL-do-repositorio-do-frontend>`
   ```
3. Clone o repositório do Frontend (React):
   O frontend foi desenvolvido separadamente, utilizando React. Para isso, clone o repositório correspondente:
   ```bash
   git clone <URL-do-repositorio-do-frontend>
   ```

4. Instalar dependências:
   - Para o backend (dentro da pasta do projeto clonado):
   ```bash
   `npm install`
   ```
   - Para o frontend, dentro do repositório React:
   ```bash
   `npm install`
   ```

5. Configuração das conexões:
   Conecte o backend com o banco de dados MongoDB através do arquivo `.env`. Você precisará definir as variáveis de ambiente necessárias para a conexão com o MongoDB e configurar o Prisma adequadamente. Certifique-se de que o frontend está configurado para se comunicar corretamente com o backend. O backend estará rodando na porta `3000` (ou outra porta que você preferir), e o frontend deve enviar as requisições HTTP para essa porta.

6. Testar a API:
   Você pode testar os endpoints da API utilizando o Thunder Client ou Postman. As funcionalidades disponíveis são:
   - Adicionar - Adiciona um novo cadastro.
   - Editar - Permite editar um cadastro existente (testado via Thunder Client).
   - Excluir - Remove um cadastro existente.

7. Rodar o projeto:
   - Para iniciar o backend: `npm start`
   - Para rodar o frontend, siga as instruções no repositório de frontend.

## Funcionalidades da API

- Adicionar Cadastro: Insere um novo usuário no banco de dados.
- Editar Cadastro: Permite a edição de informações já cadastradas (funcionalidade testada via Thunder Client).
- Excluir Cadastro: Remove um cadastro do banco de dados.

## Estrutura do Projeto 
```bash
├── models/           # Modelos do MongoDB para os cadastros
├── routes/           # Rotas da API para CRUD (adicionar, editar, excluir)
├── controllers/      # Lógica das operações de banco de dados
├── server.js         # Arquivo principal que inicia o servidor
├── .env              # Configurações de ambiente (MongoDB, portas, etc.)
└── README.md         # Instruções e informações do projeto
```


## Observações

Este projeto foi dividido em dois repositórios para melhor organização, uma vez que o foco da matéria é Node.js + Banco de Dados, mas há um frontend desenvolvido em React disponível separadamente. O fluxo completo de cadastro pode ser testado quando ambos os repositórios estiverem configurados e rodando simultaneamente.


