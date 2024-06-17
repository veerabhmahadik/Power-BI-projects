
# Room to Insight: Dashboard for Hotel Performance Analysis

## Description

The Hospitality Domain Data Analysis project aims to analyze and visualize data from the hospitality industry using Power BI. This project involves examining various performance metrics of properties such as revenue, occupancy rates, average daily rates, and customer ratings. The goal is to provide insights that can help in understanding market trends, customer preferences, and overall performance of hospitality properties.

### Usage Examples

- Visualizing revenue, RevPAR, and occupancy rates for different properties.
- Analyzing customer ratings and cancellation rates.
- Comparing performance metrics across different cities and room types.

### Issues or Limitations

- Data quality and completeness may vary across different properties.
- Real-time updates are not included in this project.
- Limited to the data available in the provided dataset.

### Future Features

- Integration of real-time data updates.
- Enhanced interactive features in the Power BI dashboard.
- Additional visualizations and insights.

## Technologies

### Technologies Used

- **Power BI:** For creating interactive dashboards and visualizations.
- **CSV Files:** For storing and managing the dataset.

### Why These Technologies?

- **Power BI** is chosen for its robust data visualization capabilities and ease of use for creating interactive reports and dashboards.
- **CSV Files** provide a simple and efficient way to store and manage the dataset.

## Installation and Usage

### Prerequisites

- **Power BI Desktop:** For opening and interacting with the Power BI report.

### Instructions

1. **Clone the Repository**
   ```sh
   git clone https://github.com/veerabhmahadik/hospitality-domain-data-analysis.git
   ```
2. **Navigate to the Project Directory**
   ```sh
   cd hospitality-domain-data-analysis
   ```
1. **Load the Data Files**
   - Ensure the following CSV files are in the project directory from the 'data' folder:
     - `dim_date.csv`
     - `dim_hotels.csv`
     - `dim_rooms.csv`
     - `fact_aggregated_bookings.csv`
     - `fact_bookings.csv`
2. **Open the Power BI Report**
   - Use Power BI Desktop to open `Hospitality Domain Power BI.pbix` to explore the interactive dashboard and visualizations.

### Dependencies

- **Power BI Desktop:** Ensure you have Power BI Desktop installed to open and interact with the `.pbix` file.
- **CSV Files:** Required for loading the dataset into Power BI.

