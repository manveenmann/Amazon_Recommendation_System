#  **Amazon Product Recommendation Model**

# METHODOLOGY
![amazon_flowchart'](https://github.com/user-attachments/assets/1f90fe97-cc4f-49d7-8f40-641c591b81ad)

# DESCRIPTION

 **Dataset:** The dataset used for this project is loaded from a CSV file named **amazon_product.csv**.
 
**Data Preprocessing:** 1.Removed unnecessary columns such as id.
2.Tokenization and stemming were applied to the product titles and descriptions.

**Model:** The model uses TF-IDF Vectorization combined with Cosine Similarity to find the most similar products based on a user’s query.

**Output:** The system provides the top 10 most relevant products based on the input query.

# 3. Input / Output

**Input:** The user enters a product name or keyword in the search bar.

**Output:** The model returns a list of the top 10 products that match the query based on title and description similarity.



