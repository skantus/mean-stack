# Clone project:
1. git clone https://github.com/skantus/mean-stack.git
2. cd mean-stack
3. npm install
4. npm start

or

# Create project:
1. `ng new mean`
2. `ng build` -> Create `dist` file
3. `ng serve` | `npm star` -> Test WebApp

# Create Server & copy files
1. server.js
2. create server/routes/api.js

# Mongodb
1. run server app (new terminal): `nodemon server`
2. Start db (new terminal): `mongod`
3. Create local db (new terminal): `use meandb`
4. Check db created: `show dbs`
5. Insert data: `db.users.insert({"name":"John Doe"})`
6. Show data: `db.users.find().pretty()`
