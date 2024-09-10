# NLW17-Intermediary
NLW17 - Intermediary

NodeJS LTS (v20.17)
```sh
nvm uninstall 20.11.0
nvm install 20
```

Create the package.json:
```sh
npm init -y
```

Install the dependencies:
```sh
npm i typescript -D
npm i @types/node tsx -D
npm i fastify
```

Create the tsconfig.json (change the contents according with the [TSConfig bases](https://github.com/tsconfig/bases)):
```sh
npx tsc --init
```