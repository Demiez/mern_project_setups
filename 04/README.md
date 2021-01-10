# react_app_without_cra

### Implementing starter skeleton without create-react-app in order to avoid lots of boilerplate code

### Steps:

yarn init -y <br>
yarn add -D @babel/core @babel/cli @babel/preset-env @babel/preset-react @babel/plugin-transform-typescript
touch .babelrc
yarn add -D webpack webpack-cli
touch webpack.config.ts
yarn -D add babel-loader style-loader css-loader sass sass-loader file-loader source-map-loader ts-loader webpack-dev-server eslint-loader
yarn add -D typescript @types/node @types/react @types/react-dom
touch tsconfig.json <br>
touch .editorconfig <br>
touch .eslintrc.json .prettierrc custom.d.ts
yarn add react react-dom