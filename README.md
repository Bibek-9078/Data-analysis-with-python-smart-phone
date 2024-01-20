# Data-analysis-with-python-smart-phone

This repository contains the code and notebooks for analyzing the Smart phone  Latest Dataset. The dataset provides valuable insights into Smart phone range of mobile devices, including specifications, ratings, prices and many more.

# Objectives

### 1. To find the top brands of smartphones in the market.

### 2. To find the price range of trending smartphones.

### 3. To find the ram capacity and internal memory which purchased more.

### 4. To find which processor is most used in the smartphones.

### 5. To find the number of cameras (rear and front ) in the smartphones, which is more purchased.

### 6. To find the market of ios or android.

# 1. Data Collection

To begin our analysis, we need data. There are various sources to obtain smartphones data such as online repositories, APIs, Publicly available dataset such as kaggle datasets. For this analysis I’ll be using the dataset that I have scraped from the smartprix website. Dataset contains following columns such as brand_name, model, price, rating, processor, screen_size, camera, operating system.

During the scraping process, a combination of Selenium and BeautifulSoup was utilized to extract the desired data. Selenium is a powerful tool for automating web browsers, allowing for the interaction with dynamic web pages. It can simulate user actions such as clicking buttons, filling out forms, and navigating through web pages. This makes it particularly useful when dealing with websites that heavily rely on JavaScript for content loading.

On the other hand, BeautifulSoup is a Python library that provides a convenient way to parse and extract data from HTML or XML documents. It simplifies the process of traversing the HTML structure and locating specific elements or tags of interest.

# Feature Description 

| Feature  | Description |
| --- | --- |
| **`brand_name`**                      | Brand name of smartphone (eg. oneplus, samsung, motorola, categorical) |
| **`model`**                           | Model name of smartphone (eg. OnePlus 11 5G, Samsung Galaxy A14 5G, neither numerical nor categorical) |
| **`price`**                           | Price of smartphone (eg. 30000, numeric)|
| **`rating`**                          | Rating of each smartphone given by consumer (eg. 89, 67, numerical ) |
| **`has_5g, has_nfc, has_ir_blaster`** | Smartphone conatining information of 5g, nfc and ir_blaster (eg. True, False, categorical )|
| **`processor_brand`**                 |  Smartphone with processor_brand name (eg. snapdragon, exynos, categorical ) |
| **`num_cores`**                       |Number of cores present in smartphone (eg. 8 = octacore, 6=hexacore, categorical )|
| **`screen_size `**                    | Rating of each smartphone given by consumer (eg. 89, 67, numerical ) |
| **`os `**                             |  Operating system of smartphone (eg. android, os, categorical ) |
                                    

# Exploratory Data Analysis (EDA)  

### Steps that I followed through out EDA :

**01.**  First of all try to find out type of columns (Is it numerical or categorical)

**02**.Based on type of columns perform univariate, bivariate and multivariate analysis.

**03**.Considering one columns at a time and performing EDA is called univariate analysis.

04.Considering two columns at a time to perform EDA is called bivariate analysis.

05.Considering more than two columns at a time to perform EDA is called multivariate analysis.

06.During bivariate analysis combination of columns may be (Numerical- Numerical, Numerical- Categorical, Categorical-Categorical)

07.During univariate analysis (numerical columns ) try to find out 5 number summary of basic statistics i.e mean, median, min, max, std, 1st quartile(25% data), 3rd quartile(75% data), range.

08.During univariate analysis if column is numerical then generally we plot (Histogram, KDE, Boxplot) to understand distribution and finding outliers present in dataset using boxplot.

09.During univariate analysis if column is categorical then generally we plot (Barplot, Pieplot) to understand distribution of data and finding out pattern.

10.During bivariate analysis if columns combination is (Numerical-Numerical ) then generally we plot (scatter plot) where we can see data distribution along with correlation between two features/columns.

11.During bivariate analysis if columns combination is (Numerical-Categorical) then we plot ( Bar plot) considering categorical columns on x-axis while numerical columns on y-axis, which help in analysis.

12.During bivariate analysis if columns combination is (Categorical-Categorical) then we generally plot (heatmap) and analyze by crosstab to understand data.

# Conclusion
I did exploratory data analysis of smartphone’s data in which I have found that top brands phone, top processor brands what ram capacity is more purchased in dataset. Price of smartphones varies with different features eg. os, camera, ram, internal memory, 5G, NFC and other features.

I did analysis of smartphone’s dataset and seen pattern and trend of smartphone’s market. I purchase Samsung’s smartphone with 8gb ram and 128 gb internal memory which I found in my analysis, these features were dominating in my dataset. 
