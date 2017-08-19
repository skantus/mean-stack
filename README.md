# Clone project:
1. git clone https://github.com/skantus/mean-stack.git
2. cd mean-stack
3. npm install
4. -> follow #Mongodb steps

- or

# Create project:
1. `ng new mean`
2. `ng build` -> Create `dist` file to make modifications in the Front
3. `ng serve` | `npm star` -> Test running WebApp

# Create Server & copy files
1. server.js
2. create server/routes/api.js

- Finally...

# Mongodb
1. run server app (new terminal): `node | nodemon server`
2. Start mongo server (new terminal): `mongod`
3. Start db (new terminal): `mongo`
4. Create local db (new terminal): `use meandb`
5. Check db created: `show dbs`
6. Insert data: `db.users.insert({"name":"John Doe"})`
7. Show data: `db.users.find().pretty()`
