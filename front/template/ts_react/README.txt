===в основном взято отсюда, внесены исправления согласно обновленным версиям либ, поправлены опечатки
http://typescript-lang.ru/docs/tutorials/React%20&%20Webpack.html

===билд===
npm install -g typescript typings webpack
---typings - это react типы на ts
npm link typescript -- используем глобальную версию typescript
npm run buil -- билдим

---
===full empty project create===
npm init
npm install -g typescript typings webpack
npm install --save react react-dom
npm install --save-dev ts-loader source-map-loader
npm link typescript
typings install --global --save dt~react
typings install --global --save dt~react-dom
добавить tsconfig.json
Создайте файл webpack.config.js
---


d webpack конфиге секция loaders устарела
https://webpack.js.org/concepts/loaders/
https://stackoverflow.com/questions/42060243/invalid-configuration-object-webpack-has-been-initialised-using-a-configuration








