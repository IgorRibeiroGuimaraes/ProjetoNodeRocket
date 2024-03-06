### Rocketseat Event - Polling Backend Project

Este é o repositório do projeto backend desenvolvido durante o evento organizado pela Rocketseat. O projeto utiliza Node.js, TypeScript, Fastify como framework, Prisma ORM para integração com o banco de dados PostgreSQL e Redis, Docker para gestão de serviços, Zod para validação de dados e WebSocket para comunicação em tempo real.

## Instalação

Certifique-se de ter o Node.js e o Docker instalados em sua máquina.

1. Clone o repositório:

git clone https://github.com/IgorRibeiroGuimaraes/ProjetoNodeRocket.git


2. Instale as dependências:

cd ProjetoNodeRocket
npm install

3. Execute o Docker Compose para configurar o ambiente de desenvolvimento:

docker-compose up -d


Isso iniciará os serviços PostgreSQL e Redis.

4. Execute as migrações do banco de dados com o Prisma:

npx prisma migrate dev


## Uso

Para iniciar o servidor de desenvolvimento, execute:

npm run dev


O servidor estará disponível em `http://localhost:3333`.

O projeto consiste na criação de enquetes (polls) em tempo real. Certifique-se de explorar os endpoints da API para criar, visualizar e interagir com as enquetes.

## Licença

Este projeto está licenciado sob a [Licença MIT](https://opensource.org/licenses/MIT).

## Contato

Para mais informações, entre em contato via e-mail: igorrguimaraes84@gmail.com

---

Obrigado por utilizar nosso projeto! Esperamos que seja útil para você.
