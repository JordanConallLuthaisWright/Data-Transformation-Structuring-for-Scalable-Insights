
# Data Transformation & Structuring for Scalable Insights at Company XYZ 

***(Dataset taken from Kraggle)***

## Project Overview
This project focuses on transforming **unstructured JSON event data** into **structured CSV tables** for improved accessibility and analysis within **Company XYZ**. The dataset originates from **app-generated events and backend APIs**, requiring data engineering processes to ensure **data quality and usability**.

The goal is to **extract, transform, and format** key attributes from `case.json` into three structured CSV files:
- `CuratedOfferOptions.csv`
- `DynamicPriceOption.csv`
- `DynamicPriceRange.csv`

The transformation process prioritizes:
- **Data integrity** and structured formatting
- **Efficient processing** using Python
- **Localization** (UTC-3 conversion for timestamps)
- **Partitioning data** based on event types for clarity

## Tech Stack & Skills Demonstrated
- **Python**: Data processing and transformation
- **Pandas**: Data manipulation and structuring
- **JSON Parsing**: Extracting nested data
- **Time Zone Conversion**: Adjusting timestamps to UTC-3
- **Data Engineering**: Formatting and structuring large event datasets

## Data Description
The dataset consists of **JSON event records**, each containing:
- **EnqueuedTimeUTC** – Timestamp of the event (UTC timezone)
- **EventName** – Type of event
- **Payload** – Event-specific details in nested JSON format

The dataset includes two event types:
- **DynamicPrice_Result** → Used to generate `DynamicPriceOption.csv` & `DynamicPriceRange.csv`
- **CuratedOffer_Result** → Used to generate `CuratedOfferOptions.csv`

## Transformation Rules
Each CSV file follows predefined formatting rules:
- **Quoted fields**: Text-based attributes (e.g., Provider, OfferId, ProductBrand)
- **Non-quoted fields**: Numeric values (e.g., Prices, ChamaScore)
- **Date formatting**: Converted to `DD/MM/YYYY` in **UTC-3**

## How to Run
1. Install dependencies (if not already installed):
   ```bash
   pip install pandas
