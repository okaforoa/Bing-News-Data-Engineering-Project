
# Bing News Data Engineering Project

This project demonstrates an end-to-end data engineering workflow using Microsoft Fabric and Microsoft Azure to analyze Bing News data. The workflow includes data ingestion, transformation, sentiment analysis, and visualization. The primary tools used are Azure Data Factory, Synapse Data Engineering, Synapse Data Science, One Lake, Power BI, and Microsoft Teams for collaboration.

## Project Overview

### Architecture Diagram
![Architecture Diagram](path_to_your_architecture_diagram_image)

### Agenda
![Agenda](path_to_your_agenda_image)

### Pipeline Workflow
![Pipeline Workflow](path_to_your_pipeline_workflow_image)

### Dashboard Overview
![Dashboard Overview](path_to_your_dashboard_overview_image)

## Components

1. **Bing API**: Source of news data.
2. **Azure Data Factory**: Orchestrates the data ingestion from the Bing API.
3. **JSON Files**: Raw data storage in One Lake.
4. **Synapse Data Engineering**: Data transformation and processing.
5. **Synapse Data Science**: Sentiment analysis on the ingested data.
6. **Data Activator**: (Not implemented) For setting up alerts and notifications.
7. **Power BI**: Data visualization and reporting.
8. **Microsoft Teams**: Collaboration and communication tool.

## Steps to Reproduce

### Environment Setup
1. **Azure Subscription**: Ensure you have an active Azure subscription.
2. **Resource Group**: Create a resource group for the project.
3. **Azure Services**: Deploy the necessary services:
   - Azure Data Factory
   - Azure Synapse Analytics
   - One Lake
   - Power BI
   - Microsoft Teams

### Data Ingestion
1. **Create Data Factory Pipeline**:
   - Use Azure Data Factory to create a pipeline to ingest news data from the Bing API.
   - Store the ingested data as JSON files in One Lake.

### Data Transformation
1. **Synapse Data Engineering**:
   - Transform the ingested JSON data using Synapse Data Engineering.

### Sentiment Analysis
1. **Synapse Data Science**:
   - Perform sentiment analysis on the transformed data.

### Data Visualization
1. **Power BI**:
   - Create a Power BI dashboard to visualize the sentiment analysis results.

### End-to-End Testing
1. **Pipeline Execution**:
   - Execute the entire pipeline to ensure data flows seamlessly from ingestion to visualization.
   - Validate the results in Power BI.

## Dashboard

The dashboard provides a quick summary of the sentiment analysis, including:
- Count of sentiment by category.
- Count of date published by category.
- Detailed table of news articles with their sentiment scores.

### Example Visuals
![Quick Summary](path_to_your_quick_summary_image)
![Detailed Table](path_to_your_detailed_table_image)

## Future Work
- **Setting Up Alerts**: Implement alerts using Data Activator for real-time notifications.

## Conclusion

This project demonstrates a comprehensive data engineering workflow using Microsoft Azure and Microsoft Fabric. The integration of various Azure services allows for efficient data ingestion, transformation, analysis, and visualization, providing valuable insights from Bing News data.

## Author
Olisamedua Okafor
