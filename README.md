### Project: Stationery Store Inventory Management System

This project is a web application designed to solve the critical issues faced by stationery store owners due to manual inventory and sales management. The system provides a digital solution to eliminate errors, save time, and offer clear financial insights, transforming a chaotic manual process into an efficient and reliable workflow.

#### Problem Statement

The owners and employees of the stationery store lose time and money due to a completely manual system for managing inventory and sales. This leads to discrepancies between sales and financial records, preventing them from making informed decisions, planning purchases, and ensuring their business is profitable.

#### Proposed Solution

The solution is a web application that offers a straightforward and effective way to manage the store's operations. The prototype is designed to provide a sense of **calm and control** by automating key processes. The main functionalities are:

* **Data Upload:** Users can upload an entire product database via an Excel file, or manually add new products.
* **Sales Registration:** A simple interface allows users to register a sale, which automatically updates the inventory.
* **Validation:** The system prevents a sale if the quantity sold exceeds the available stock.

#### Key Features

* **Real-time Inventory:** The application automatically updates product stock after each sale.
* **Total Profit Calculation:** It calculates and displays total earnings based on sales.
* **Low Stock Alerts:** The system sends an alert when a product's remaining stock falls below 10 units, indicating the need to reorder.
* **Visual Dashboard:** Provides a clear overview of initial inventory, products sold, and total earnings.
* **Excel Integration:** Allows both bulk data import and export of sales and inventory reports.

#### Technology Stack

* **Frontend:** React.js
* **Excel Integration:** `xlsx` library
* **Logic & Data:** JavaScript
* **Data Storage:** A secure database to store all inventory and sales information.

#### How to Use

To use this application, you would need to:

1.  Clone the project repository.
2.  Install the necessary dependencies.
3.  Run the application locally.
4.  Upload your product inventory using an Excel file with the specified format, or add products manually.
5.  Start registering sales to see the inventory and profit calculations in real time.
