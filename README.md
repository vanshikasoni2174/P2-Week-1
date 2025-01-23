This project demonstrates the use of Power Query (Query Editor) in Power BI to prepare and customize supply chain data for analysis. The focus is on creating tailored tables for Inventory, Manufacturing, Supplier, and Supply Chain datasets. By using Power Query for transformations, the raw sustainable supply chain dataset is cleaned, structured, and enriched for further analysis.

Project Overview
Dataset Used: Sustainable supply chain dataset containing raw data on inventory, manufacturing, suppliers, and supply chain processes.
Tools Used: Power BI, Power Query.
Objective:
Prepare and customize tables for supply chain data analysis.
Leverage Power Query to clean, filter, and transform the raw dataset into meaningful tables.
Provide a structured dataset for further reporting or analytical use.

Key Steps in the Project

1. Data Import and Setup
The raw dataset was imported into Power BI from CSV files.
The Power Query (Query Editor) was used to clean and transform the data.
Each table (Inventory, Manufacturing, Supplier, and Supply Chain) was duplicated, filtered, and customized based on project requirements.

3. Customized Tables in Power Query
   
Inventory Table
This table focuses on key inventory metrics, enabling analysis of stock management.

Columns:
Product Type
SKU (Stock Keeping Unit)
Availability
Number of Products Sold
Customer Demographics
Stock Levels
Lead Times
Order Quantities
Revenue Generated
Transformations:
Removed rows with missing or irrelevant SKUs.
Added calculated columns to determine stock turnover rates and reorder points.
Filtered products based on availability and stock levels.

Manufacturing Table
This table provides insights into production activities and quality control.

Columns:
Product Type
SKU
Production Volumes
Manufacturing Lead Time
Manufacturing Costs
Inspection Results
Defect Rates
Transformations:
Grouped data by product type to calculate total production volumes and average costs.
Created a column to calculate defect rates based on inspection data.
Filtered rows for products with high defect rates to identify quality issues.

Supplier Table
This table highlights supplier performance and transportation data.

Columns:
Supplier Name
Location
Lead Time
Transportation Modes
Routes
Transformations:
Merged supplier data with transportation details to provide a unified view.
Grouped data to calculate average lead times by supplier.
Filtered suppliers with unreliable transportation modes or excessive delays.

Supply Chain Table
This table combines inventory, manufacturing, and supplier data for a comprehensive view of the supply chain.

Columns:
Product Type
SKU
Price
Availability
Number of Products Sold
Revenue Generated
Customer Demographics
Stock Levels
Lead Times
Order Quantities
Shipping Times
Shipping Carriers
Shipping Costs
Supplier Name
Location
Transportation Modes
Routes

Transformations:
Merged data from inventory, manufacturing, and supplier tables to create a single unified table.
Filtered rows for routes and shipping carriers with high costs or delays.
Added calculated columns to analyze fulfillment performance, such as delivery efficiency and cost per order.

3. Key Features
Power Query-Driven Data Preparation: All transformations, filtering, and column additions were done in Power Query, ensuring ease of use and reproducibility.
Customized Tables: The tables were tailored to highlight critical supply chain metrics such as stock levels, defect rates, supplier reliability, and shipping efficiency.
Reusability: The prepared tables can be exported or used directly for further analysis in Power BI or other tools.
Usage Instructions
Clone the repository to access the Power BI project file (.pbix).
Open the .pbix file in Power BI Desktop.
Navigate to Transform Data to review and explore the Power Query steps.
Use the customized tables for further analysis or reporting.
