## Finance Dashboard App

A full-stack MERN Finance Dashboard Application built using TypeScript. It allows clients or companies to visualise their financial disposition, as well as a simple machine learning algorithm to predict revenue for next year based on results from previous years.

## Features

- Insights into revenue and profit.
- Insights into operational and non operational expenses.
- Illustrates financial targets and breaks down expenses into categories.
- Shows recent transactions.
- Shows list of products in the transactions, along with the buyer, price, and amount of products.
- A regression line built with simple machine learning to predict the revenue for next year.

## Prerequisites

Before you begin, ensure you have met the following requirements:

- Node.js and npm installed on your machine.
- MongoDB server running locally or accessible via a URL.

## Getting Started

# 1. Clone the repository:

   git clone https://github.com/david-tech-ding/finance-dashboard-app.git

# 2. Install the project dependencies

- Navigate to the project folder `cd finance-dashboard-app`.
- Run `npm install`.

3. Create a .env.local file in the project root and add the VITE_BASE_URL, then create a .env file in the backend (server) folder with the following environment variables:

- MONGODB_URL=your_mongodb_connection_string
- PORT=your_port

## Run the deployment server

- Run command `npm run dev`. Then navigate to the localhost on your browser.
  
## Built with
- Next.js
- React.js
- Express.js
- MongoDB
- TypeScript
- MUI
- Recharts
- Redux Toolkit

## Deployment in Vercel
1. Connect the project repository to your Vercel account (https://vercel.com/).
2. Configure the deployment settings. and add the environment variables stored in .env.local file.
3. Deploy the app to Vercel.
