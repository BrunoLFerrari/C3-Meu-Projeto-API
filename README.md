# C3-Meu-Projeto-API
Autenticação de tokens JWT

#EXTRAIA AS CINCO PASTAS .RAR CHAMADAS NODE_MODULE E AS COLOQUE EM UMA ÚNICA PASTA NODE_MODULE 

# Projeto Prático da C3: API com NodeJS, Typescript, Prisma e Express

# SOBRE O TRABALHO:
Este projeto prático envolve a criação de uma API utilizando as tecnologias NodeJS, Typescript, Prisma, e o servidor Express, acompanhado de um banco de dados à sua escolha (recomenda-se SQLite). Este projeto segue as diretrizes aplicadas durante as aulas, adotando o padrão MVC (Model-View-Controller) para organizar os modelos já existentes no Prisma Quickstart e inclui a adição de um novo modelo para Comentários.

## Ferramentas Empregadas

- **NodeJS**: Ambiente de execução para o desenvolvimento de aplicações eficientes em JavaScript.
- **Typescript**: Uma extensão de JavaScript que incorpora tipagem estática ao código.
- **Prisma**: Ferramenta ORM contemporânea e fácil de usar para NodeJS e TypeScript.
- **Express**:  Framework web robusto, ágil e de design simples para Node.js.
- **Banco de Dados**: Opte pelo banco de dados que melhor atender suas necessidades. Recomenda-se o SQLite.
- **ThunderClient**: Plugin para Visual Studio Code que facilita o teste das rotas da API durante o processo de desenvolvimento.
## Estrutura do Projeto

O projeto segue o padrão MVC:

- **Model**: Representa a estrutura dos dados e a lógica de negócios. Utiliza o Prisma para definir os modelos de dados.
- **View**: Não aplicável neste projeto de API.
- **Controller**: Gerencia a comunicação entre os Models e as rotas da aplicação, processando as requisições e respostas.

## Modelos

Os modelos adotados seguem o padrão do Prisma Quickstart, com a inclusão de um novo modelo para Comentários.

## Modelo de Comentários

A estrutura de Comentários apresenta as características a seguir:

- Está associado a um Post (um Post pode ter diversos Comentários).
- Está vinculado a um Usuário (um Usuário pode realizar múltiplos Comentários).

## Configuração e Instalação

1. **Clone o repositório**

   ```bash
   git clone https://github.com/BrunoLFerrari/C3-Meu-Projeto-API.git
   
2. **Instale as dependênciaso**

   ```bash
   npm install

3. **Configure o Prisma**

-  Crie e configure o arquivo .env na raiz do projeto para definir a conexão com o banco de dados.
-  Execute as migrações do Prisma para criar as tabelas no banco de dados.

   ```bash
   npx prisma migrate dev --name init
   
5. **Inicie o servidor**

   ```bash
   npm run dev
  
