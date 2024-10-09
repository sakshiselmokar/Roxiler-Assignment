# MERN Stack Coding Challenge

## Project Overview

A full-stack MERN application that fetches product transaction data from a third-party API, stores it in a MongoDB database, and provides several APIs for transaction listing, statistics, and visual data. The frontend consumes these APIs and displays the data in a table and charts.

## Features

- Fetch and initialize data from a third-party API.
- List, search, and paginate transactions by month.
- Display sales statistics (total sales, sold items, unsold items).
- Bar and pie charts for price ranges and categories.
- Combined API response for easy data retrieval.

## Backend API Endpoints

- **Initialize Database**: `/api/initialize` (GET) – Seeds the database with product transactions.
- **List Transactions**: `/api/transactions` (GET) – Supports search, pagination, and month filter.
- **Statistics API**: `/api/statistics` (GET) – Returns sales stats for the selected month.
- **Bar Chart API**: `/api/bar-chart` (GET) – Returns item counts per price range.
- **Pie Chart API**: `/api/pie-chart` (GET) – Returns item counts per category.
- **Combined Data API**: `/api/combined-data` (GET) – Combines responses from the above APIs.

## Frontend Features

- **Transactions Table**: Lists and paginates transactions by month.
- **Statistics Section**: Displays total sales, sold items, and unsold items.
- **Bar and Pie Charts**: Visualizes price ranges and categories.

## How to Run

1. **Backend:**
   - `npm install` to install dependencies.
   - Configure `.env` for MongoDB URI.
   - `npm start` to run the server.
   
2. **Frontend:**
   - `cd frontend && npm install` to install frontend dependencies.
   - `npm start` to run the React app.
