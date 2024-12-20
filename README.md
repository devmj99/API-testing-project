# API Testing Project (Valentino Artisan Coffee House)

This repository contains a Postman collection for testing the API of Valentino's Artisan Coffee House. The API handles operations like managing products, orders, and clients for the coffee house.

## AUTHOR
 Jiffry Abdullah

## Overview

- **Project Name**: Valentino Artisan Coffee House API
- **Purpose**: To test various endpoints for API status, products, orders, and clients.
- **Tools Used**: Postman

## Features
- Retrieve API status.
- Manage product listings (get all products, fetch single product).
- Handle orders (create, view all, view by ID).
- Client registration.

## How to Use
### Prerequisites
1. Install [Postman](https://www.postman.com/downloads/).
2. Clone this repository or download the files:
   ```bash
   git clone https://github.com/devmj99/API-testing-project.git

**Step 1: Import the Collection**
    Open Postman.
    Click Import > File and select MyAPICollection.json.

**Step 2: Set Up Environment Variables**
    Import the sample environment file (SampleEnvironment.json):
    Go to Environments in Postman.
    Click Import and select the file.
    Update the placeholder values in the variables:
    baseUrl: (https://valentinos-coffee.herokuapp.com
    apiKey: Genrate an API key in postman settings
    Save the environment and set it as active.

**Step 3: Run the Collection**
    Select any request from the collection.
    Click Send to execute the request.
    View the response and test results.
    API Endpoints
    Status
    GET /status - Retrieve the current status of the API.
    Products
    GET /products - Get all products.
    GET /products/:productId - Fetch a single product by ID.
    Orders
    GET /orders - Fetch all orders.
    GET /orders/:orderId - Retrieve a specific order.
    POST /orders - Create a new order.
    Clients
    POST /clients - Register a new client.
   
**Example**
  To test the "Get API Status" endpoint:
    Select the request Get API Status from the collection.
    Click Send.
    Verify the response:
         {
            "status": "API is up and running "
        }


