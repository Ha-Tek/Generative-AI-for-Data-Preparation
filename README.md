# Hands-on Project: Generative AI for Data-Preparation
In practice, the initial stage of a data science workflow involves cleaning and preparing data for analysis, including removing blank entries, normalizing numerical attributes, and converting categorical variables into numerical representations. In this project, generative AI creates Python code to perform these preprocessing tasks on a real-world dataset.

Source: [Coursera](https://www.coursera.org/learn/generative-ai-elevate-your-data-science-career/ungradedLti/CQM2B/hands-on-lab-generative-ai-for-data-preparation)


## Objectives

In this project, we will learn how to use generative AI for creating a Python code to:

- Handle missing values in the data set
- Correct the data type for the required data set attributes
- Perform standardization and normalization on required parameters
- Convert categorical data into numerical indicator variables



## Dataset

The dataset for this project is available at the following URL:

```python
URL = (
    "https://storage.googleapis.com/kagglesdsdata/datasets/3057690/5254982/laptops_test.csv"
    "?X-Goog-Algorithm=GOOG4-RSA-SHA256"
    "&X-Goog-Credential=gcp-kaggle-com%40kaggle-161607.iam.gserviceaccount.com%2F20261028%2Fauto%2Fstorage%2Fgoog4_request"
    "&X-Goog-Date=20261028T175515Z"
    "&X-Goog-Expires=259200"
    "&X-Goog-SignedHeaders=host"
    "&X-Goog-Signature=918393ae103b1ad06c2a1deb37ed3a02ff71444115ef504df0fd7aa0612a1818685dc2eb94c720144d4b396a4768fc7c8ab585eb7413e3ccaea11664fd83b9ac53e83fbcca47539869b886bbb976aa5f581e7bc67ad42bc5a709ba749a6d4dc9e1583c41da5d7ac1129eec6110ecd53239eaacd4ac3085b971c00d63bbd4b8680f6f0a23ed107752125628793edb9ca496c696505aa44c53fc192c0cbe2a3346e5f432295865251d84fed4ec61978963b0cfe302da85c014cf4df27fcb84b6285119e7e6f37114a45f89d95229dfc03067e2e1a7f9f2b57e48f81302343d90cfd7999c6952078e6010d032d969ae95faef729f2677d882aea3484a36ddd4dc51"
)
```

This dataset [**Laptop Price Prediction using Specifications**](https://www.kaggle.com/datasets/arnabchaki/laptop-price-prediction?resource=download) or dataset uploaded with file name [laptop_pricing_dataset.csv](https://storage.googleapis.com/kagglesdsdata/datasets/3057690/5254982/laptops_test.csv"
    "?X-Goog-Algorithm=GOOG4-RSA-SHA256"
    "&X-Goog-Credential=gcp-kaggle-com%40kaggle-161607.iam.gserviceaccount.com%2F20261028%2Fauto%2Fstorage%2Fgoog4_request"
    "&X-Goog-Date=20261028T175515Z"
    "&X-Goog-Expires=259200"
    "&X-Goog-SignedHeaders=host"
    "&X-Goog-Signature=918393ae103b1ad06c2a1deb37ed3a02ff71444115ef504df0fd7aa0612a1818685dc2eb94c720144d4b396a4768fc7c8ab585eb7413e3ccaea11664fd83b9ac53e83fbcca47539869b886bbb976aa5f581e7bc67ad42bc5a709ba749a6d4dc9e1583c41da5d7ac1129eec6110ecd53239eaacd4ac3085b971c00d63bbd4b8680f6f0a23ed107752125628793edb9ca496c696505aa44c53fc192c0cbe2a3346e5f432295865251d84fed4ec61978963b0cfe302da85c014cf4df27fcb84b6285119e7e6f37114a45f89d95229dfc03067e2e1a7f9f2b57e48f81302343d90cfd7999c6952078e6010d032d969ae95faef729f2677d882aea3484a36ddd4dc51), which is available on [**Kaggle**](https://www.kaggle.com/) under the [**Database Contents License (DbCL) v1.0**](https://opendatacommons.org/licenses/dbcl/dbcl-10.txt). 
