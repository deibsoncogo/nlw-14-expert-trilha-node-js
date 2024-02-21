comando para criar o arquivo package.json
```bash
npm init -y
```

instalamos algumas dependências também
```bash
npm i -D typescript @types/node tsx
```

comando para criar as configurações do TypeScript, existe uma documentação onde mostra as melhores configurações a se utilizar dependendo da versão do Node JS com TypeScript, pesquisar por Node Target Mapping GitHub
```bash
npx tsc --init
```

dependência base para desenvolver o projeto
```bash
npm i fastify @fastify/cookie @fastify/websocket
```

dependência para lidar com o banco de dados
```bash
npm i @prisma/client
npm i -D prisma
npx prisma init
```

dependência para lidar com o Redis no banco de dados
```bash
npm i ioredis
```

dependência para lidar com validação de dados
```bash
npm i zod
```
