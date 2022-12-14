# Factors in department stores and shops that makes good sales

Analysis of factors that directly vary and the opposite variable

### Libraries used
- pandas==1.4.3
- numpy==1.22.3
- seaborn==0.11.2
- matplotlib==3.5.2
- flake8==5.0.4
- pycodestyle==2.9.1
- pycodestyle_magic==0.5

### Installation
run with python3.*

`pip install -r requirement.txt`

### Content

Do you wonder why stores with customer analytics sell so much? And why would a salesperson sell exactly what they want? Because data, anyway, has a lot of hidden powers. If not used to benefit Okay, I'll show you.

![graph](https://github.com/NineNatthanarong/analysis-of-product-sales/blob/main/output.png)

This graph shows the correlation per 1 million sales, most notably the number of children. With a very high positive correlation, even children at home were involved. Food type, location. And many things are very effective.

### Therefore, the first group of interest is children.

![graph](https://github.com/NineNatthanarong/analysis-of-product-sales/blob/main/output2.png)

![graph](https://github.com/NineNatthanarong/analysis-of-product-sales/blob/main/output3.png)

From the graph, it was found that when parents had children cause a lot of sales including children at home It's a very consistent variation.

### The second and third groups are the types of stores and items for sale.

![graph](https://github.com/NineNatthanarong/analysis-of-product-sales/blob/main/output4.png)

The graph shows that when selling at supermarkets and selling salads and flowers Over time, sales will increase. But not as important as children.

### The good side has passed, let's have a look. What are the bad aspects that cause less sales?

![graph](https://github.com/NineNatthanarong/analysis-of-product-sales/blob/main/output5.png)

The graph shows that the grocery store has the lowest sales. But it's normal because the size of the grocery store isn't that big. And its locations in San Francisco, Bellingham and Guadalajara have resulted in low sales.

### So what kind of marketing is the most profitable?

#### correlation store_sales(in millions) with media type The most 3 are

1.media_type_TV

2.media_type_Radio

3.media_type_Product Attachment

#### correlation store_cost(in millions) with media type The most 3 are

1.media_type_Radio

2.media_type_TV

3.media_type_Product Attachment

#### correlation unit_sales(in millions) with media type The most 3 are

1.media_type_Radio

2.media_type_Daily Paper, Radio, TV

3.media_type_Sunday Paper, Radio

From the text, it can be concluded that the 3 marketing that generates the most sales, profits and revenues are

#### 1.media_type_Radio
#### 2.media_type_TV
#### 3.media_type_Product Attachment
### Project Motivation
I'm searching for the data I need in Kaggle for analysis. I see marketing so I'm very interested in analyzing it. because I often go to the store So I wonder what factors make it sell well?
### File Description
**prediction.ipynb** -> jupyter notebook for data analysis

**media prediction and its cost.csv** -> data shop from [Kaggle](https://www.kaggle.com/)

**requirement.txt** -> require libraries to run
### Medium
- [Medium](https://medium.com/@ninenatthanarong/factors-in-department-stores-and-shops-that-makes-good-sales-3b5cb6434891)
### Authors

- [@NineNatthanarong](https://github.com/NineNatthanarong)
### Acknowledgements
- dataset reference
    - [https://www.kaggle.com/datasets/ramjasmaurya/medias-cost-prediction-in-foodmart](https://www.kaggle.com/datasets/ramjasmaurya/medias-cost-prediction-in-foodmart)
### License

[MIT](https://choosealicense.com/licenses/mit/)