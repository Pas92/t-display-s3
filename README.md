# - project name -

This project uses [DeviceScript](https://microsoft.github.io/devicescript/).

## Project structures

```
.devicescript      reserved folder for devicescript generated files
src/main.ts        default DeviceScript entry point
...
```


## Local/container development

-  install [Node.js LTS](https://nodejs.org/en/download)

```bash
nvm install --lts
nvm use --lts
```

-  install DeviceScript compiler and tools

```bash
npm install
```

### Using Visual Studio Code

- open the project folder in code

```bash
code .
```

- install the [DeviceScript extension](https://microsoft.github.io/devicescript/getting-started/vscode)

- start debugging!

### Using the command line

- start the watch build and developer tools server

```bash
npm run watch
```

-  navigate to devtools page (see terminal output) 
to use the simulators or deploy to hardware.

-  open `src/main.ts` in your favorite TypeScript IDE and start editing.

