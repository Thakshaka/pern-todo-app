# Simple To Do Using PERN Stack

## Tech Stack
1. PostgreSQL
2. Express.js
3. React.js
4. Node.js

## Database
1. PostgresSQL (Sequelize)

## API Testing
1. Postman

## Hosting
1. Frontend - Vercel
2. Backend - Vercel
3. Database - Supabase

Live Demo: [View](https://pern-todo-app-client-kt8xcb4qz-thakshakas-projects.vercel.app/)

## Deploy locally

1. Create a postgres database and a table named "todo" in [supabase](supabase.com)

2. Make sure to create .env with your supabase credentials
   ```
   cd .\server\
   ```
   ```
   SUPABASE_URL=''
   SUPABASE_KEY=''
   ```

3. Client side
   ```
   cd .\client\
   npm i
   ```

4. Server side
   ```
   cd .\server\
   npm i
   nodemon index.js
   ```

