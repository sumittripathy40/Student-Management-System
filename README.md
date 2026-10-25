# Student Management System

A menu-driven **Student Management System** written in Python. The program provides separate admin, teacher, and student flows for managing student and teacher records using local text files.

## ✨ Features

- **Admin menu:** add, search, display, update, and delete student and teacher records
- **Teacher menu:** search student information and perform permitted student-record operations
- **Student menu:** sign in and search student information
- Password creation flow for students and teachers with a basic password rule
- Validates student and teacher IDs against stored records before account setup
- Stores records in tab-separated text files

## 🧰 Built With

- **Python 3**
- Python standard library: `getpass` for password input

No external Python packages are required by the current script.

## 📂 Project Structure

```text
Student-Management-System/
├── student management system.py
├── README.md
└── student_data1.txt       # created/used by the program
    teacher_data1.txt       # created/used by the program
    student_pwd1.txt        # created/used by the program
    teacher_pwd1.txt        # created/used by the program
```

The data and password files are referenced by the program at runtime. Create or prepare them in the working directory before using flows that read from them.

## 🚀 Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/sumittripathy40/Student-Management-System.git
cd Student-Management-System
```

### 2. Check your Python version

Python 3 is recommended. Verify it is installed:

```bash
python --version
```

### 3. Run the program

```bash
python "student management system.py"
```

Follow the prompts in the terminal to navigate the main menu and the admin, teacher, or student options.

## 🗃️ Data Storage

The script uses local text files and tab-separated records:

- `student_data1.txt` — student IDs, names, grades, and five marks
- `teacher_data1.txt` — teacher IDs, names, grades, and subjects
- `student_pwd1.txt` — student login credentials
- `teacher_pwd1.txt` — teacher login credentials

Keep these files in the directory from which you run the script. The current implementation stores passwords in plain text, so it should be treated as a learning project only and **not used to store real user credentials or sensitive student information**.

## 👨‍💻 Author

**Sumit Tripathy**

- GitHub: [@sumittripathy40](https://github.com/sumittripathy40)
- Repository: [Student-Management-System](https://github.com/sumittripathy40/Student-Management-System)

## 📌 Future Improvements

- Store data in a database instead of local text files
- Hash passwords and improve authentication security
- Improve file handling and input validation
- Add automated tests and clearer separation between menus, business logic, and persistence
