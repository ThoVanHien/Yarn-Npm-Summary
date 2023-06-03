# Yarn-Npm-Summary

Ref: [F8] https://www.youtube.com/watch?v=7sX_8lKURqo

## NPM:

- Project scope:

  - npm install a b => dependencies
  - npm i a b => dependencies
  - npm install --save-dev a b => devDependencies
  - npm i -D a b => devDependencies
  - npm uninstall a b

- Global scope:
  - npm i --global create-react-app
  - npm i --g create-react-app => `bin`(script), ex ng --help, create-react-app, ...

## NPX: Node => NPM, NPX:

- Nguyên lý hoạt động: `npx create-react-app` => kiểm tra project hiện tại, trong node_modules/.bin => chạy script có tên `create-react-app` (`npm`, `ng`). Nếu không có thì install, chạy xong thì remove.

## Yarn:

- Project scope:
  - yarn add a b => dependencies
  - yarn add a && b -D => devDependency
  - yarn add --dev a => devDependency
- Global scope:
  - yarn global <add/remove/upgrade/bin/list> a --y
