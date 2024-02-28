<p align="center">
  <a href="http://nestjs.com/" target="blank"><img src="https://nestjs.com/img/logo-small.svg" width="200" alt="Nest Logo" /></a>
</p>

# Run in DEV MODE

1. Clone the repository
2. Execute

```
yarn install
```

3. Have Nest CLI installed

```
npm i -g @nestjs/cli
```

4. Up the database

```
docker-compose up -d
```

5. Clone **.env.template** rename to **.env**

6. fill the environment variable

7. Execute the application

```
yarn start:dev
```

6. Recreate Database with a SEED

```
localhost:3000/api/v2/seed
```

## Stack

- MongoDb
- Nest
