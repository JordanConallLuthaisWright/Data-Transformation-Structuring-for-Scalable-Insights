
# Data Transformation & Structuring for Scalable Insights at Company XYZ 

***(Dataset taken from Kraggle)***

## Project Overview
This project focuses on **transforming unstructured JSON event data** into **structured CSV tables** for improved accessibility and analysis within **Company XYZ**. The dataset originates from **app-generated events and backend APIs**, requiring **data engineering processes** to ensure **data quality and usability**.

By leveraging **data preprocessing, JSON parsing, time zone conversion, and data transformation**, this project structures event data for business insights. Key tasks include **partitioning event types, extracting nested data, and standardizing formats**, ensuring high-quality data for downstream analysis.

The structured datasets support **decision-making, business intelligence, and performance analysis**, demonstrating practical **data engineering** skills in real-world applications.

The goal is to **extract, transform, and format** key attributes from `case.json` into three structured CSV files:
- `CuratedOfferOptions.csv`
- `DynamicPriceOption.csv`
- `DynamicPriceRange.csv`

## **Project Aim**  
This project aims to **convert raw JSON event data into structured CSV files**, enhancing **data accessibility, integrity, and analysis** for Company XYZ.

The transformation process prioritizes:
- **Data integrity** and structured formatting
- **Efficient processing** using Python
- **Localization** (UTC-3 conversion for timestamps)
- **Partitioning data** based on event types for clarity

---

## Tech Stack & Skills Demonstrated
- **Python**: Data processing and transformation
- **Pandas**: Data manipulation and structuring
- **JSON Parsing**: Extracting nested data
- **Time Zone Conversion**: Adjusting timestamps to UTC-3
- **Data Engineering**: Formatting and structuring large event datasets

## **Technical Skills Demonstrated**  
- **Data Preprocessing & Cleaning**: Extracting **nested JSON fields** and structuring datasets.  
- **Event-Based Data Transformation**: Partitioning data by event type for meaningful organization.  
- **Time Zone Conversion**: Adjusting timestamps to **UTC-3** for localization.  
- **Data Engineering & Structuring**: Formatting data into structured CSV outputs.  
- **Pandas & Python**: Manipulating large-scale data efficiently.  

---

## **Files in This Repository**  

| File                          | Description |
|--------------------------------|------------|
| `Data Transformation & Structuring for Scalable Insights at Company XYZ.ipynb` | Jupyter Notebook with data transformation steps. |
| `case.json`                    | Raw JSON dataset containing event records. |
| `CuratedOfferOptions.csv`       | Processed CSV output with curated offers. |
| `DynamicPriceOption.csv`        | Processed CSV output with dynamic pricing options. |
| `DynamicPriceRange.csv`         | Processed CSV output with pricing ranges. |
| `README.md`                     | Project documentation. |

---

## Transformation Rules
Each CSV file follows predefined formatting rules:
- **Quoted fields**: Text-based attributes (e.g., Provider, OfferId, ProductBrand)
- **Non-quoted fields**: Numeric values (e.g., Prices, ChamaScore)
- **Date formatting**: Converted to `DD/MM/YYYY` in **UTC-3**

---

## **How to Run This Project**  

1. **Clone the repository**  
   ```bash
   git clone https://github.com/your-username/data-transformation-xyz.git
2. **Install Dependencies
bash
Copy
Edit

   
---

## Business Context & Problem Statement  

Company XYZ generates valuable **app event data**, but it's stored in an **unstructured JSON format**. To make informed business decisions, the data must be **structured, cleaned, and formatted into CSV files**.  

### Key Challenges:  
- **Transforming raw JSON events** into structured tables.  
- **Standardizing time zones** for accurate analysis.  
- **Ensuring data quality** through proper structuring.  

---

## Methodology & Technical Steps  

### **1. Data Preprocessing & Cleaning**  
- **Extracted nested JSON fields** from the `Payload` column.  
- **Mapped and structured event data** based on predefined rules.  

### **2. Event-Based Partitioning**  
- **DynamicPrice_Result** → Used to generate `DynamicPriceOption.csv` & `DynamicPriceRange.csv`.  
- **CuratedOffer_Result** → Used to generate `CuratedOfferOptions.csv`.  

### **3. Time Zone Adjustment**  
- Converted timestamps to **UTC-3** and formatted as **DD/MM/YYYY**.  

### **4. CSV Structuring**  
- **Ensured correct formatting** (quoted/non-quoted fields based on type).  
- **Validated final outputs** for consistency and completeness.  

---

## Key Takeaways & Impact  

- **Improved data accessibility** for Company XYZ.  
- **Standardized event processing** for app-generated data.  
- **Ensured high-quality, structured datasets** for future analysis.  
- **Demonstrated real-world data engineering techniques** in JSON processing.  

---

## Contact & Contributions  

Feel free to explore and contribute! If you have any suggestions, reach out or submit a pull request.  

- **Email**: [jordan.c.l.wright@gmail.com](mailto:jordan.c.l.wright@gmail.com)  

---

### **Author:** Jordan  
[GitHub Profile](https://github.com/JordanConallLuthaisWright)

