# Hikeasy Backend using Node + Typescript + Mysql

## How to start the backend

First set up the database and config:

Set up the mysql server in local machine

Add `.env` to the `./Backend` directory
- Content of the `.env`:
  ```
  DB_HOST=localhost
  DB_USERNAME=<user>  
  DB_PASSWORD=<password>  
  DB_DATABASE=hikeasy  
  ```

To run the backend locally for quick testing, you only need to run this command:

```
npm start
```

This will do 3 things:

1. Ensure packages are latest (through NPM)
2. Compile the TypeScript files
3. Start the backend service (should be at port 8080)


## Functionality
We have finished the prototype of some api, inside the 'service' directory and we added endpoint for the api:
1. TrailService
2. EventService
3. UserService
4. ReviewService
