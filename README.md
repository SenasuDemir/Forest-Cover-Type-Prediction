# 🌲 Forest Cover Type Prediction

📌 **Project Aim**  
The objective of this project is to predict the **Cover Type** of a forested area using machine learning and deep learning models.  
We utilize various **geographical, topographical, and soil-related features** collected from the **US Geological Survey (USGS)** and **US Forest Service (USFS)**.  

🗂 **Dataset**: [Kaggle - Forest Cover Type Prediction](https://www.kaggle.com/competitions/forest-cover-type-prediction/data)  

## 🌍 **Introduction**
Forests are vital ecosystems that support biodiversity, climate regulation, and environmental sustainability.  
Accurately classifying forest cover types is essential for **conservation planning**, **wildlife habitat studies**, and **fire risk assessment**.

### 📊 **Dataset Features**
This dataset includes **geographical and environmental features**, such as:
- **Elevation & Slope** – Helps understand terrain variations.
- **Distance to Water & Roadways** – Important for accessibility and moisture levels.
- **Soil Type & Wilderness Areas** – Key indicators of vegetation patterns.
- **Hillshade (Sunlight Exposure)** – Affects plant growth and forest structure.

### 🌳 **Cover Type Classes**
The dataset consists of **7 forest cover types**:
1️⃣ **Spruce/Fir**  
2️⃣ **Lodgepole Pine**  
3️⃣ **Ponderosa Pine**  
4️⃣ **Cottonwood/Willow**  
5️⃣ **Aspen**  
6️⃣ **Douglas-fir**  
7️⃣ **Krummholz**  

---

## 🚀 **Project Workflow**
✅ **Data Exploration & Visualization**  
✅ **Feature Engineering & Data Preprocessing**  
✅ **Machine Learning Model Training**  
✅ **Deep Learning Model Training**  
✅ **Performance Evaluation & Comparison**  

---

## 🛠 **Technologies & Tools Used**
- **Python** 🐍  
- **Pandas, NumPy** 📊 – Data manipulation & processing  
- **Matplotlib, Seaborn** 📉 – Data visualization  
- **Scikit-Learn** 🤖 – Machine learning models  
- **TensorFlow, Keras** 🔬 – Deep learning models  

---

## 📊 **Model Performance Summary**
| Model | Accuracy Score |
|--------|---------------|
| 🌳 **Random Forest Classifier** | **0.8661** |
| 📌 **K-Neighbors Classifier** | 0.8125 |
| 🌲 **Decision Tree Classifier** | 0.8044 |
| 🚀 **Gradient Boosting Classifier** | 0.8006 |
| 🧪 **Bernoulli Naïve Bayes** | 0.6087 |
| 🔬 **Gaussian Naïve Bayes** | 0.5999 |
| 📉 **Logistic Regression** | 0.4806 |
| 🤖 **Deep Learning Model** | 0.6806 |

✅ **Random Forest Classifier** achieved the highest accuracy (**86.61%**), followed by **KNN** (81.25%) and **Decision Tree** (80.44%).  
❌ **Deep Learning** underperformed compared to traditional ML models, achieving **68.06% accuracy**.

---

## 🔍 **Key Insights**
✔️ **Random Forest outperforms** other classifiers due to its ability to handle noise and prevent overfitting.  
✔️ **Deep Learning needs further tuning** (e.g., more layers, hyperparameter tuning) to improve performance.  
✔️ **Feature importance analysis** could refine model predictions and boost accuracy.  

--
