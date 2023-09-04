# E-commerce Data Warehousing and Analytics Project

## Project Overview

This school project is centered around the creation of a data warehouse for an e-commerce platform, with a primary focus on sales and inventory data. The project encompasses various data-related tasks, including data modeling, ETL (Extract, Transform, Load) processes, SQL optimization, OLAP cube design, and SQL unit testing.

### Project Context

As part of this academic endeavor, we are simulating a scenario where XYZ Corp, a fictional e-commerce company in France, is facing challenges related to data management and analysis. With a growing customer base and an expanding product catalog, the company recognizes the need for a robust solution to analyze sales and manage inventory effectively.

In this project, your role as a Data Developer is to undertake a series of tasks aimed at addressing these challenges.

### Project Tasks

The main tasks for this project include:

1. **GDPR Compliance**: Develop processes to ensure that all data handling aligns with GDPR regulations.

2. **ETL Job Implementation**: Create an optimized ETL job and establish effective error management procedures.

3. **Automation**: Implement automation for the ETL job using relevant scheduling tools or frameworks.

4. **Data Warehouse Modeling and Optimization**: Apply data warehousing best practices by implementing a fast constellation schema and partitioning data by Date ID to enhance query performance for time-based analysis.

5. **OLAP Cube Creation**: Design and build OLAP cubes to enable quick and efficient data analysis. Example queries include total sales by product category and month, as well as stock levels for specific products in warehouses.

6. **SQL Unit Testing**: Develop unit tests to ensure data and transformation quality and reliability. For instance, verify that no LineTotal values are negative through the implementation of SQL procedures.

## Getting Started

To start working on this school project, follow these steps:

1. Clone this GitHub repository to your local development environment.

2. Install the necessary tools and dependencies as specified in the project documentation.

3. Refer to the documentation provided within each project task folder for detailed instructions on completing each task.

## Project Structure

The project is structured as follows:

- **`data_splitter_script/`**: Contains the script for splitting the dataset into JSON, database, and CSV formats.

- **`etl_job/`**: Includes the Talend ETL job and error management components.

- **`automation/`**: Provides guidance on automating the ETL job.

- **`data_warehouse/`**: Contains components related to data warehouse modeling and optimization.

- **`olap_cubes/`**: Includes materials for OLAP cube design and MDX query examples.

- **`sql_unit_tests/`**: Contains SQL unit tests for data quality assurance.

## Contributing

This is a school project and is not open for external contributions.

## License

This project is solely intended for educational purposes and does not require a license.

## Acknowledgments

Acknowledgments to the educational institution for providing the opportunity to work on this project.
