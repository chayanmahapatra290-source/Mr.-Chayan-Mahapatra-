# Marketplace Application

This repository contains the marketplace application built with React for the frontend and Node.js/Express for the backend.

## Project Structure

```bash
Mr.-Chayan-Mahapatra-
├── frontend
│   ├── public
│   │   ├── index.html
│   │   └── favicon.ico
│   ├── src
│   │   ├── components
│   │   │   ├── ProductCatalog.js
│   │   │   ├── ShoppingCart.js
│   │   │   ├── OrderSummary.js
│   │   │   └── AdminPanel.js
│   │   ├── pages
│   │   │   ├── Home.js
│   │   │   ├── Product.js
│   │   │   ├── Cart.js
│   │   │   ├── Orders.js
│   │   │   └── Admin.js
│   │   ├── App.js
│   │   ├── index.js
│   │   ├── api
│   │   │   └── api.js
│   │   └── styles
│   │       └── App.css
│   ├── package.json
│   └── README.md
├── backend
│   ├── config
│   │   └── db.js
│   ├── controllers
│   │   ├── productController.js
│   │   ├── cartController.js
│   │   ├── orderController.js
│   │   └── adminController.js
│   ├── models
│   │   ├── Product.js
│   │   ├── Cart.js
│   │   ├── Order.js
│   │   └── User.js
│   ├── routes
│   │   ├── productRoutes.js
│   │   ├── cartRoutes.js
│   │   ├── orderRoutes.js
│   │   └── adminRoutes.js
│   ├── middleware
│   │   └── authMiddleware.js
│   ├── .env
│   ├── server.js
│   ├── package.json
│   └── README.md
├── database
│   ├── schema.sql
│   └── seed.js
└── README.md
```