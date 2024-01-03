Project Description:

    This repository houses a Python script designed to perform a detailed analysis of eBay search results for a specified item. By leveraging the power of Selenium for web scraping, the script extracts median prices, applies statistical methods to identify outliers, and records the results in an Excel file. This project serves as a practical example of web scraping techniques applied to e-commerce data.

Python Libraries Used:

    The project relies on the following Python libraries:
        Selenium: Used for web scraping and browser automation.
        NumPy: Utilized for numerical operations and percentile calculations.
        openpyxl: Employed for handling Excel files and storing analysis results.
        datetime: Used for obtaining the current date.
        time: Included for introducing delays in the script execution.
    Reasons for Usage:
        Selenium provides a powerful tool for automating web interactions, making it suitable for web scraping tasks.
        NumPy simplifies statistical calculations, crucial for identifying and handling outliers.
        openpyxl facilitates easy manipulation of Excel files, enabling data storage and analysis.
        datetime is used to timestamp each data entry with the current date, providing a record of when the analysis was performed.
        time is employed to introduce a delay after submitting the search query to eBay, ensuring that the search results have loaded before attempting to scrape them.

Methods of Using the Software:

    To use the software, follow these steps:
        Run the script.
        Input the desired item name when prompted.
        Observe the script fetching eBay search results, calculating median prices, and filtering outliers.
        The results, including the current date and average price, are recorded in an Excel file named price.xlsx.
