# SAPUI5 Product Catalog

A SAPUI5 freestyle application built with SAP Fiori design principles to browse product categories, view category-specific products, and explore detailed product and supplier information.

## 🚀 Features

- **Category Management** — Browse and search product categories.
- **Product Listing** — View products filtered by the selected category.
- **Product Search** — Search products by name.
- **Product Details** — View product information, pricing, stock levels, and discontinued status.
- **Supplier Information** — Display supplier contact and address details.
- **Order Details** — Explore order-related information for selected products.
- **Sorting and Grouping** — Organize products using the view settings dialog.
- **Flexible Column Layout** — Navigate between categories, products, and product details in a three-column interface.
- **Responsive UI** — Designed using SAPUI5 controls for desktop, tablet, and mobile layouts.

## 🛠️ Technologies Used

- SAPUI5
- SAP Fiori design principles
- JavaScript
- XML Views
- OData V2
- Northwind OData Service
- UI5 Tooling
- HTML and CSS

## 📂 Project Structure

```text
product-catalog/
├── webapp/
│   ├── controller/
│   ├── css/
│   ├── fragment/
│   ├── i18n/
│   ├── localService/
│   │   ├── metadata.xml
│   │   └── mockdata/
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

## ⚙️ Prerequisites

- Node.js and npm
- SAP Business Application Studio or another environment that supports UI5 Tooling
- Internet access when using the remote Northwind OData service

## ▶️ Installation and Setup

1. Clone the repository:

   ```bash
   git clone https://github.com/AbhishekSanapala/sapui5-product-catalog.git
   ```

2. Navigate to the project directory:

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

5. Open the local URL provided by UI5 Tooling in your browser.

> If your project uses a different start script, check the `scripts` section in `package.json`.

## 🔌 Data Source

The application uses the Northwind OData V2 service:

```text
/V2/Northwind/Northwind.svc/
```

The service provides product categories, products, suppliers, and related order information.

The project also contains local service metadata and mock data files for development and testing. Mock mode depends on the active UI5 Tooling configuration.

## 🧭 Application Navigation

1. Select a category from the Categories column.
2. Browse the products belonging to that category.
3. Select a product to open its detailed information.
4. Review general information, supplier details, and order details.
5. Use search, sorting, grouping, and navigation controls as needed.

## 🎯 Learning Objectives

This project demonstrates practical experience with:

- SAPUI5 MVC architecture
- XML-based views and JavaScript controllers
- Component configuration using `manifest.json`
- OData V2 model integration
- UI5 routing and navigation
- Flexible Column Layout
- Data binding, filtering, sorting, and grouping
- Reusable fragments and formatter functions

## 👨‍💻 Author

**Abhishek Sanapala**

SAPUI5 | SAP Fiori | SAP ABAP | SAP RAP

## 📄 License

This project is intended for learning and demonstration purposes. Add a license file if you intend to distribute the project under a specific open-source license.

