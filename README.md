🧹 Task 1 – Data Cleaning and Preprocessing
📊 Dataset Used: Mall Customer Segmentation
🛠 Tools: Python (Pandas)

✅ What I Did
This task focused on preparing a raw dataset for analysis by identifying and fixing common data quality issues. Here's a quick overview of the cleaning process:

🔍 Checked for Missing Values
I used .isnull() to scan the dataset and confirmed there were no missing values to handle.

🔁 Removed Duplicate Records
I checked for duplicate rows using .duplicated() and found none, so no rows were dropped.

🧼 Cleaned and Standardized Text
The Gender column was cleaned by removing any whitespace and standardizing the values (e.g., capitalizing “male” and “female”).

✍️ Renamed Columns for Consistency
All column headers were converted to lowercase and formatted with underscores instead of spaces. For example, Annual Income (k$) became annual_income_(k$).

🔢 Verified and Adjusted Data Types
Ensured that numeric fields like age, annual_income_(k$), and spending_score_(1-100) were stored as integers for proper analysis.

📁 Final Output:
The cleaned and preprocessed dataset was saved as cleaned_mall_customers.csv, ready for analysis or modeling.