### React, Typescript, Webpack & Babel without create-react

yarn init -y<br>
yarn add react react-dom
yarn add -D babel-core babel-loader babel-preset-env babel-preset-react babel-plugin-async-to-promises css-loader file-loader html-webpack-plugin sass sass-loader style-loader ts-loader ts-node typescript webpack webpack-cli webpack-dev-server clean-webpack-plugin react-hot-loader react-hot-loader
yarn add -D @types/node @types/react @types/react-dom @types/webpack @types/webpack-dev-server
mkdir public src ./src/components ./src/assets ./src/assets/styles
touch ./public/index.html ./src/index.tsx ./src/App.tsx ./src/assets/styles/app.scss
tsc -init || touch tsconfig.json
touch webpack.config.ts
touch .babelrc
