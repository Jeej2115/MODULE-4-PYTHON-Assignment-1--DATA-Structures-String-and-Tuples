# MODULE-4-PYTHON-Assignment-1--DATA-Structures-String-and-Tuples
This assignment focuses on understanding Python string operations and tuple manipulation, including concatenation, slicing, built-in methods, and tuple operations.

# Python String Operations and Tuple Manipulation

## 📌 Project Overview

This assignment focuses on understanding and applying **Python string operations and tuple manipulation**. The exercises provide practical experience with string concatenation, indexing, slicing, built-in string methods, and fundamental tuple operations.

The objective is to build a strong foundation in Python data structures and understand how strings and tuples can be created, accessed, modified, and processed.

---

## 🎯 Objectives

The main objectives of this assignment are:

* Understand the basics of **Python strings**.
* Perform **string concatenation**.
* Access individual characters using **indexing**.
* Extract portions of strings using **slicing**.
* Reverse strings using slicing.
* Use built-in **string methods** such as `upper()`, `lower()`, `capitalize()`, `count()`, and `replace()`.
* Create and work with **tuples**.
* Concatenate and repeat tuples.
* Access tuple elements using indexing.
* Extract elements from tuples using slicing.

---

## 🛠️ Technologies Used

* **Python 3**
* **Jupyter Notebook / JupyterLab**

---

## 📂 Assignment Topics

### 1. String Concatenation

The assignment demonstrates how to:

* Create strings.
* Take string input from the user.
* Concatenate two or more strings.
* Add additional text to an existing string.

Example:

```python
string1 = "Hello"
name = input("Enter your Name: ")

result = string1 + " " + name
print(result)
```

Sample output:

```text
Enter your Name: Zara
Hello Zara
```

---

### 2. String Indexing and Slicing

String indexing and slicing are used to access specific characters or portions of a string.

The following operations are performed:

* Print the first character.
* Print the last character.
* Print the first five characters.
* Print the last eleven characters.
* Reverse the complete string.
* Extract the word **"Python"** using slicing.

Example:

```python
existing_string[0]
existing_string[-1]
existing_string[:5]
existing_string[-11:]
existing_string[::-1]
```

---

### 3. String Methods

The assignment demonstrates commonly used Python string methods using:

```python
strM = "Python beginner tutorial."
```

The following methods are used:

| Method         | Purpose                               |
| -------------- | ------------------------------------- |
| `upper()`      | Converts the string to uppercase      |
| `lower()`      | Converts the string to lowercase      |
| `capitalize()` | Capitalizes the first character       |
| `count()`      | Counts occurrences of a character     |
| `replace()`    | Replaces specified text with new text |

Example:

```python
print(strM.upper())
print(strM.lower())
print(strM.capitalize())
print(strM.count('t'))
print(strM.replace("Python", "Data Analytics"))
```

---

### 4. Tuples

The assignment also covers basic tuple operations.

Two tuples are created:

```python
t1 = (10, 20, 30)
t2 = (40, 50, 60)
```

The following operations are performed:

* Concatenate two tuples.
* Repeat a tuple three times.
* Access the third element.
* Access the first three elements.
* Access the last three elements.

Example:

```python
t_combine = t1 + t2
print(t_combine)

t_repeat = t_combine * 3
print(t_repeat)

print(t_combine[2])
print(t_combine[:3])
print(t_combine[-3:])
```

---

## 📊 Key Concepts Learned

Through this assignment, the following Python concepts were practiced:

* Variables
* User input
* Strings
* String concatenation
* String indexing
* String slicing
* String reversal
* Built-in string methods
* Tuples
* Tuple concatenation
* Tuple repetition
* Tuple indexing
* Tuple slicing

---

## 💡 Connection to Future Python Work

The skills developed in this assignment will be useful in future Python programming and **data analysis** projects. String operations are important for cleaning, formatting, searching, and transforming text data. Tuples are useful for storing fixed collections of values and are commonly encountered when working with structured data.

These concepts provide a foundation for more advanced Python topics such as:

* Lists
* Dictionaries
* Functions
* File handling
* Exception handling
* Pandas
* NumPy
* Data cleaning and preprocessing
* Data analysis

---

## 📝 Conclusion

This assignment provided a practical understanding of **Python string operations and tuple manipulation**. Through string concatenation, indexing, slicing, and built-in string methods, I learned how to create, modify, access, and process string data efficiently.

The tuple exercises helped me understand tuple creation, concatenation, repetition, indexing, and slicing. Overall, these exercises strengthened my understanding of Python data structures and provided a foundation for working with data effectively in Python.

---

## 👩‍💻 Author

**Pison Jaya Elbinah Balan**

---

## 📁 Project Structure

```text
Python-Strings-and-Tuples/
│
├── Python_String_Operations.ipynb
├── README.md
└── Outputs/
```

