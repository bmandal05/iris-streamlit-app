# 🌼 Iris Flower Species Classifier 🌿

A simple machine learning web app built with **Streamlit** that predicts the species of an Iris flower based on its petal and sepal dimensions.  
The model is trained using a **Random Forest Classifier** on the classic Iris dataset.

---

## 🚀 Features

- 🖱️ Interactive sliders to input Sepal and Petal measurements
- 🤖 Predicts between: **Setosa**, **Versicolor**, **Virginica**
- 📊 Visual bar chart showing class probabilities
- ⚡ Lightweight and fast — built with Streamlit
- 💾 Trained ML model saved using `joblib`

---

## 🧰 Project Structure

iris-streamlit-app/
├── app.py # Streamlit web app
├── train_model.py # Script to train and save the model
├── model.pkl # Trained ML model file
├── requirements.txt # Python dependencies
└── README.md # Project documentation


---

## 🧠 Model Details

- **Dataset**: Iris (from scikit-learn)
- **Algorithm**: Random Forest Classifier
- **Accuracy**: ~97%
- **Exported using**: `joblib`

---

## 🖥️ How to Run the App Locally

```bash
git clone https://github.com/YOUR_USERNAME/iris-streamlit-app.git
cd iris-streamlit-app
pip install -r requirements.txt
python train_model.py   # optional
streamlit run app.py
