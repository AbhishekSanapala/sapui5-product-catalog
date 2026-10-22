# SAPUI5 Product Catalog

A SAPUI5 freestyle application built using SAP Fiori design principles to browse product categories, filter and search products, and view product, supplier, and order details in a three-column layout.

## Features

- Browse product categories and category-specific products.
- Search, sort, and group products.
- View product prices, stock levels, and discontinued status.
- Explore supplier and order details.
- Navigate using SAP Fiori Flexible Column Layout.
- Support local mock data for development and testing.

## Technologies

- SAPUI5 and SAP Fiori
- JavaScript, XML Views, HTML, and CSS
- OData V2 and Northwind service
- UI5 Tooling

## Project Structure

```text
product-catalog/
├── webapp/
│   ├── controller/
│   ├── css/
│   ├── fragment/
│   ├── i18n/
│   ├── localService/
│   ├── model/
│   ├── view/
│   ├── Component.js
│   ├── index.html
│   └── manifest.json
├── package.json
├── ui5.yaml
├── ui5-mock.yaml
└── README.md
```

## Installation and Setup

**Prerequisites:** Node.js and npm.

1. Clone the repository:

   ```bash
   git clone https://github.com/AbhishekSanapala/sapui5-product-catalog.git
   ```

2. Enter the project directory:

   ```bash
   cd sapui5-product-catalog
   ```

3. Install dependencies:

   ```bash
   npm install
   ```

4. Start the application:

   ```bash
   npm start
   ```

5. Open the local URL provided by UI5 Tooling.

## Data Source

Uses the Northwind OData V2 service and includes local metadata and mock data for development and testing.

## Key Concepts Demonstrated

- SAPUI5 MVC architecture and XML views
- Routing and Flexible Column Layout
- OData V2 integration and data binding
- Filtering, sorting, and grouping
- Reusable fragments and formatter functions

## Author

**Abhishek Sanapala**

SAPUI5 | SAP Fiori | SAP ABAP | SAP RAP
