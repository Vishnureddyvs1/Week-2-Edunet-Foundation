# Week-2-Edunet-Foundation
Week-2 Edunet Founadtion
Here's an extraordinary, detailed `README.md` for your **Week 2 – Crop Prediction Project**. This version is professional, clear, and gives a strong impression to evaluators:

🌾 Week 2 – Crop Prediction using Machine Learning

Welcome to **Week 2** of the Crop Fertilizer Recommendation System project! In this phase, we focused on understanding the dataset and preparing it for model training using fundamental machine learning practices.

---

 📁 Project Structure

* `Crop_Prediction.ipynb` → Jupyter Notebook containing:

  * Dataset loading
  * Data exploration
  * Feature-label separation
  * Train-test splitting

* `Crop_recommendation.csv` → Dataset with 2200 crop records and 7 features:

  * **Features:** N, P, K, Temperature, Humidity, pH, Rainfall
  * **Target:** `crop_no` (crop label)

---

🔍 What’s Implemented in Week 2

| Step | Task                                                                                 |
| ---- | ------------------------------------------------------------------------------------ |
| ✅    | Loaded the CSV dataset using `pandas`                                                |
| ✅    | Printed the shape of feature matrix `X` and label vector `Y`                         |
| ✅    | Split the data into training and testing sets (80-20 ratio) using `train_test_split` |
| ✅    | Verified the shapes of training and test sets                                        |

---
 🧪 Output Shapes from the Notebook

```python
The shape of x is : (2200, 7)
The shape of y is : (2200,)
Shape of x_train: (1760, 7)
Shape of y_train: (1760,)
Shape of x_test: (440, 7)
Shape of y_test: (440,)
```
🛠️ Technologies Used

* Python 3
* Jupyter Notebook
* Pandas
* Scikit-learn

 📌 How to Reproduce

1. Clone or download this repository.
2. Open `Crop_Prediction.ipynb` in Jupyter Notebook.
3. Make sure `Crop_recommendation.csv` is in the same directory.
4. Run all cells sequentially.

🧠 Learnings from Week 2

* How to handle CSV data using `pandas`
* Importance of feature-target split in supervised ML
* Dataset splitting for evaluation
* Using Scikit-learn’s `train_test_split` effectively

📤 Submission

✅ Uploaded `Crop_Prediction.ipynb` in this repository
✅ Shared GitHub file link in LMS under **Week 2 Submission**
✅ Described the implementation in the LMS submission box

 📎 Useful References

* [Scikit-learn Docs - train\_test\_split](https://scikit-learn.org/stable/modules/generated/sklearn.model_selection.train_test_split.html)
* [Pandas Documentation](https://pandas.pydata.org/docs/)
* [Machine Learning Crash Course by Google](https://developers.google.com/machine-learning/crash-course)

👨‍💻 Author

Vishnu Reddy
B.Tech CSE (Cybersecurity)
Aspiring Python Developer | Passionate about ML & Cybersecurity

