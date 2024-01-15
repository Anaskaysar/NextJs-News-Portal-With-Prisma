## Step One: Cretation of Next JS Project
-> npx create-next-app

## Step Two: Database Setup (Prisma ORM for SQL)

### Install Prisma
-> npm install prisma --save-dev <br>
-> npx prisma init --datasource-provider mysql <br>

### Linking the Database
-> create a database named 'newsportal' into the localhost using Xampp. <br>
-> Change the Database Connection String. Rename database name and password in .env file. (mysql://root:@localhost:3306/newsportal) <br>

### Database Migration
-> Writing The Queries According to the databse design <br>
-> Migrate it to server using - npx prisma migrate dev <br>