# Support Vector Machine (SVM) with Streamlit - Disease Detection
### App Link
- https://support-vector-machine-disease-detection.streamlit.app/
---
### What is Support Vector Machine (SVM)?
- SVM is a **machine learning algorithm** that tries to **draw the best line or curve** to **separate two groups** of data.
- **Real-Life Example:** Imagine drawing a **line on the ground** to separate boys on one side and girls on the other. SVM does the same to **divide categories** using the best border.
- SVM is great when our data has a **clear boundary**. It can use **straight lines or curves** to separate groups.
---
### Required Python Packages
- **`scikit-learn`** - To build machine learning models
- **`streamlit`** - To build data apps
- **`pandas`** - To work with the dataset
---
### Example Problem
- Predict **Disease (Yes/No)** Based on **Temperature** and **Heart Rate**

| Temperature | Heart\_Rate | Disease |
| ----------- | ----------- | ------- |
| 98          | 72          | No      |
| 99          | 75          | No      |
| 101         | 90          | Yes     |
| 100         | 85          | Yes     |
| 97          | 70          | No      |

---
### How it Works
- SVM creates a **line (or curve)** that **separates groups**.
- It tries to make the **largest gap** between the line and data points.
- Used for **classification problems** like **Yes/No** or **A/B** types.
---
