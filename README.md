# AI-Powered Smart Shopping: Finding Healthier Food Alternatives
## Full README

### Project Overview
This repository contains the code and resources for the project titled **AI-Powered Smart Shopping: Finding Healthier Food Alternatives with Personalized Recommendations**. The goal of this project is to leverage advanced machine learning and data analytics techniques to provide users with healthier alternatives to their selected food items. The project incorporates data cleaning, clustering, embedding visualizations, and personalized ranking algorithms to optimize food recommendations based on nutritional constraints and preferences.

---

### Features
- **Data Cleaning**: Preprocessing and handling missing or abnormal values in the Open Food Facts dataset.
- **Embedding Visualizations**: Representing food items using BERT embeddings and t-SNE.
- **Nutritional Quality Scoring**: Using Nutri-Score, FSANZ, and NOVA to assess food healthfulness.
- **Clustering and Ranking**: Employing KMeans clustering and LambdaMART (LightGBM) for efficient and accurate personalized recommendations.
- **Comparison Analysis**: Evaluating the algorithm's recommendations against GPT-generated alternatives.

---

### Data Source
The dataset used in this project is sourced from [Open Food Facts](https://world.openfoodfacts.org), a collaborative database of food products from around the globe, containing nutritional information, ingredients, and other metadata.

---

### Models and Algorithms
- **KMeans Clustering**: For grouping similar products based on nutritional attributes.
- **BERT Embeddings**: To capture semantic information from product descriptions and ingredients.
- **LambdaMART with LightGBM**: For ranking filtered candidates based on nutritional scores.
- **t-SNE**: For dimensionality reduction and visualization of food categories.

---

### Project Workflow
1. **Data Cleaning and Preprocessing**:
   - Handled missing values by removing columns with >50% missing data.
   - Standardized numerical features for clustering and ranking.

2. **Embedding Visualization**:
   - Used BERT embeddings and t-SNE to visualize relationships between food products.

3. **Nutritional Scoring**:
   - Implemented Nutri-Score, FSANZ, and NOVA scores to evaluate food healthfulness.

4. **Personalized Recommendation System**:
   - Clustered products using KMeans.
   - Ranked healthier alternatives with LightGBM's LambdaMART algorithm.

5. **Robustness and Consistency Analysis**:
   - Compared recommendations with GPT-generated alternatives.
   - Performed ANOVA and t-tests to validate statistical significance.

---

### Medium Article
For an in-depth explanation of the project, check out our Medium post: [AI-Powered Smart Shopping](https://medium.com/@shibo_63715/ai-powered-smart-shopping-finding-healthier-food-alternatives-with-personalized-recommendations-547cfc6aa20b).

---

### Getting Started
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/ai-food-recommendation.git
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Download the dataset from [Open Food Facts](https://world.openfoodfacts.org) and place it in the `data/` directory.
4. Run the notebooks step-by-step:
   - **Step 0**: Random Shopping List Creator
   - **Step 1**: Data Cleaning OpenFoodFact
   - **Step 2**: Example OpenFoodFact Linked Shopping List
   - **Step 3**: BERT Embedding Visualization
   - **Step 4**: Category Analysis
   - **Step 5**: Unhealthfulness Score Calculation
   - **Step 6**: Processing Score Calculation
   - **Step 7**: Similarity Calculation
   - **Step 8**: Shopping List Analysis

---

### File Structure
```
.
├── data/                # Folder for raw and processed data
├── notebooks/           # Jupyter notebooks for each step of the analysis
├── models/              # Saved models and outputs
├── requirements.txt     # Python dependencies
├── README.md            # This README file
```

---

### Key Contributors
- **Shi Bo**: Machine learning model development and recommendation system implementation.
- **Tianyuan Hu**: Data cleaning, visualization, and management.
- **Guanlan Hu**: Nutritional score modeling and embedding techniques.
- **Shilong Li**: Statistical analysis and robustness testing.

---

### Challenges
- Handling missing and inconsistent data in the Open Food Facts dataset.
- Designing robust nutritional scoring and recommendation algorithms.
- Evaluating the algorithm's performance against generative AI recommendations.

---

### Future Work
- Expand the dataset to include more diverse products and regions.
- Improve recommendation algorithms for highly processed foods.
- Integrate real-time user feedback to enhance recommendation accuracy.

---

### License
This project is licensed under the MIT License.

---

### Contact
For questions or collaborations, please contact **Shi Bo** at `boshi1@seas.upenn.edu`.

---
