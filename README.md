# Adonis API application

Implementation of an api to register projects and tasks developed with the adonis framework.

Some resources used:

1. Bodyparser
2. Authentication
3. CORS
4. Lucid ORM
5. Migrations and seeds

## Setup

Use the adonis command to install the blueprint

```bash
adonis new yardstick --api-only
```

or manually clone the repo and then run `npm install`.


### Migrations

Run the following command to run startup migrations.

```js
adonis migration:run
```

### Aplication

Execute after having performed all the previous steps.

```js
npm start
```

