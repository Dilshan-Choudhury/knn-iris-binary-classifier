# 🌸 Iris Binary Classification using KNN

This project demonstrates how to use the **K-Nearest Neighbors (KNN)** algorithm to perform binary classification on the Iris dataset. The goal is to classify whether a flower is **Setosa (1)** or **Not Setosa (0)**, along with visualization of model performance.

---

## 🚀 Features

* KNN-based binary classification
* Adjustable `k` value for experimentation
* Uses Iris dataset (converted to binary)
* Model evaluation:

  * Accuracy
  * Confusion Matrix
  * Classification Report
* Visualization using Seaborn heatmap

---

## 🛠️ Tech Stack

* Python
* Pandas
* NumPy
* Scikit-learn
* Matplotlib
* Seaborn

---

## 📂 Project Structure

```id="proj-struct-knn"
knn-iris-binary-classifier/
│
├── knn_classifier.py     # Main script
├── README.md             # Documentation
```

---

## ⚙️ How It Works

1. Load Iris dataset from online source
2. Convert labels into binary:

   * Setosa → 1
   * Others → 0
3. Split dataset into training and testing sets
4. Apply KNN algorithm with chosen `k` value
5. Predict results on test data
6. Evaluate performance using:

   * Accuracy
   * Confusion Matrix
   * Classification Report
7. Visualize confusion matrix using heatmap

---

## ▶️ Usage

1. Clone the repository:

```id="clone-knn"
git clone https://github.com/your-username/knn-iris-binary-classifier.git
cd knn-iris-binary-classifier
```

2. Install dependencies:

```id="install-knn"
pip install pandas numpy matplotlib seaborn scikit-learn
```

3. Run the script:

```id="run-knn"
python knn_classifier.py
```

---

## 📊 Example Output

```id="output-knn"
=== RESULTS ===
Accuracy: 1.0

Confusion Matrix:
[[20  0]
 [ 0 10]]
```

A confusion matrix heatmap will also be displayed.

---

## 📌 Key Concepts

* K-Nearest Neighbors (KNN)
* Distance-based classification
* Binary classification
* Confusion Matrix visualization
* Model evaluation metrics

---

## 💡 Future Improvements

* Optimize best `k` using cross-validation
* Extend to multi-class classification
* Add GUI (Tkinter / Streamlit)
* Deploy as a web app

---

## 🤝 Contributing

Feel free to fork the project and submit improvements!

---

## 📜 License

This project is open-source under the MIT License.
