# MuhammadHaris1.github.io


# Factory Backend
The Factory is a digital marketplace for buyers and sellers to 
find and sell the products they want. The sellers have the ability 
to go live and sell!

## Prerequisites
Ensure that you have the following software installed on your machine: 

1. Node.js v14.18.2
2. PostgreSQL
3. Docker (optional)

## Setup
Follow these steps to set up and run the Node.js server on your local machine: 

1. Clone the repository: <br />
    `git clone --branch factory-0.5.0-backend https://github.com/netclixlabs/the-waffle-factory-app.git factory-backend`

2. Install the dependencies: <br />
    `cd factory-backend` <br />
    `yarn` or `npm install`

3. Create a `.env` file in the root directory to configure environment variables:
    
    ### This text is inserted by `prisma init`:
    ### Environment variables declared in this file are automatically made available to Prisma.
    ### See the documentation for more detail: https://pris.ly/d/prisma-schema#using-environment-variables

    ### Prisma supports the native connection string format for PostgreSQL, MySQL and SQLite.
    ### See the documentation for all the connection string options: https://pris.ly/d/connection-strings

    DATABASE_URL="YOUR_DB_URL_HERE "<br />
    SESSION_COOKIE_SECRET = "SESSION_SECRET"

4. Start the local development server: <br />
    `yarn dev` or `npm run dev`

5. Open your browser and visit [http://localhost:4000/graphql](http://localhost:4000/graphql) to view your server.

## Cloud Setup
Follow these steps to set up and run on the cloud: 

## API
Provide details about the available API endpoints or functionality in your Node.js server. Example: GET /api/users (give details, what does the request and respones look like) 

## GRAPHQL
