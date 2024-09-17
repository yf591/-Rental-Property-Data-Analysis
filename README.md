# -Rental-Property-Data-Analysis

## Rental Property Data Analysis

This repository is a project aimed at acquiring and analyzing rental property data to **find undervalued properties**.

### Analysis Content

1. **Data Collection**:  Scrape rental property data from a rental property information website.
2. **Data Cleaning**: Remove unnecessary information from the acquired data and convert it into a format suitable for analysis.
3. **Data Analysis**:
    - Analyze the relationship between property features (rent, area, age, etc.).
    - Build a rent prediction model using Ordinary Least Squares (OLS) regression analysis.
    - Conduct regression diagnostics to evaluate the accuracy and reliability of the model.
4. **Undervalued Property Extraction**: Compare the predicted rent with the actual rent to extract undervalued properties.
5. **Output Results**: Output the information of undervalued properties to CSV and Excel files.

### Technologies Used

- Python
- BeautifulSoup (Scraping)
- Pandas, NumPy (Data analysis)
- Matplotlib, Seaborn (Data visualization)
- Statsmodels (Regression analysis)
- Scikit-learn (Machine learning)

### How to Use

1. Install the libraries listed in `requirements.txt`.
2. Run `rental_property_scraper.py` to acquire property data from the rental property information website. (Specify the target website URL within the script.)
3. Run `data_analysis.py` to perform data analysis and extract undervalued properties.
4. The results will be output to `reasonable_houses_merged.csv` and `reasonable_houses_merged.xlsx`.

### Notes

- Changes in the structure of the scraping target website may cause the scraping process to malfunction.
- The analysis results are merely predictions and do not guarantee the actual value of the property.
- When scraping, be sure to carefully check the terms of use of the target website.

### Future Prospects

- Collect more property information to improve analysis accuracy.
- Conduct analysis incorporating property location information and surrounding environment.
- Perform more advanced analysis using machine learning models.
- Develop a user interface to make it easier to use.

### License

This project is released under the MIT License.

### Disclaimer

This project aims to analyze rental property information but is not affiliated with any specific website.
The author assumes no responsibility for any damages caused by this project.
