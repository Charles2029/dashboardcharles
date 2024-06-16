## Next.js App Router Course - Starter

This is the starter template for the Next.js App Router Course. It contains the starting code for the dashboard application.

For more information, see the [course curriculum](https://nextjs.org/learn) on the Next.js Website.


notie

## Create a Postgres database
https://nextjs.org/learn/dashboard-app/setting-up-your-database
Next, to set up a database, click Continue to Dashboard and select the Storage tab from your project dashboard. Select Connect Store → Create New → Postgres → Continue.

## Fetching Data 

Now that you've created and seeded your database, let's discuss the different ways you can fetch data for your application, and build out your dashboard overview page.

Now that you've  created and seeded your database, let's discuss the different ways you can fetch data for your application, and build our your dashboard overview  page.

## Database queries
When you're creating a full-stack application, you'll also need to write logic to interact with your database. For relational databases like Postgres, you can do this with SQL, or an **ORMhttps://vercel.com/docs/storage/vercel-postgres/using-an-orm** like  Prisma（https://www.prisma.io/）.

There are a few cases where you have to write database queries:

When creating your API endpoints, you need to write logic to interact with your database.
If you are using React Server Components (fetching data on the server), you can skip the API layer, and query your database directly without risking exposing your database secrets to the client.

When  creating your API endpoints, you need to write logic to interact with your database.
If you are using React Server Components (fetching data on the server), you can skip the API layer, and query your database directly without risking exposing your database secrets to the client.

That's right, you should not query your database directly when fetching data on the client as this would expose your database secrets.
That's right, you should not query your database directly when fetching data on the client as this would expose your database secrets.

## Using SQL
For your dashboard project, you'll write database queries using the Vercel Postgres SDK and SQL. There are a few reasons why we'll be using SQL:

For your dashboard project, you'll write database queries using the Vercel Postgres SDK and SQL. There are a few reasons why we'll be using SQL:

## Static and Dynamic Rendering
https://nextjs.org/learn/dashboard-app/static-and-dynamic-rendering

