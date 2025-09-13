Stationery Inventory Management Application
This is a web application designed for small businesses, particularly stationery stores, to efficiently manage their inventory and sales. The application provides a simple and intuitive interface to track products, register sales, and generate reports.

Features
Product Database Upload: Easily upload your product inventory from an Excel file. The application accepts a spreadsheet with three columns: Product Name, Initial Quantity, and Price.

Sales Registration: Quickly record sales by selecting a product and entering the quantity sold.

Real-time Validation: The system automatically checks if the quantity being sold is available in stock. An alert message is displayed if the sale exceeds the current inventory.

Inventory Tracking: The application provides a real-time view of remaining product quantities after each sale.

Stock Alerts: Critical stock levels are highlighted to inform you when a product's quantity drops below a certain threshold (e.g., 10 units), helping you to manage re-ordering.

Dashboard & Reporting: The main dashboard displays key metrics like total sales revenue. You can also export detailed sales and final inventory reports to Excel files.

How to Use
Navigate to the Application: Open the index.html file in your web browser.

Import Inventory: Click on the "Import Excel" button and upload your Excel file. Ensure your file follows the required format (Product Name, Initial Quantity, Price).

Manage Inventory: The "Inventory" view allows you to see all your products, their current stock, and their value. You can also edit product details directly from this page.

Register Sales: Go to the "Sell" section, select a product from the dropdown, enter the quantity, and click "Confirm and Register Sale."

Generate Reports: The "Reports" view provides a summary of your sales and allows you to export detailed reports in Excel format.

Technology Stack
React: Used for building the interactive user interface.

Tailwind CSS: Used for all styling, ensuring a modern and responsive design.

xlsx: A popular library for reading and writing spreadsheet files, used here to handle Excel data.
