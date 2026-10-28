# Paradise Nursery

Paradise Nursery is an online plant shop built with React and Redux. Customers can browse houseplants by category, add them to a shopping cart, change quantities and see the total cost update as they shop.

## Features

- **Landing page** with the company name, a short introduction and a "Get Started" button
- **Product listing** with 18 houseplants grouped into three categories (Air Purifying, Aromatic Fragrant, Medicinal), each showing a thumbnail, name, description and price
- **Add to Cart** buttons that add the plant, then disable themselves so the same plant is not added twice
- **Navbar** on the product and cart pages with links to Home, Plants and Cart, plus a cart icon showing the total number of items
- **Shopping cart** with each plant's thumbnail, name, unit price and subtotal, +/- quantity buttons, a delete button, the total cart amount, a checkout button ("Coming Soon") and a "Continue Shopping" button

## Tech stack

- React 18 (Vite)
- Redux Toolkit and React Redux for cart state

## Project structure

```
src/
  App.jsx          Landing page and "Get Started" button
  App.css          Landing page styles, including the background image
  AboutUs.jsx      Details about Paradise Nursery
  ProductList.jsx  Navbar and plant listing grouped by category
  CartItem.jsx     Shopping cart page
  CartSlice.jsx    Redux slice for the cart (addItem, removeItem, updateQuantity)
  store.js         Redux store
  main.jsx         App entry point
```

## Run locally

```bash
npm install
npm run dev
```

Then open the address Vite prints (usually http://localhost:5173).
