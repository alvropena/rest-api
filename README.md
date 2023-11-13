# rest-api

<!-- Install package.json -->
npm install -y
<!-- Set up Typescript, TS Node, Nodemon -->
npm install -D typescript
npm install -D ts-node
npm install -D nodemon
<!-- Install Express, Body Parser, Cookie Parser, Compression, and CORS -->
npm install express body-parser cookie-parser compression cors
npm install -D @types/express @types/body-parser @types/cookie-parser @types/compression @types/cors
<!-- Set up MongoDB -->
npm install mongodb
connect > drivers > create a constant and change <password> to alvaro 
npm install mongoose
npm i -D @types/mongoose
<!-- Setting up our schema: db/users.ts -->
select means every time we use one of our controllers to fetch our users we want to avoid fetch the authentication user by accident