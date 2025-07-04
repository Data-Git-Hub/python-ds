# P2: Employ Python Data Structures, Notebooks & Engage

[P2: Employ Python Data Structures, Notebooks & Engage](https://github.com/Data-Git-Hub/python-ds)

## Introduction
In this assignment, I apply foundational Python skills related to data structures and notebook-based workflows. Using Jupyter Notebooks in VS Code, I complete a series of exercises that demonstrate proficiency with lists, dictionaries, tuples, and sets, while also exploring functions and basic control flow. The project emphasizes clear documentation using Markdown, code execution, and exporting work to HTML, reinforcing best practices for reproducibility and communication in data analytics. <br>

## Windows Setup Instructions

Open a PowerShell terminal in VS Code. 
Create local project virtual environment, activate it, and install packages. 
When asked to use the new .venv click yes. 

Important: Install from requirements first with scikit-learn commented out. 
Then remove the leading hashmark (around line 187) and re-run the command to install scikit-learn.
See requirements.txt for more information. 


```shell
py -m venv .venv
.\.venv\Scripts\activate
py -m pip install --upgrade pip setuptools wheel
py -m pip install -r requirements.txt
```
### Remove "#" TBD. from requirements.txt

```shell
py -m pip install -r requirements.txt
```

---

## macOS/Linux Setup Instructions

Open a default terminal in VS Code. 
Create local project virtual environment, activate it, and install packages. 
Important: Install from requirements first with scikit-learn commented out. 
Then remove the leading hashmark (around line 187) and re-run the command to install scikit-learn.
See requirements.txt for more information. 

```zsh
python3 -m venv .venv
source .venv/bin/activate
python3 -m pip install --upgrade pip setuptools wheel
python3 -m pip install -r requirements.txt
```

### Remove "#" TBD. from requirements.txt

```zsh
py -m pip install -r requirements.txt
```

---

## Tell VS Code to use .venv

Open the Command Palette: Press Ctrl + Shift + P (Windows) or Cmd + Shift + P (Mac/Linux)
Then type: Python: Select Interpreter
Press Enter.

Look for the interpreter with .venv in the path.
Click on that interpreter to select it.
Confirm it's selected: You should see the Python version and .venv path in the lower-left status bar of VS Code.

---

## Working on the Project

Open the .ipynb Jupyter notebook file in VS Code. 
Run the entire notebook before you start to edit. 
As you make progress, use Git to add, commit, and push your work to your GitHub repo.

```shell
git add .
git commit -m "describe the change here"
git push -u origin main
```

---

### Introduction

### Tasks

### Section 1. Modify markdown cells.

### Section 2. Python syntax `print()`, division operator `(/)`, and variable assignment. 

### Section 3. Python coding usage of `for` loops, multiplications, and `if` conditionals. Display factorial integers from 1 to 10 using `print()` and variable assignment.

### Section 4. Python `function`, use an `iterable` like a `list`, and apply `sum()` and `len()` to compute and return the average.

### Section 5. Calculating the statistical `variance` of a list. It applies the mean, element-wise subtraction, squaring, and aggregation using `list comprehension` or functional tools like `map()` or `filter()` to efficiently compute the result.

### Section 6. Python `list slicing` techniques to access and manipulate subsets of list data, including specifying start and stop indices, and using `stride` values to extract patterns such as every second or third element, or to reverse a list.

### Section 7. Printing a Python `dictionary` that uses key-value pairs to represent structured data, including `strings`, `integers`, and `lists`.

### Section 8. Using Python, specifically retrieving a value from a nested `dictionary` where the target is a `list` stored under a specific key.

### Section 9. Use a Python `set` to identify and count `unique` elements in a list. It highlights the efficiency of sets for deduplication and reinforces basic data structure operations like `len()` and `print()`.

### Section 10. This task combines `looping` logic and `string manipulation` to create a visual pattern using `*` characters. It practices nested or coordinated `for` loops and string operations like `*` (repetition) and concatenation to produce symmetrical console output.

---

## Python Data Structures and Notebooks

Complete the tasks in the Python Notebook in this repository.
To be submitted for credit, all changes must be committed and pushed to this repository (do not create your own repository unless instructed to on the course website).

## Rubric

Each question is worth one point.

---

## Authors

Contributors names and contact info <br>
@github.com/Data-Git-Hub <br>

---

## Version History
- P2 Sect - 8.0 - Modify Section 8. python-ds.ipynb, README.md
- P2 Sect - 7.0 - Modify Section 7. python-ds.ipynb, README.md
- P2 Sect - 6.0 - Modify Section 6. python-ds.ipynb, README.md 
- P2 Sect - 5.0 - Modify Section 5. python-ds.ipynb, README.md 
- P2 Sect - 4.0 - Modify Section 4. python-ds.ipynb, README.md
- P2 Sect - 3.0 - Modify Section 3. python-ds.ipynb, README.md
- P2 Sect - 2.0 - Modify Section 2. python-ds.ipynb, README.md
- P2 Init - 0.0 - Modify python-ds.ipynb, README.md 
## Test History 