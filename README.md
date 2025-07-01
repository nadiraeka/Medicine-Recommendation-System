## Medicine Recommendation System Using Content-Based Filtering

### 📄 Description
<div align="justify">

This project builds a hybrid **Medicine Recommendation System** that combines **disease classification based on symptoms** with a **content-based medicine recommendation engine**. Two comprehensive datasets were used: one containing detailed information on Indian medicines, and another with medicine usage, side effects, and substitutes. The process starts with extensive data cleaning, including handling duplicates and irrelevant columns. Exploratory analysis was performed using summary statistics and visualizations to understand medicine attributes like price and composition. For classification, symptoms are encoded and machine learning models such as **Decision Tree**, **Random Forest**, and **SVM** are trained to predict diseases. Based on the prediction, the system recommends a corresponding medicine. In parallel, a **content-based recommendation system** was developed using **TF-IDF vectorization** and **cosine similarity** to suggest similar medicines based on descriptions and salt compositions. Additional modeling with **Word2Vec embeddings** was also explored to enhance semantic matching. Statistical analysis using **VIF** and correlation heatmaps was used to inspect multicollinearity and relationships among features. The final models were saved using `pickle`, enabling integration into real-world applications.

[Interactive Dashboard](http:/ristek.link/SomniumDashboard)
</div>

### 🛠 Tools & Libraries
- Python, Jupyter Notebook  
- `pandas`, `numpy`, `re`, `tqdm` for data preprocessing and manipulation
- `statsmodels`, `scipy.stats`, `variance_inflation_factor` for statistical analysis   
- `matplotlib`, `seaborn`, `plotly.express` for visual exploration  
- `scikit-learn` for machine learning:
  - `DecisionTreeClassifier`, `RandomForestClassifier`, `SVC`
  - `LabelEncoder`, `train_test_split`, `accuracy_score`
- `gensim` for modelling  
- `sklearn.feature_extraction.text.TfidfVectorizer` and `cosine_similarity` for content-based recommendation  
- `pickle` for model persistence

<div align='center'>

<img src="https://github.com/user-attachments/assets/dcb5aeee-4d92-4993-89dc-4ec064df526a" width="400" />
  <img src="https://github.com/user-attachments/assets/9efa9b04-6d85-4493-b1c4-5da6e6c3ce80" width="400" />
  <img src="https://github.com/user-attachments/assets/56d8fb99-5cae-4140-bdb8-d61a2994fd1e" width="400" />
  <img src="https://github.com/user-attachments/assets/24b9d363-a2e7-4c6c-a869-cc7cc2cd08a7" width="400" />
  <img src="https://github.com/user-attachments/assets/29b57472-e334-43d4-a6e2-a61ccb4362fe" width="400" />

</div>

