seção 1
npm init -y
.gitignore
npm i -D typescript @types/node
tsconfig.json
npm install --save-dev typescript@ eslint@^7.12.1 eslint-plugin-promise@^5.0.0 eslint-plugin-import@^2.22.1 eslint-plugin-node@^11.1.0 @typescript-eslint/eslint-plugin@^4.0.1 eslint-plugin-standard@4.0.1 eslint-config-standard-with-typescript@11.0.1
eslintrc
npm i -D husky
npm i -D lint-staged
.huskyrc.json
npm i -D -g jest @types/jest ts-jest
jest --init
npx jest --init
jest.config

seção 2
signup.controller.test
signup.ts
criação da interface para criar a conta (caso de uso)

seção 3
criação de scripts de teste
criação do jest-unit-config para arquivos de extensão .spec
criação do jest-integration-config para arquivos de extensão .test

seção 4
pasta utils
email-validator-adapter.spec
npm i validator
npm i @types/validator -D

seção 5
criação da pasta data
criação do repository

seção 6
criação da camada infra (criptography)
npm i bcrypt
npm i @types/bcrypt -D
npm i -D @shelf/jest-mongodb @types/mongodb
npm i mongodb
alterar jest.config
criar arquivo de configuração para o jest-mongodb

seção 7
criação da pasta main/server.ts (dentro do main é criado as instancias das outras camadas)
npm install express
npm install @types/express
npm i sucrase -D
npm i -D supertest @types/supertest
routes
npm i fast-glob
modificou arquivo server.ts
env.ts
