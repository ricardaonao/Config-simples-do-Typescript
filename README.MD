## Forma mais simples de utilizar TypeScript

**Instalado**<br>
Express + tipagens<br> 
```
npm install express <br>
npm i --save-dev @types/express
``` 
 
Typescript <br>
```
npm install --save -D typescript
``` 

**Configurado** <br>
No package.json configura o "script" para : <br>
```
"dev": "ts-node-dev --respawn --transpile-only src/index.ts"
```
( ele apenas traspila, nao verificar se há erro no código. isso já fizemos ao digitar e o ts ja informou se tem erro ou não no momento da digitação.)

**Configurando o TS**
rode
```
 tsc --init
 ```
 e configure o *outDist* para uma pasta que deseja por os arquivos js transpilados. depois rode para transpilar.<br>

 ```
 npx tsc
 ```
Por fim, rode comando abaixo para subir o sistema
```
npm run dev
```