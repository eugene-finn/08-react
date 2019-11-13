Настройка react app

 1. Развернуть приложение с помощью CRA (по желанию)
 2. Настроить кастомный webpack + babel проект (+2 балла)
 3. Заставить работать TypeScript через babel (+1 бал)
 4. Написать хелло ворлд (todo app или любое другое), сделать базовую верстку вашего приложения, поработать с JSX (+2 бал)

Документация по webpack
https://webpack.js.org/guides/getting-started/

Документация по babel
https://babeljs.io/docs/en/

Typescript preset https://babeljs.io/docs/en/babel-preset-typescript

Можете взять за основу простое todo приложение

https://codesandbox.io/s/github/reduxjs/redux/tree/master/examples/todos

npm init -y

npm install --save-dev webpack webpack-cli

npm install --save react react-dom

npm install --save-dev @types/react @types/react-dom

npm install --save-dev typescript ts-loader source-map-loader

touch README.md

touch .gitignore

touch tsconfig.json

npm install --save lodash

npx webpack
