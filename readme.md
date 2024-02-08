# Next Level Week Expert | Trilha Node JS | Rocketseat
Durante a Next Level Week Expert, uma experiência intensiva e enriquecedora conduzida pelo renomado Diego Fernandes da Rocketseat, tive o privilégio de colaborar no desenvolvimento do projeto Polls. Esta plataforma foi concebida com o propósito de simplificar a criação de enquetes e facilitar o processo de votação, proporcionando uma experiência intuitiva e eficiente para os usuários.

Utilizando um conjunto de tecnologias de ponta, destacando-se Node JS, TypeScript, Prisma, Fastify e WebSocket, o projeto Polls foi meticulosamente construído para oferecer desempenho excepcional e escalabilidade.

# Execução
O projeto não está em execução na nuvem, mais você pode utilizar estas orientações para executar ele junto do arquivo do Insomnia para as requisições.

[![Run in Insomnia}](https://insomnia.rest/images/run.svg)](https://insomnia.rest/run/?label=Next%20Level%20Week%20Expert%20%7C%20Trilha%20Node%20JS&uri=https%3A%2F%2Fraw.githubusercontent.com%2Fdeibsoncogo%2Fnlw-expert-trilha-node-js%2Fmaster%2Fdocs%2Finsomnia.json)

## Instalação
Primeiramente instale as dependências utilizando o `NPM`.
```bash
npm ci
```

Configure as variáveis de ambiente criando um arquivo chamado de `.env` e utilizando o arquivo `.env.example` para configurar ele.

Certifique se que o banco de dados está funcionando localmente ou remoto antes de executar os migrations.
```bash
npx prisma migrate deploy
```

Por fim basta executar o servidor.
```bash
npm run dev
```

# Imagens do projeto
### Criação de uma enquete
![Criação de uma enquete](/src/assets/prints/print1.png)

### Criação de um voto
![Criação de um voto](/src/assets/prints/print2.png)

### Visualização da enquete e seus votos
![Visualização da enquete e seus votos](/src/assets/prints/print3.png)

### Visualização evento registrado pelo WebSocket
![Visualização evento registrado pelo WebSocket](/src/assets/prints/print4.png)
