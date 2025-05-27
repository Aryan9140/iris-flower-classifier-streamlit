
# 🌸 Iris Flower Classifier - Streamlit App

This is a web application built using **Streamlit** that classifies Iris flower species based on user input features. The app uses a **Random Forest Classifier** trained on the classic **Iris dataset** from scikit-learn.

---

## 🚀 Features

- Interactive sliders to input flower features.
- Real-time prediction of flower species.
- Visualization of sample data.
- Simple and elegant UI with Streamlit.

---

## 📦 Tech Stack

- **Python**
- **Streamlit**
- **Pandas**
- **Scikit-learn**

---

## 🧠 Model Used

- **RandomForestClassifier** from scikit-learn
- Dataset: `load_iris()` from `sklearn.datasets`

---

## 📊 Input Features

| Feature          | Description              |
|------------------|--------------------------|
| Sepal Length (cm)| Length of the sepal      |
| Sepal Width (cm) | Width of the sepal       |
| Petal Length (cm)| Length of the petal      |
| Petal Width (cm) | Width of the petal       |

---

## 🛠️ How to Run Locally


   # 📁 1. Clone the repository
git clone https://github.com/your-username/iris-flower-classifier-streamlit.git
cd iris-flower-classifier-streamlit

# 🛠️ 2. (Optional) Create and activate virtual environment
# For Linux/Mac:
python -m venv venv
source venv/bin/activate

# For Windows:
python -m venv venv
venv\Scripts\activate

# 📦 3. Install dependencies
pip install -r requirements.txt

# 🚀 4. Run the Streamlit app
streamlit run app.py


# 📁 Project Structure

iris-flower-classifier-streamlit/
│
├── app.py               # Main Streamlit application
├── requirements.txt     # Python dependencies
└── README.md            # Project documentation




# ✅ Sample Output

🎯 Prediction: Iris-setosa, Iris-versicolor, or Iris-virginica  
🧪 Real-time predictions with interactive sliders  
📋 Top rows of the Iris dataset displayed in a table


