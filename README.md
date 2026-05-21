````markdown id="0ecj7n"
# 🎓 Student Result Management System

## 📌 Project Overview

The **Student Result Management System** is a simple Python-based console application used to manage student academic records.  
This project allows users to:

- ✅ Add student details
- ✅ Calculate total marks and percentage
- ✅ Assign grades automatically
- ✅ View all student records
- ✅ Delete student records using roll number

The project is created using basic Python concepts such as:

- Lists
- Dictionaries
- Loops
- Conditional Statements
- User Input Handling

---

# 🚀 Features

✅ Add Student Details  
✅ Calculate Total Marks  
✅ Calculate Percentage  
✅ Automatic Grade Generation  
✅ View All Student Records  
✅ Delete Student Records  
✅ Menu Driven Program  

---

# 🛠️ Technologies Used

- **Python 3**
- **VS Code**

---

# 📂 Project Structure

```bash
Student-Result-Management-System/
│── student_result.py
│── README.md
```

---

# ⚙️ Steps to Create the Project

## 1️⃣ Initialize an Empty List

A list named `students` is created to store all student records.

```python
students = []
```

---

## 2️⃣ Create Menu-Driven Program

A `while` loop is used to repeatedly display options to the user.

```python
while True:
```

### Menu Options:
- Add Student
- View Students
- Delete Student
- Exit

---

## 3️⃣ Add Student Details

The user enters:

- Student Name
- Roll Number
- 6 Subject Marks

```python
name = input("Enter name: ")
rollno = input("Enter Roll no: ")
```

---

## 4️⃣ Calculate Total and Percentage

```python
total = marks1 + marks2 + marks3 + marks4 + marks5 + marks6
percentage = total / 6
```

---

## 5️⃣ Generate Grade Automatically

```python
if percentage > 80:
    grade = "A"
elif percentage > 50:
    grade = "B"
else:
    grade = "C"
```

---

## 6️⃣ Store Data Using Dictionary

```python
students.append({
    "name": name,
    "roll": rollno,
    "total": total,
    "percentage": percentage,
    "grade": grade
})
```

---

## 7️⃣ View Student Records

All student details are displayed using a loop.

```python
for s in students:
    print(s)
```

---

## 8️⃣ Delete Student Record

Students can be deleted using roll number.

```python
if s["roll"] == r:
    students.remove(s)
```

---

# ▶️ How to Run the Project in VS Code

## Step 1️⃣ Install Python
Download and install **Python 3** on your system.

---

## Step 2️⃣ Install VS Code
Download and install **Visual Studio Code (VS Code)**.

---

## Step 3️⃣ Install Python Extension
Open VS Code and install the **Python Extension** from the Extensions section.

---

## Step 4️⃣ Create Project Folder
Create a folder named:

```bash
Student-Result-Management-System
```

---

## Step 5️⃣ Create Python File
Inside the folder, create a file named:

```bash
student_result.py
```

Copy and paste the project code into this file.

---

## Step 6️⃣ Open Folder in VS Code
Open the project folder in VS Code using:

```bash
File → Open Folder
```

---

## Step 7️⃣ Run the Program
Click on the **Run ▶️** button in VS Code  
or open terminal and run:

```bash
python student_result.py
```

---

## Step 8️⃣ Use the Menu
After running the program, the following menu will appear:

```bash
1. Add Student
2. View Students
3. Delete Student
4. Exit
```

Enter the required option number to perform operations.

---

# 📸 Sample Output

```bash
1. Add Student
2. View Students
3. Delete Student
4. Exit

Enter choice: 1

Enter name: Rahul
Enter Roll no: 101
Enter marks1: 80
Enter marks2: 75
Enter marks3: 90
Enter marks4: 85
Enter marks5: 70
Enter marks6: 88

Student added!
```

---

# 🔮 Future Improvements

✅ Add File Handling for Permanent Data Storage  
✅ Add Database Connectivity (MySQL)  
✅ Create GUI using Tkinter  
✅ Add Search Student Feature  
✅ Add Update Student Details Option  
✅ Generate Report Cards Automatically  
✅ Add Login Authentication System  
✅ Export Results to Excel/PDF  



ndly Python application that helps understand how real-world student management systems work using core programming concepts.
````
