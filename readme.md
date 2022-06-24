• Comando para iniciar um projeto node: npm init

• Instalar o TypeScript no projeto: npm install -g typescript

• Criar arquivo de configuração do TypeScript: tsc --init (será criado um arquivo tsconfig.json, um arquivo de configuração do TypeScript)

• Abrir o arquivo tsconfig.json

• Deixar ("moduleResolution": "node" e "rootDir": "./") descomentados (escrever "./scr")

• Descomentar "outDir": "./" e escrever o diretorio entre as "" (./dist)

• Em seguida vamos instalar a biblioteca ( npm install --save-dev @types/node )

• Em seguida criar uma pasta nova chamada "src"

• Depois criar o arquivo "index.ts"

• Em seguida instalar o Nodemon para conseguirmos executar os arquivos (npm install nodemon)

• Instalar o ts-node (npm install -D ts-node)

• Customizar o comando "nodemon src/index.ts"

• Apos a customizaçao podemos usar o comando "npm run start-dev"

• Usar o .gitignore no node modules (criar o arquivo .gitignore e escrever "node_modules/")