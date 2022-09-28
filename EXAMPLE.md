# Example: Web Application with Next.js and sqlite3

In our example, we're going to build a web application that allows users to create posts. We're going to use [Next.js](https://nextjs.org/) and [sqlite3](https://www.sqlite.org/index.html) to build this application.

## Development Environment

You're going to need to install [Node.js](https://nodejs.org/en/) and [npm](https://www.npmjs.com/) to get started. Google how to do this for your operating system.

> 🚨 **If you're stuck setting up your development environment ask in our Discord under `#tech-support`** 🚨

Find yourself a good text editor. We recommend [Visual Studio Code](https://code.visualstudio.com/) but you can use whatever you like.

> 🎉 **JetBrains has a [free license for students](https://www.jetbrains.com/community/education/#students) that you can use for any of their products!** 🧠

> 🚨 **If you're using Windows look into setting up [Git-Bash](https://gitforwindows.org/) as your terminal. Otherwise some of the commands below will not work.** 🚨

## Setting up the Project

Once you have those installed, you can create a new project using the following command:

```bash
npx create-next-app --typescript
```

This will create a new project using [Next.js](https://nextjs.org/) and [TypeScript](https://www.typescriptlang.org/). You can learn more about Next.js [here](https://nextjs.org/learn/basics/create-nextjs-app).

Follow the prompts to create your project. Once it's done, you can run the following command to start the development server:

```bash
npm run dev
```

You should see a message that says `ready - started server on 0.0.0.0:3000, url: http://localhost:3000`. Open that URL in your browser and you should see the default Next.js page.

## Setting up the Database

We're going to use [sqlite3](https://www.sqlite.org/index.html) to store our data. To get started, we need to install the [sqlite3](https://www.sqlite.org/index.html) package:

```bash
npm install sqlite3
```

This will install the [sqlite3](https://www.sqlite.org/index.html) package and add it to our `package.json` file. We can now use this package in our project.

If you want to install other packages, you can use the `npm install` command.

We'll provide the basic SQL commands to get started. You learn about database in CSC 370.

Now that we have the database installed, we need to create a database file. We can do this by creating a new file called `db.sqlite3` in the root of our project. This file will be used to store our data.

Now that we have a database file, we need to create a table to store our posts. We can do this by creating a new file called `init.sql` in the root of our project. This file will contain the SQL commands to create our table.

```sql
CREATE TABLE posts (
  id INTEGER PRIMARY KEY AUTOINCREMENT,
  title TEXT NOT NULL,
  content TEXT NOT NULL
);
```

Now that we have our table created, we need to run the SQL commands to create our table. We can do this by running the following command:

```bash
sqlite3 db.sqlite3 < init.sql
```

This will run the SQL commands in `init.sql` and create our table.
