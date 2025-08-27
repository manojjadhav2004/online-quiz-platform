
# 📝 Online Quiz in Python

This is a small **quiz game in Python** that I built in my 1st year of college.  
It runs in the terminal and asks you quiz questions from different subjects.  
You can pick a subject (Python, FDS, or C language), choose a difficulty level (Easy, Medium, Hard), and then answer the questions.

At the end, it shows how many you got right, wrong, and your final score.
            
---

## 🔥 Features
- Choose subject: **Python, FDS, C Language**
- Choose difficulty: **Easy, Medium, Hard**
- Shows **correct/incorrect answers**
- **Score system** (10 points per correct answer)
- Option to give feedback at the end

---

## ⚙️ What you need
- Python 3 installed  
- `pandas` and `openpyxl` libraries  
- An Excel file (`PythonDatabase.xlsx`) that has the questions  

Install the libraries with:
```bash
pip install pandas openpyxl
````

---

## ▶️ How to Run

1. Clone this project:

   ```bash
   git clone https://github.com/<your-username>/online-quiz.git
   cd online-quiz
   ```

2. Make sure the Excel file (`PythonDatabase.xlsx`) is in the same folder as `quiz.py`.

3. Run the program:

   ```bash
   python quiz.py
   ```

---

## 📊 Excel File Setup

The Excel file should have different sheets:

* `PYTHON-EASY`, `PYTHON-MEDIUM`, `PYTHON-HARD`
* `FDS-EASY`, `FDS-MEDIUM`, `FDS-HARD`
* `C-EASY`, `C-MEDIUM`, `C-HARD`

Each sheet should look like this:

| Sr.No. | Question                 | A      | B        | C      | D        | Answer |
| ------ | ------------------------ | ------ | -------- | ------ | -------- | ------ |
| 1      | What is Python?          | Snake  | Language | Coffee | Compiler | B      |
| 2      | Who invented C language? | Dennis | Guido    | James  | Bjarne   | A      |

---

## 🎮 Example

```
WELCOME TO ONLINE QUIZ
Choose the subject for quiz
1. PYTHON
2. FDS
3. C Language
Enter your choice: 1

Choose level of QUESTIONS
1. EASY
2. MEDIUM
3. HARD
Enter your choice: 1
how many questions do you want to solve: 2

1. What is Python?
    A Snake
    B Language
    C Coffee
    D Compiler
Enter your answer: B
Correct!

YOUR SCORE IS 10/100
```

---

## 🚀 Future Ideas

* Make a GUI version (with Tkinter or PyQt)
* Store scores and feedback in a database
* Shuffle questions each time

---

## 📜 License

Open-source project under the **MIT License**.

```

---

Want me to also **clean up your code a little** (remove hardcoded file paths, add better error handling) so you can just drop it in GitHub and it works smoothly?
```
