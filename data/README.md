
# Dataset

This folder contains the datasets used for the Pizza Sales Analysis project.

The analysis was performed using four CSV files that store different parts of the pizza sales data. These files were imported into Excel and combined using Power Query for further analysis and dashboard development.

## Data Sources

The dataset consists of the following files:

• orders.csv – Contains order-level information including order ID, date, and time of each purchase.

• order_details.csv – Contains detailed information about each order, including the pizzas ordered and the quantity purchased.

• pizzas.csv – Includes information about pizza sizes, prices, and pizza IDs.

• pizza_types.csv – Contains pizza names, ingredients, and category information.

## Data Preparation

The datasets were imported into Excel and transformed using Power Query. The tables were then connected using Power Pivot to create relationships between the datasets for analysis.

This structured data model enabled efficient calculation of key metrics and the development of an interactive sales dashboard.

## Data Relationships

The following relationships were created in the data model:

1. order_details → orders (Order ID)
2. order_details → pizzas (Pizza ID)
3. pizzas → pizza_types (Pizza Type ID)
4. orders → calendar (Order Date)
