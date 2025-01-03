# TradeHub Data Insights

## Dashboard Link
[TradeHub Data Insights Dashboard](https://app.powerbi.com/groups/b158e878-b19d-4ff8-a670-209d8cd88334/reports/fe7509a5-d5ae-4bf1-9ce8-2d595a6082cf?ctid=365d5d36-6c0a-407b-ac40-67a602fef88b&pbi_source=linkShare)

## Overview
**TradeHub Data Insights** is a sophisticated business intelligence dashboard that provides in-depth, real-time analytics across key business dimensions, including sales performance, customer demographics, product insights, and store operations. This tool is designed to empower decision-makers by offering clear, data-driven insights that drive business growth and operational efficiency.

The dashboard offers a comprehensive view of business performance, enabling users to monitor critical metrics and trends, and make informed decisions based on up-to-date data.
<br>

## Key Features
<br>

### Sales Performance Analytics
<br>

![Sales Performance](https://github.com/user-attachments/assets/486fa9f4-96f2-412e-91e8-8a1233c306df)
- **Total Sales Overview**: $1.76M – Analyze the overall revenue across regions and time periods.
- **Profit Insights**: $1.05M – Track profitability at a granular level.
- **Regional Sales Distribution**: Breakdown of sales by geographic regions (North America, Europe, Asia).
- **Monthly & Year-over-Year Trends**: Compare monthly sales figures with year-over-year data to identify growth patterns.
- **Store Performance**: Detailed analysis of sales performance across various store locations.
- **Return Sales Tracking**: Track product returns ($17.43K) and their impact on business.
<br>

### Customer Demographics Insights
<br>

![Customer Demographics](https://github.com/user-attachments/assets/966aee33-f970-493c-8ad9-bd34daa7120e)
- **Total Customer Base**: 7,359 customers – Understand your customer base through demographic analysis.
- **Income Analysis**: Average income of $57.81K, segmented by education and occupation.
- **Geographic Distribution**: Visual representation of customer distribution across regions.
- **Occupation Breakdown**: Insights into customer professions to inform targeted marketing strategies.
- **Membership Insights**: Track the distribution of membership card holders and account opening trends from 1990-1994.
<br>

### Product Insights
<br>

![Product Insights](https://github.com/user-attachments/assets/3194e34f-5d99-41ec-8bec-ce5d9229071a)
- **Retail Price Tracking**: Average retail price of $2.1176 across all products.
- **Product Return Analysis**: Monitor return rates and product performance metrics.
- **Inventory Insights**: Track inventory levels with over 420K units in stock.
- **Product Category Performance**: Identify best-selling products by category and brand.
- **Year-over-Year Comparison**: Evaluate the performance of products over time.
<br>

### Store Operations Insights
<br>

![Store Operations](https://github.com/user-attachments/assets/ab0dce53-4d08-46ed-9601-9002a6ab65a6)
- **Store Performance Metrics**: Analyze performance across 24 stores, identifying the top-performing stores.
- **Revenue per Square Foot**: Evaluate store efficiency with metrics like $2.5324 revenue per square foot.
- **Store Type Analysis**: Understand performance based on store type, such as Supermarket, Deluxe, and Gourmet.
- **Efficiency Metrics**: Track the size and operational efficiency of each store, including space utilization.
- **Year-over-Year Comparison**: Assess the growth and performance of stores over time.
<br>

## Technical Details
<br>

### Built With
- **Power BI**: For advanced data visualization, interactive reporting, and real-time analytics.
- **SQL Server**: Data storage and management for handling large datasets and ensuring scalability.
- **Advanced Data Modeling**: Complex data relationships and optimizations for fast reporting.
- **Custom Visuals**: From Microsoft AppSource to enhance the data presentation experience.
<br>

### Data Sources
- **Transaction Data**: Detailed sales records from 1997-1998.
- **Customer Data**: Comprehensive information on customer demographics, account openings, and membership.
- **Product Data**: Inventory data, product returns, and pricing.
- **Store Information**: Location-based store performance, type, and size metrics.
- **Regional Sales Data**: Breakdown of sales by region, including returns data.

<br>

## Getting Started
<br>

### Prerequisites
- **Power BI Desktop**: Required for opening, editing, and publishing the Power BI reports.
- **SQL Server**: Necessary to connect to and query the data stored in the company’s database.
- **Data Warehouse Access**: Ensure you have proper access to the company’s data warehouse for data integration.

<br>

### Installation Instructions
<br>

1. **Clone the Repository**:
    ```bash
    git clone https://github.com/jiyasavaliya/tradehub-data-insights.git
    ```

2. **Navigate to the project directory**:
    ```bash
    cd TradeHub-Data-Insights
    ```

3. **Install the required dependencies**:
    ```bash
    pip install -r requirements.txt
    ```

4. **Access the Dashboard**:  
    Open the provided Power BI link to view the TradeHub Data Insights dashboard:  
    [TradeHub Data Insights Dashboard](https://app.powerbi.com/groups/b158e878-b19d-4ff8-a670-209d8cd88334/reports/fe7509a5-d5ae-4bf1-9ce8-2d595a6082cf?ctid=365d5d36-6c0a-407b-ac40-67a602fef88b&pbi_source=linkShare)

<br>

## Usage
<br>

### Example Code

1. **Load and Process Data**:
    ```python
    from tradehub_data_insights import data_processor
    data = data_processor.load_data('path/to/data.csv')
    processed_data = data_processor.clean_data(data)
    ```

2. **Generate Visualizations**:
    ```python
    from tradehub_data_insights import visualizer
    visualizer.plot_trade_data(processed_data)
    ```

3. **Perform Statistical Analysis**:
    ```python
    from tradehub_data_insights import analyzer
    stats = analyzer.calculate_statistics(processed_data)
    print(stats)

    ```
<br>

## Contributing

We welcome contributions to TradeHub Data Insights! If you have any ideas, suggestions, or bug reports, please open an issue or submit a pull request. Follow these steps to contribute:

1. **Fork the repository**.
2. **Create a new branch**:
    ```bash
    git checkout -b feature-name
    ```
3. **Make your changes and commit them**:
    ```bash
    git commit -m "Add new feature"
    ```
4. **Push to the branch**:
    ```bash
    git push origin feature-name
    ```
5. **Open a pull request**.

<br>

## License
This project is licensed under the MIT License. See the [MIT License](LICENSE) file for more information.

## Email Support
You can contact the BI team directly at [jiyasavaliya55@gmail.com](mailto:jiyasavaliya55@gmail.com) for technical support or inquiries.
