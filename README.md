# Projeto de uma API Complexa

## Pacotes instados:

- typescrip -> npm install typescript -D 
- tsup -> npm install tsup -D
- tsx -> npm install tsx -D

- Express -> npm install express
- Sequelize -> npm install sequelize
- sqlite3 -> npm install sqlite3
- @types/sqlite3 - npm install @types/sqlite3 -D
- Cors -> npm install cors

### Inicia o typescrit no projeto

- npx tsc --init

## Scripts:

- "dist": "tsup src"
- "start:dev": "tsx --env-file=.env src/server.ts",
- "start:watch": "tsx watch --env-file=.env src/server.ts",
- "start:dist": "npm run dist && node dist/server.js"