# nodejs-microservice

A CLI to automatically clone the [Node Microservice API Starter](https://github.com/Jayvirrathi/microservices.git).

## Installation

Install the CLI globally OR use npx:

```sh
# with npm
npm install -g nodejs-microservice

# with yarn
yarn global add nodejs-microservice
```

## Usage

```sh
# with global install
nodejs-microservice name-of-app  [-y|--yarn]
# with npx
npx nodejs-microservice name-of-app [-y|--yarn]
# with yarn create
yarn nodejs-microservice name-of-app [-y|--yarn]
```

This will create a directory with the given name, clone the [Node Microservice API starter](https://github.com/Jayvirrathi/microservices.git) repo into it, and install dependencies.
