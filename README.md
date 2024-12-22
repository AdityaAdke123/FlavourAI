# FlavourAI
Personalized Dish Recommendation System

FlavourAI is a personalized dish recommendation system that suggests recipes tailored to user preferences. By leveraging natural language processing and machine learning techniques, it analyzes user input to provide customized recipe recommendations.

Dataset: https://www.kaggle.com/datasets/irkaal/foodcom-recipes-and-reviews

Output:-
![Screenshot 2024-12-21 201801](https://github.com/user-attachments/assets/d42711f1-9520-42e6-a62e-280a22777a5f)

![Screenshot 2024-12-21 201858](https://github.com/user-attachments/assets/ef00b555-68f1-462d-aae7-ebff8025873c)

Features
Content-Based Filtering: Utilizes Sentence-BERT embeddings and cosine similarity to match user queries with relevant recipes.

Extensive Recipe Database: Processes a dataset of over 550,000 recipes, ensuring a wide variety of options.

Streamlit Web Application: Provides an interactive user interface for seamless recipe exploration.

Dataset
The project uses the Food.com Recipes and Reviews dataset from Kaggle, which includes a comprehensive collection of recipes and user reviews.

Installation
Clone the repository:

bash
Copy code
git clone https://github.com/AdityaAdke123/FlavourAI.git
Navigate to the project directory:

bash
Copy code
cd FlavourAI
Install the required packages:

bash
Copy code
pip install -r requirements.txt
Usage
Run the Streamlit application:

bash
Copy code
streamlit run app.py
Interact with the app:

Enter your food preferences or dietary requirements in natural language.

Receive personalized recipe recommendations based on your input.

Data Preprocessing
The dataset undergoes several preprocessing steps to enhance recommendation accuracy:

Keyword Standardization: Cleans and standardizes recipe keywords for consistency.

Nested Structure Handling: Flattens nested data structures to simplify analysis.

Embedding Generation: Generates dense vector embeddings for each recipe using Sentence-BERT, facilitating efficient similarity calculations.

Model Evaluation
The recommendation system's performance is evaluated using:

Cosine Similarity: Measures the similarity between user queries and recipe embeddings.

User Feedback: Assesses recommendation relevance based on user interactions.

Contributing
Contributions are welcome! Please fork the repository and submit a pull request with your enhancements.

License
This project is licensed under the MIT License. See the LICENSE file for details.

Acknowledgements
Special thanks to Kaggle for providing the dataset and to the open-source community for their invaluable tools and resources.

