# Rental-Property-Data-Analysis

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

-----------------

## 賃貸物件データ分析

このリポジトリは、賃貸物件データを取得・分析し、**割安な物件を見つける**ことを目的としたプロジェクトです。

### 分析内容

1. **データ収集**: 賃貸物件情報サイトからスクレイピングにより物件データを取得します。
2. **データクレンジング**: 取得したデータから不要な情報を削除し、分析に適した形式に変換します。
3. **データ分析**:
    - 物件の特徴量（家賃、面積、築年数など）の関係性を分析します。
    - 最小二乗法を用いた回帰分析により、家賃の予測モデルを構築します。
    - 回帰診断を行い、モデルの精度や信頼性を評価します。
4. **割安物件の抽出**: 予測モデルと実際の賃料を比較し、割安な物件を抽出します。
5. **結果の出力**: 割安物件の情報をCSVファイルとExcelファイルに出力します。

### 使用技術

- Python
- BeautifulSoup (スクレイピング)
- Pandas, NumPy (データ分析)
- Matplotlib, Seaborn (データ可視化)
- Statsmodels (回帰分析)
- Scikit-learn (機械学習)

### 使用方法

1. `requirements.txt` に記載されているライブラリをインストールします。
2. `rental_property_scraper.py` を実行して、賃貸物件情報サイトから物件データを取得します。（対象サイトのURLはスクリプト内で指定してください。）
3. `data_analysis.py` を実行して、データ分析と割安物件の抽出を行います。
4. 結果は `reasonable_houses_merged.csv` と `reasonable_houses_merged.xlsx` に出力されます。

### 注意点

- スクレイピング対象のサイトの構造変更により、スクレイピング処理が正しく動作しなくなる可能性があります。
- 分析結果はあくまでも予測であり、実際の物件の価値を保証するものではありません。
- スクレイピングを行う際は、対象サイトの利用規約をよく確認してください。

### 今後の展望

- より多くの物件情報を収集し、分析精度を向上させる。
- 物件の立地情報や周辺環境などの情報を加味した分析を行う。
- 機械学習モデルを用いたより高度な分析を行う。
- ユーザーインターフェースを作成し、より使いやすくする。

### ライセンス

このプロジェクトはMITライセンスで公開されています。


### 免責事項

このプロジェクトは、賃貸物件情報を分析することを目的としていますが、特定のサイトとは一切関係ありません。
このプロジェクトによって生じた損害について、作者は一切の責任を負いません。

This project aims to analyze rental property information but is not affiliated with any specific website.
The author assumes no responsibility for any damages caused by this project.
