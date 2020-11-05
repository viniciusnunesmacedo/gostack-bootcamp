# Rocketseat GoStack Bootcamp
Anotações do decorrer do bootcamp
### Nivel 01
Para criar package.json
```
yarn init -y
```
Para abrir o Visual Studio pelo console
```
console .
```
Quando adicionar qualquer lib com "yarn add" é gerado o arquivo yarn.lock onde fica registrado a origem, versão e a integridade do arquivo baixado.
Também é adicionado a referencia dentro do arquivo packege.json


#### Type Script .ts
Adicionar a dependencia typescript
```
yarn add typescript -D
```
**Obs.:** O parametro __-D__ adiciona dentro do **package.config** no item devDependencies, porém quando gerado a versão de produção essa dependencia não é adicionada. 
Para adicionar como dependenica do projeto não devemos usar o -D.

Sempre que houver '...' embaixo da referencia da classe, veririficar se tem o @type da referencia, informando:
```
yarn add @types/nome da lib -D
```
Para adicionar o tsconfig usamos:
```
yarn tsc --init
```
Quando adicionado podemos simplesmente usar o yarn tsc e todos os arquivos com extensão .ts serão convertidos para .js.
No arquivo tsconfig.json, se alterarmos a linha:
```
"outDir": "./dist", 
```

O caminho irá salvar todas as conversões considerando a pasta indicada no parametro como raiz, inclusive respitando as subpastas e recriando da mesma forma.


