Please work. Please please god work...

// PLEASE HELP:

The 'npx prisma migrate dev --name init' command isn't working. This is the error I'm getting:

    Loaded Prisma config from prisma.config.js.

    Prisma schema loaded from prisma/schema.prisma.
    Datasource "db": PostgreSQL database "postgres", schema "public" at "myPSQLUsername"

    Error: P1001: Can't reach database server at `myPSQLUsername:5432`

I followed along with TOP Prisma ORM and skipped the second set of commands like instructed.

Didn't run these commands as instructed (Maybe this is the issue?):
    npm init -y 
    npm install typescript tsx @types/node --save-dev
    npx tsc --init