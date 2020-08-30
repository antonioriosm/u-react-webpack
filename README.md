## Configurar Webpack para React

Instalar :
```
yarn add webpack webpack-cli
yarn add --dev babel-core babel-preset-env babel-preset-react babel-loader
yarn add --dev @babel/core # sin esto no funcionaba
```
Para producción en windows
```
"webpack": "set NODE_ENV=production&& webpack",
```
Para producción en linux | mac
```
"webpack": "NODE_ENV=production webpack",
```

Se ejecuta con
```
npm run webpack
```