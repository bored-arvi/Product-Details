## Overview

The Product List App is a simple Flutter application that displays a list of products. The app fetches product data from a mock API (`https://fakestoreapi.com/products`) and displays each product's title, category, price, rating, and image. It includes a loading indicator while data is being fetched from the API.
## Features

- **Fetch Data from API**: The app uses HTTP requests to fetch product data from a mock API (`https://fakestoreapi.com/products`).
- **Responsive UI**: Displays a clean, modern, and scrollable list of products.
- **Loading Indicator**: A circular progress indicator is shown while the data is being fetched from the API.
- **Product Details**: For each product, you can view its title, category, price, and rating.
- **Smooth Scroll**: The list is scrollable with smooth, bouncing scroll behavior.

### **API**

This section gives details about the API that the app interacts with, including the URL and the structure of the response.

## API

The app uses the following API to fetch product data:

- **API URL**: `https://fakestoreapi.com/products?limit=10`
- **Response**: A JSON array containing product objects. Each product has the following fields:
  - `id`: A unique identifier for the product.
  - `title`: The title or name of the product.
  - `price`: The price of the product.
  - `category`: The category to which the product belongs (e.g., "electronics").
  - `rating`: An object containing:
    - `rate`: The average rating of the product (a number).
    - `count`: The number of ratings.
  - `image`: A URL to an image of the product.
