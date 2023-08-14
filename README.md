# ETL Project using Python

Welcome to the ETL (Extract, Transform, Load) project repository! This project focuses on automating the ETL process to extract bank and market capitalization data from a JSON file, transform the market capitalization currency from US dollars (USD) to British pounds (GBP) using exchange rate data, and finally load the transformed data into a separate CSV file. The script also includes logging to record each phase's activity in a log file.

## Project Overview

The main goal of this project is to streamline the ETL process for handling bank and market capitalization data. The ETL process consists of the following phases:

1. **Extraction:** The script extracts bank and market capitalization data from the `bank_market_cap.json` JSON file.

2. **Transformation:** The extracted data undergoes transformation, specifically converting market capitalization from USD to GBP using exchange rate data.

3. **Loading:** After transformation, the data is loaded into a CSV file named `transformed_data.csv`.

4. **Logging:** The script includes a logging feature that records each phase's activities, aiding in tracking the process.

## How to Run the Script

To execute the ETL process on your local machine, follow these steps:

1. Clone this repository using the following command: git clone https://github.com/MHMD1001/ETL-Using-Python.git

2. Navigate to the directory containing the script using the terminal or your preferred environment.

3. Make sure you have Python 3.x installed on your machine.

4. Open the script file,`Bank Marcet Cap ETL.ipynb`, using Jupyter Notebook or your preferred Python IDE.

5. Run the script cell by cell, following the comments and explanations provided within the script. The script will guide you through the ETL process, including extraction, transformation, and loading.

## Requirements

To run the script, you'll need the following dependencies:

- Python 3.x
- pandas (for data manipulation)
- JSON (for JSON file handling)

You can install these dependencies using the following command: pip install pandas


## Conclusion

This ETL project automates the process of extracting, transforming, and loading bank and market capitalization data. The transformation phase includes converting market capitalization from USD to GBP using exchange rate data. By following the steps outlined in the script and reviewing the log file for activities, you can seamlessly execute the ETL process and generate the transformed CSV file for further analysis.

Feel free to explore the script and customize it as per your requirements. If you have any questions or feedback, don't hesitate to reach out.

Happy ETL-ing!

Muhammad Fathi

