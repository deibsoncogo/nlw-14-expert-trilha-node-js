comando para criar o arquivo package.json
npm init -y

instalamos algumas dependências também
npm i -D typescript @types/node tsx

comando para criar as configurações do TypeScript, existe uma documentação onde mostra as melhores configurações a se utilizar dependendo da versão do Node JS com TypeScript, pesquisar por Node Target Mapping GitHub
npx tsc --init

dependência base para desenvolver o projeto
npm i fastify
npm i @fastify/cookie
npm i @fastify/websocket

dependência para lidar com o banco de dados
npm i @prisma/client
npm i -D prisma
npx prisma init

dependência para lidar com o Redis no banco de dados
npm i ioredis

dependência para lidar com validação de dados
npm i zod
