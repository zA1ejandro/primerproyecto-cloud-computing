# Node.js Express Hello World

A minimal Hello World application built with Node.js and Express and prepared to run locally with Docker Compose.

## Project structure

```text
node-express-hello-world/
├── src/
│   ├── index.js
│   └── package.json
├── Dockerfile
├── docker-compose.yml
├── .dockerignore
├── .gitignore
└── README.md
```

All Node.js application files are kept inside `src/`.

## Run with Docker Compose

From the project root, run:

```bash
docker compose up --build
```

Then open:

```text
http://localhost:3000
```

The application returns:

```text
Hello World!
```

To stop the application:

```bash
docker compose down
```

## Run without Docker

Enter the `src` directory first:

```bash
cd src
npm install
npm start
```
