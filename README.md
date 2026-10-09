# Project: Modular & Packager

**Author:** Meera Kyada

---

## 📌 Project Overview

The **Modular & Packager** project is a Python-based menu-driven application developed to demonstrate the practical use of **Python modules, packages, built-in modules, and custom modules**.

The project combines different utilities such as date and time operations, mathematical calculations, random data generation, UUID generation, file operations, and module attribute exploration into a single application.

---

## 🎯 Project Objectives

- To understand Python modules and packages.
- To create and use custom modules.
- To use built-in Python modules.
- To perform date and time operations.
- To perform mathematical calculations.
- To generate random data.
- To generate unique identifiers using UUID.
- To perform file operations using a custom module.
- To explore module attributes using `dir()`.
- To understand `importlib`.
- To understand `__name__` and `__main__`.
- To develop a menu-driven Python application.

---

## 🛠️ Technologies Used

- **Programming Language:** Python
- **Python Version:** 3.14.6
- **IDE:** Visual Studio Code
- **Version Control:** Git
- **Code Hosting Platform:** GitHub
- **Interface:** Command Line / Terminal

### Python Modules Used

```python
datetime
time
math
random
uuid
importlib
```

### Custom Modules

```text
math_operations.py
file_operations.py
```

---

## 📁 Project Structure

```text
Modular_&_Packager/
│
├── Modules/
│   ├── __pycache__/
│   ├── __init__.py
│   ├── file_operations.py
│   └── math_operations.py
│
├── Modular_Packager.py
├── Output.png
├── README.md
└── sample.txt
```

### File Description

| File / Folder | Description |
|---|---|
| `Modules/` | Contains custom Python modules |
| `__init__.py` | Initializes the custom package |
| `file_operations.py` | Performs file operations |
| `math_operations.py` | Performs mathematical operations |
| `Modular_Packager.py` | Main menu-driven application |
| `sample.txt` | Sample file used for file operations |
| `output.png` | Project output screenshots |
| `README.md` | Project documentation |

---

## ✨ System Features

The application provides the following main features:

1. **Datetime and Time Operations**
2. **Mathematical Operations**
3. **Random Data Generation**
4. **Generate Unique Identifiers (UUID)**
5. **File Operations using Custom Module**
6. **Explore Module Attributes using `dir()`**
7. **Exit**

---

## 🕒 Datetime and Time Operations

The application provides:

- Current date and time
- Difference between two dates
- Custom date format
- Stopwatch
- Countdown timer

### Example

```text
Current Date and Time: 2026-10-06 20:30:49

Difference: 7376 days

Formatted Date: 25-05-2009

Elapsed Time: 21.92 seconds

Time's up!
```

The `datetime` and `time` modules are used for these operations.

---

## 🧮 Mathematical Operations

The Mathematical Operations section provides:

- Factorial
- Compound Interest
- Trigonometric Calculations
- Area of Geometric Shapes

### Factorial

```text
Enter a number: 7
Factorial: 5040
```

### Compound Interest

The program accepts principal amount, rate of interest, and time.

```text
Compound Interest: 1102.50
```

### Trigonometric Calculations

The program calculates:

```text
sin()
cos()
tan()
```

### Area of Geometric Shapes

The available shapes are:

```text
Circle
Rectangle
Triangle
```

The `math` module is used for mathematical calculations.

---

## 🎲 Random Data Generation

The application provides:

- Random Number
- Random List
- Random Password
- Random OTP
- Random Sampling

### Example

```text
Random Number: 58

Random List: [15, 28, 73, 84, 33]

Generated Password: Jyi^
```

The `random` module is used for generating random values.

---

## 🆔 UUID Generation

The application uses the `uuid` module to generate a unique identifier.

### Example

```text
Generated UUID:
f43234db-e231-449e-b903-f4cb8d7d1858
```

UUIDs can be used as unique identifiers for records, objects, or application data.

---

## 📂 File Operations – Custom Module

The custom `file_operations.py` module provides:

- Create a new file
- Write to a file
- Read from a file
- Append to a file

### Example

```text
Enter file name: sample.txt

File created successfully!

Data written successfully!

Data appended successfully!
```

This demonstrates basic Python file handling through a custom module.

---

## 🔍 Module Attributes using `dir()`

The application provides an option to explore module attributes dynamically.

Example:

```text
Enter module name to explore: math
```

The `dir()` function displays the available attributes and functions of the selected module.

Example attributes include:

```text
acos
asin
atan
ceil
cos
factorial
floor
log
pi
sin
sqrt
tan
```

---

## 🧩 Custom Modules & Package

### `__init__.py`

The `__init__.py` file initializes the custom `Modules` package.

### `math_operations.py`

This module contains mathematical operations such as:

- Factorial
- Compound Interest
- Trigonometry
- Area calculations

### `file_operations.py`

This module contains file operations such as:

- Create
- Write
- Read
- Append

### `importlib`

The project demonstrates dynamic module loading using `importlib`.

Example:

```python
import importlib

module = importlib.import_module("Modules.math_operations")
```

### `__name__` and `__main__`

The project demonstrates the use of:

```python
if __name__ == "__main__":
```

This allows the main program code to execute when the file is run directly.

---

## 📦 Project Deliverables

The project includes:

- Python source code
- Custom modules
- Custom package
- `__init__.py`
- Example output screenshots
- Sample text file
- Complete project documentation

### Deliverable Files

```text
Modular_Packager.py
Modules/
    __init__.py
    math_operations.py
    file_operations.py
sample.txt
output.png
README.md
```

---

## 💡 Example Use Case

The **Modular & Packager** toolkit can be used by students, developers, or general users who need multiple small utilities in one application.

For example, a user can:

- Calculate the difference between dates.
- Use a stopwatch or countdown.
- Perform mathematical calculations.
- Generate a random password or OTP.
- Generate a UUID.
- Create, read, write, and append files.
- Explore the attributes of a Python module.

All these operations can be accessed through one menu-driven application.

---

## 🌍 Real-World Applications

The concepts demonstrated in this project can be useful in:

### Date and Time Applications

- Scheduling systems
- Timers
- Date calculations
- Time-based applications

### Mathematical Applications

- Educational software
- Financial calculations
- Geometry applications
- Scientific calculations

### Random Data Applications

- Password generation
- OTP generation
- Random selection
- Testing and sample data

### UUID Applications

- Unique record identification
- Transactions
- Application objects
- Data identification

### File Handling Applications

- Storing information
- Reading saved data
- Updating text files
- Basic data management

### Modular Programming

Modules and packages help developers divide a large application into smaller, reusable, and maintainable components.

---

## 📊 Evaluation Criteria

| Criteria | Description |
|---|---|
| **Functionality** | Required utilities perform their intended operations. |
| **Code Structure** | The application is organized using a main file, custom modules, and a package. |
| **Documentation** | The project includes proper documentation and example outputs. |
| **Innovation** | Multiple useful utilities are combined into one menu-driven toolkit. |

---

## 🔄 Program Workflow

```text
Start
  ↓
Display Main Menu
  ↓
Select an Option
  ↓
Perform Operation
  ↓
Display Result
  ↓
Return to Main Menu
  ↓
Select Exit
  ↓
End
```

### Main Menu

```text
============================
Welcome to Multi-Utility Toolkit
============================

Choose an option:

1. Datetime and Time Operations
2. Mathematical Operations
3. Random Data Generation
4. Generate Unique Identifiers (UUID)
5. File Operations (Custom Module)
6. Explore Module Attributes (dir())
7. Exit
```

---

## ▶️ How to Run

### Step 1: Open the Project

Open the `Modular_&_Packager` folder in Visual Studio Code.

### Step 2: Open Terminal

Open the terminal in VS Code.

### Step 3: Run the Program

```bash
python Modular_Packager.py
```

### Step 4: Select an Option

Choose an option from the main menu and provide the required input.

---

## 📝 Assumptions

- Python 3.14.6 is installed.
- The project folder structure is maintained correctly.
- Custom modules are stored inside the `Modules` folder.
- `sample.txt` is used for file operations.
- The user provides valid input according to the displayed instructions.

---

## 🎓 Learning Outcomes

After completing this project, the following concepts are demonstrated:

- Python modules and packages
- Custom module creation
- Built-in Python modules
- `datetime` and `time`
- Mathematical calculations
- Random data generation
- UUID generation
- File handling
- `importlib`
- `dir()`
- `__name__`
- `__main__`
- Menu-driven programming
- Modular program organization

---

## 🚀 Future Enhancements

The project can be improved by adding:

- More mathematical utilities
- Additional date and time features
- More file management operations
- Better input validation
- Additional custom modules
- Graphical User Interface (GUI)

---

## 🖥️ Output Presentation

The output demonstrates the major features of the project, including:

- Date and Time Operations
- Mathematical Operations
- Random Data Generation
- UUID Generation
- File Operations
- Module Attribute Exploration

![Modular & Packager Output](/Output.png)

---

## 📌 Conclusion

The **Modular & Packager** project demonstrates the practical use of Python modules, packages, built-in libraries, custom modules, file handling, date and time operations, mathematical calculations, random data generation, UUID generation, `importlib`, and `dir()`.

By combining these utilities into one menu-driven application, the project demonstrates how modular programming can make Python applications more organized, reusable, and maintainable.

---

## 🙏 Thank You

**Thank you for reviewing the Modular & Packager project!**