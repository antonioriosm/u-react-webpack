## Configurar Webpack para React

Instalar :
```
yarn add webpack webpack-cli
yarn add --dev babel-core babel-preset-env babel-preset-react babel-loader
yarn add --dev @babel/core # sin esto no funcionaba
yarn add --dev webpack-dev-server # modo desarrollo
yarn add --dev html-webpack-plugin # agrega app.bundle.js en index.html
yarn add --dev react react-dom
yarn add --dev @babel/preset-react @babel/preset-env # sin esto no funcionaba
```
En modo desarrollo:
```
npm start
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