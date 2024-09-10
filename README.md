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
npm i -D --save-exact @biomejs/biome
npm i drizzle-orm
npm i drizzle-kit -D
npm i zod
npm i postgres
```

Create the tsconfig.json (change the contents according with the [TSConfig bases](https://github.com/tsconfig/bases)):
```sh
npx tsc --init
```

Start the Docker:
```sh
docker compose up -d
```

Check the Docker status:
```sh
docker ps
```

Generate the database migration:
```sh
npx drizzle-kit generate
```

Execute the migration into the database:
```sh
npx drizzle-kit migrate
```

Open the Drizzle Studio to see the database:
```sh
npx drizzle-kit studio
```

Lint Tool:
- [Biome.js](https://biomejs.dev/)

- [Figma](https://www.figma.com/design/3UdUrAsfcXXmv95ZrNQLpa/NLW-Pocket-JS-%E2%80%A2-in.orbit?node-id=2001-844&node-type=canvas&t=UWvUqJ9hZ6ZGIMTi-0)

CTRL+SHIFT+P
settings.json:
```json
{
  "editor.tabSize": 2,
  "editor.formatOnSave": true,
  "editor.defaultFormatter": "biomejs.biome"
}
```

VS Code Extensions:
- [Biome](https://marketplace.visualstudio.com/items?itemName=biomejs.biome)

## Database

- [PostgreSQL](https://www.postgresql.org/)
- [Docker](https://www.docker.com/products/docker-desktop/)
- [Docker Hub](https://hub.docker.com/)
- [Neon](https://neon.tech/)
- [Drizzle ORM](https://orm.drizzle.team/)