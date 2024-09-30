![image](https://github.com/user-attachments/assets/9a2e5f4e-51de-488b-9f4a-ca58cc3389a4)

# HR-data-analysis

### **ETL Process Report for HR Data**

### 1. **Extract Phase**

Import excel file to power Bi

### 2. **Transform Phase**

The transformation phase involves cleaning and shaping the data to make it suitable for analysis. Typical steps include:

- **Data cleaning**:
    - Handling missing values (e.g., replacing null values, removing irrelevant rows).
    - Standardizing inconsistent formats (e.g., date formats, number formats).
    - Removing duplicates.
- **Data manipulation**:
    - Joining multiple excel sheets by creating a function to do that in power query in power Bi.
    - Creating new columns.
    - Encoding categorical data enter those values into new columns (e.g.”WFH “ =1 and “HWFH”=0.5 else 0  like that).
- **Feature engineering**:
    - Creating new metrics or dimensions .

**Tools used**: Power BI's Power Query Editor,, DAX (Data Analysis Expressions) for calculated columns/measures.

### 3. **Load Phase**

After transforming the data, it is loaded into Power BI for analysis and visualization. The clean, processed data is stored within the Power BI data model, ready to be used for creating dashboard.
