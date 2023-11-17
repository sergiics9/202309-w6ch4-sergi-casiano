# Week6

Week 6 - Challenge 4 Calculadora WebService Crea una calculadora en Node en forma de web.

El programa debe recibir dos números por query params (p.e. http://localhost:8000/calculator?a=6&b=3), y devolver el siguiente HTML:

Resultados:

6 + 3 = 9

6 - 3 = 3

6 \* 3 = 18

6 / 3 = 2

Si el usuario no ha proporcionado alguno de los números o éstos no son de tipo número, la aplicación debe devolver un HTML con un mensaje de error e interrumpir la ejecución del programa con un código de error.

La app debe abrirse en un puerto por defecto que esté configurado como variable de entorno, pero también se tiene que poder decir expresamente por línea de comandos en qué puerto queremos que se abra (p.e., node . --port 4000). Usar el paquete commander.

Si la request no va a /calculator, la app debe responder con un 404.

Opción extra Recoger los números en un formulario y calcular los valores, utilizando SOLO vanila

Código de Week6 / Server

Código de Week6 / Server

- Node
- Express
- Mongo (Mongoose)

- TS...

## Installation

- TS

```shell
npm i -D typescript
```

- config TS

```shell
npx tsc --init
```

- eslint & TS

```shell
npx eslint --init

Consecuencia
npm i -D eslint @typescript-eslint/eslint-plugin @typescript-eslint/parser eslint-config-xo
```

- eslint + prettier

```shell
npm i -D eslint-config-prettier
```

- Jest

```shell

npm i -D jest ts-jest @types/jest @types/node jest-ts-webcompat-resolver
```

- .editorconfig
- .gitignore
- npm init
- git init
