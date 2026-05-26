# STUDENT-GRADE-ANALAYZER-

markdown
# 📊 Student Grade Analyzer

A simple Python-based project that analyzes student marks using **NumPy** and provides useful statistics such as total, average, highest, lowest marks, and grade evaluation.

---

## 📌 Overview
This project allows users to input marks of multiple students and performs basic data analysis using Python. It demonstrates the use of **NumPy arrays** for efficient numerical computation.

---

## 🚀 Features
- Input marks for multiple students  
- Calculate total marks  
- Calculate average marks  
- Find highest and lowest marks  
- Assign grades based on average performance  

---

## 🧠 Grading System

| Average Marks | Grade |
|--------------|------|
| ≥ 85         | A    |
| ≥ 70         | B    |
| ≥ 50         | C    |
| < 50         | Fail |

---

## 🛠️ Technologies Used
- Python  
- NumPy  

---

## 📂 Project Structure
```

Student_marks_analyzer.ipynb

````

---

## ▶️ How to Run

### 🔹 Run using Jupyter Notebook
1. Open terminal  
2. Run:
   bash
   jupyter notebook


3. Open the notebook file
4. Run all cells

---

### 🔹 Run using Python

1. Install NumPy:

   bash
   pip install numpy
   ```
2. Run the file:

   `bash
   python your_file_name.py
   



## 💻 Sample Output


Enter number of students: 3
Enter marks of student 1: 80
Enter marks of student 2: 90
Enter marks of student 3: 70

----- STUDENT MARKS ANALYSIS -----
Marks Entered: [80. 90. 70.]
Total Marks: 240.0
Average Marks: 80.0
Highest Marks: 90.0
Lowest Marks: 70.0
Grade: B



## ⚙️ How It Works

* Takes input from the user
* Stores marks in a list
* Converts list to NumPy array
* Uses NumPy functions:

  * `np.sum()` → Total
  * `np.mean()` → Average
  * `np.max()` → Highest
  * `np.min()` → Lowest
* Applies conditional logic for grading

---

## 🎯 Future Improvements

* Add student names
* Add subject-wise marks
* Export results to CSV
* Add graphs/visualization

---

## 👩‍💻 Author

**Bhavya Chopra**

---

## ⭐ Acknowledgement

If you found this project helpful, consider giving it a ⭐ on GitHub!




