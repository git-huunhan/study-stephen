# study-stephen

## 1. Setup MongoDB on local machine

- Install MongoDB Community Edition

  To install MongoDB, run:

  ```
  brew install mongodb-community@5.0
  ```

- Install Robo3T for managing database

  Download and install Robo3T from https://robomongo.org/

- Start Mongo services

  To run MongoDB, run:

  ```
  brew services start mongodb-community@5.0
  ```

  To check mongoDB status, run:

  ```
  mongo
  ```

## 2. Backup and restore MongoDB

- Create folder for backup database

- To backup database, run:

```
mongodump -d <database-name> <path-folder>
```

- To restore database, run:

```
mongorestore --drop -d <database-name> <path-folder>
```

## 3. Learn mongoose

## 4. Create schema (document into MongoDB)

## 5. Develop API (CRUD) to a schema

## 6. Learn ReactJS component/control

## 7. Learn Redux

## 8. Develop component

## 9. Learn Webpack
