# Rocketseat GoStack Bootcamp


Para criar package.json
yarn init -y

Para abrir o Visual Studio pelo console
console .

Quando adicionar qualquer lib com "yarn add" é gerado o arquivo yarn.lock onde fica registrado a origem, versão e a integridade do arquivo baixado.
Também é adicionado a referencia dentro do arquivo packege.json

Adicionar a dependencia typescript
yarn add typescript -D
Obs.: -D adiciona dentro do package.config no item devDependencies, porém quando gerado a versão de produção essa dependencia não é adicionada. 
Para adicionar como dependenica do projeto não devemos usar o -D.

Sempre que houver '...' embaixo da referencia da classe, veririficar se tem o @type da referencia, informando:
yarn add @types/nome da lib -D

Para adicionar o tsconfig usamos:
yarn tsc --init
Quando adicionado podemos simplesmente usar o yarn tsc e tofos os arquivos com extesnão .ts serão convertidos para .js.
