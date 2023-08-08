<p align="center">
  <a href="http://nestjs.com/" target="blank"><img src="https://nestjs.com/img/logo-small.svg" width="200" alt="Nest Logo" /></a>
</p>

# Execute in dev

1. clone the repository
2. Execute
   ```
   yarn install
   ```
3. Install Nest CLI
   ```
   npm i -g @nestjs/cli
   ```
4. Up the database using docker
   ```
   docker-compose up -d
   ```
5. Clone file **.env.template** and rename the copy to **.env**
6. Fill the environment variables fields in file `.env`
7. Run the project in dev
   ```
   yarn start:dev
   ```
8. Reconstruct BD using SEED
   ```
   http://localhost:3000/api/v2/seed
   ```

# Stack used:

- Mongo DB
- Nest JS
