# Intrusion Detection System Using Machine Learning 🚀

### A comprehensive solution for detecting network intrusions using advanced machine learning algorithms.

---

## 📋 Overview
With the rise in cybersecurity threats, securing systems against intrusions has become critical. This project, **Intrusion Detection System Using Machine Learning**, leverages various machine learning algorithms to identify and classify network packets as either normal or malicious.

The system is designed to:
- Detect multiple types of intrusions, including **DOS attacks**, **worms**, and **backdoors**.
- Use supervised learning algorithms for enhanced detection accuracy.
- Provide a modular and scalable solution for intrusion detection.

---

## 🔍 Key Features
- **Multi-Model Comparison**: Evaluates models like Decision Trees, Logistic Regression, Naive Bayes, SVM, and Linear Regression.
- **High Detection Accuracy**:
  - Achieves **87.5% accuracy** with Decision Trees for detecting malicious packets.
  - True Positive Rate for normal packets: **100%**.
- **Ease of Extension**: Easily train the system for new attack categories.
- **Comprehensive Dataset Usage**:
  - **UNSW-NB15 Dataset**: Covers 9 different types of attacks and normal traffic data.
  - Includes preprocessing techniques such as standard scaling and label encoding.

---

## 📊 Methodology
The project follows these stages:
1. **Data Preprocessing**:
   - Standard scaling for numerical data.
   - Label encoding for categorical attributes like attack types.
2. **Model Training and Testing**:
   - Models compared for accuracy, confusion matrix, and classification reports.
   - Decision Trees showed the best performance for prediction.
3. **Prediction and Evaluation**:
   - Separate prediction dataset used to evaluate the model's effectiveness.
   - System generates actionable alerts for anomalous packets.

---

## 📂 Project Structure
- **Datasets**:
  - Training Dataset: 83,000 records.
  - Prediction Dataset: 173,000 records.
- **Algorithms**:
  - Decision Tree
  - Logistic Regression
  - Naive Bayes
  - Support Vector Machine (SVM)
  - Linear Regression
- **Tools**:
  - Python
  - Libraries: NumPy, Pandas, Matplotlib, Scikit-learn

---

## 🛠 System Requirements
**Hardware**:
- Processor: Intel Octa Core i7 (64-bit OS)
- Memory: 8 GB RAM

**Software**:
- Windows 10
- Python with:
  - Anaconda Navigator
  - Jupyter Notebook

---

## 💻 Results
- **Training Phase**:
  - Decision Tree achieved **100% accuracy**.
  - SVM achieved **85.9% accuracy**.
- **Testing Phase**:
  - Decision Tree achieved **87.5% accuracy**, making it the best-performing model.
- **Prediction**:
  - Successfully identified and classified network packets, achieving robust results.

---

## 🌟 Future Enhancements
- Improve accuracy for underperforming attack categories like DOS and worms.
- Incorporate feature selection techniques to reduce computational complexity.
- Extend the system to handle real-time network traffic for live intrusion detection.

---

## 📚 References
- UNSW-NB15 Dataset: [Dataset Link](https://www.unsw.adfa.edu.au/unsw-canberra-cyber/cybersecurity/ADFA-NB15-Datasets/)
- Research Papers and Sources:
  - [Intrusion Detection Using Machine Learning](https://doi.org/10.1186/s40537-018-0145-4)
  - [Towards Data Science Article](https://towardsdatascience.com/building-an-intrusion-detection-system-using-deep-learning-b9488332b321)

---

## 🤝 Acknowledgments
We would like to thank:
- **Dr. N. Rajasekhar** (Project Guide) for his guidance and support.
- The **Gokaraju Rangaraju Institute of Engineering and Technology** for providing the resources and platform for this project.

---

## 📧 Contact
**Venkata Anirudh Parakala**  
Email: [anirudhparakala@gmail.com](mailto:anirudhparakala@gmail.com)

---

