#  **Amazon Product Recommendation Model**

# METHODOLOGY
![amazon_flowchart'](https://github.com/user-attachments/assets/1f90fe97-cc4f-49d7-8f40-641c591b81ad)

# DESCRIPTION

 **Dataset:** The dataset used for this project is loaded from a CSV file named **amazon_product.csv**.
 
**Data Preprocessing:** 1.Removed unnecessary columns such as id.
2.Tokenization and stemming were applied to the product titles and descriptions.

**Model:** The model uses TF-IDF Vectorization combined with Cosine Similarity to find the most similar products based on a user’s query.

**Output:** The system provides the top 10 most relevant products based on the input query.

# Input / Output

**Input:** The user enters a product name or keyword in the search bar.

**Output:** The model returns a list of the top 10 products that match the query based on title and description similarity.


![amazon_table](https://github.com/user-attachments/assets/628fe168-e884-43a1-858e-3a3a349d77c6)


# INTERFACE
![amazon_readme](https://github.com/user-attachments/assets/20e65ddf-4594-4420-9864-8a32f6420342)


# INSTALLATION
To run this project locally, follow these steps:

1.Clone the repository.

2.Ensure you have the necessary dependencies installed:

**pip install pandas scikit-learn streamlit pillow nltk**

3.Download NLTK data (if not already installed):

**import nltk**
**nltk.download('all')**

4.Run the Streamlit app:

**streamlit run your_script_name.py**





