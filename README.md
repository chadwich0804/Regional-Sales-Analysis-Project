
# Regional-Sales-Analysis-Project

**Overview**

The Regional Sales Analysis Project examines sales performance across regions, products, channels, and seasons from 2014 to 2017. Using a dataset of sales orders, this project generates insights through data cleaning, transformation, and visualization, focusing on revenue, profit, and order quantities. Built with Python, Pandas, and Matplotlib, it includes various charts to highlight trends and patterns, such as top product sales by region and seasonal order distributions.

**Project Structure**

 
- notebooks: Jupyter notebooks with data processing and visualization code:


- sales_analysis.ipynb: Main analysis with data cleaning, calculations, and visualizations.



- scripts: Python scripts for reusable functions (e.g., data aggregation, plotting).



- figures: Output directory for generated charts (e.g., PNGs of heatmaps, bar charts).




**Features**

- Data Cleaning: Filters data to 2014-2017, removes invalid entries, and calculates derived metrics like Profit (Revenue - Total Cost).



- Visualizations:

    - Heatmap: Displays top 10 product (SKU) sales by region, with revenue in millions USD.

    - Doughnut Chart: Shows total revenue by channel (2014-2017).

    - Pie Chart: Visualizes order quantity distribution by season (Spring, Summer, Autumn, Winter).

    - 3D Bar Chart: Compares revenue and profit for top 10 products by SKU.

    - Metrics: Aggregates revenue (Line Total), profit, and order quantities by region, channel, season, and product.

**Installation**

1. Clone the repository:

    - git clone https://github.com/chadwich0804/Regional-Sales-Analysis-Project.git

2. Navigate to the project directory:

    - cd regional-sales-analysis

3. Install dependencies:

    - pip install pandas matplotlib seaborn numpy


**Requirements**

- Python 3.8+

- Pandas

- Matplotlib

- Seaborn

- NumPy

- Jupyter Notebook

**Data**

The dataset contains sales order details with columns:

- OrderDate: Date of the order (filtered to 2014-2017).

- SKU: Unique product identifier.

- Region: Geographic region of sale.

- Channel: Sales channel (e.g., Online, Retail, Wholesale).

- Season: Season of the order (Spring, Summer, Autumn, Winter).

- Line Total: Revenue per order.

- Order Quantity: Number of units sold.

- Unit Price: Price per unit.

- Total Unit Cost: Cost per unit.


**Visualizations**

- Top 10 SKU Sales by Region (Heatmap): Shows revenue (in $M) for top 10 products by region, highlighting high-performing products.

- Channel Revenue (Doughnut): Displays total revenue by channel, with percentages and amounts (e.g., $372M).

- Seasonal Order Quantity (Pie): Illustrates order quantity distribution across seasons, with percentages and millions.

- Top 10 Products by Revenue (3D Bar): Compares revenue and profit for top 10 SKUs in a 3D grouped bar chart.

**License**

This project is licensed under the MIT License. See the LICENSE file for details.
