# 🐍 Python Practice Repository

A comprehensive collection of Python exercises, practice problems, and implementations covering fundamental concepts, data structures, algorithms, object-oriented programming, and database operations.

## 📋 Repository Structure
```
python-practice/
│
├── 01_basics/
│ ├── 01_variables_and_datatypes.py
│ ├── 02_operators.py
│ ├── 03_control_flow.py
│ ├── 04_functions.py
│ ├── 05_lists.py
│ ├── 06_tuples.py
│ ├── 07_dictionaries.py
│ ├── 08_sets.py
│ ├── 09_strings.py
│ └── 10_comprehensions.py
│
├── 02_intermediate/
│ ├── 01_modules_and_packages/
│ ├── 02_file_handling/
│ ├── 03_error_exception_handling/
│ └── 04_lambda_map_filter_reduce/
│
├── 03_oop/
│ ├── 01_classes_objects.py
│ ├── 02_inheritance.py
│ ├── 03_polymorphism.py
│ ├── 04_encapsulation.py
│ ├── 05_abstraction.py
│ ├── 06_magic_methods.py
│ └── 07_property_decorators.py
│
├── 04_data_structures_algorithms/
│ ├── 01_arrays/
│ ├── 02_linked_lists/
│ ├── 03_stacks_queues/
│ ├── 04_trees/
│ ├── 05_graphs/
│ ├── 06_sorting_algorithms/
│ ├── 07_searching_algorithms/
│ └── 08_recursion/
│
├── 05_database/
│ ├── 01_sqlite/
│ │ ├── database_setup.py
│ │ ├── crud_operations.py
│ │ └── exercises/
│ ├── 02_mysql/
│ └── 03_postgresql/
│
├── 06_problem_solving/
│ ├── 01_easy/
│ ├── 02_medium/
│ └── 03_hard/
│
├── 07_projects/
│ ├── 01_calculator/
│ ├── 02_to_do_app/
│ ├── 03_library_management/
│ └── 04_student_management/
│
├── requirements.txt
├── .gitignore
└── README.md
```

## 🚀 Topics Covered

### 1. Python Basics
- Variables and Data Types
- Operators and Expressions
- Control Flow (if-else, loops)
- Functions and Arguments
- Data Structures:
  - Lists, Tuples, Dictionaries, Sets
  - String manipulation
- List/Dict/Set Comprehensions
- Input/Output operations

### 2. Intermediate Python
- Modules and Packages
- File Handling (read/write)
- Exception Handling
- Lambda Functions
- Map, Filter, Reduce
- Decorators and Generators
- Context Managers

### 3. Object-Oriented Programming (OOP)
- Classes and Objects
- Inheritance and Polymorphism
- Encapsulation and Abstraction
- Magic/Dunder Methods
- Class and Static Methods
- Property Decorators
- Method Overriding

### 4. Data Structures & Algorithms
- Arrays and Matrices
- Linked Lists (Singly, Doubly, Circular)
- Stacks and Queues
- Trees (Binary, BST, AVL)
- Graphs (DFS, BFS)
- Sorting (Bubble, Merge, Quick, Heap)
- Searching (Linear, Binary)
- Recursion and Backtracking
- Dynamic Programming

### 5. Database Operations
- **SQLite**: Setup, CRUD operations
- **MySQL**: Connection, Queries
- **PostgreSQL**: Advanced operations
- ORM basics (SQLAlchemy)
- Database design exercises

### 6. Problem Solving
- Easy Level: Basic programming challenges
- Medium Level: Intermediate algorithms
- Hard Level: Complex problem-solving
- Coding interview preparation

### 7. Mini Projects
- Calculator Application
- To-Do List Manager
- Library Management System
- Student Grade Manager
- Contact Book
- Weather App (API integration)

## 🛠️ Prerequisites

- Python 3.8 or higher
- pip (Python package installer)
- Git
- Basic understanding of programming concepts
- (Optional) MySQL/PostgreSQL for database exercises

## ⚙️ Installation & Setup

1. **Clone the repository**
```bash
git clone https://github.com/yourusername/python-practice.git
cd python-practice
```

2. **Create virtual environment**
```bash
# Windows
python -m venv venv
venv\Scripts\activate

# Mac/Linux
python3 -m venv venv
source venv/bin/activate
```

3. **Install dependencies**
```bash
pip install -r requirements.txt
```

4. **Start practicing!**
```bash
# Navigate to any section and run Python files
python 01_basics/01_variables_and_datatypes.py
```

## 📦 Dependencies
### Create a requirements.txt file with:
```bash
# Core dependencies
python-dotenv>=1.0.0
pytest>=7.0.0
black>=23.0.0

# Database dependencies
sqlite3  # Built-in
mysql-connector-python>=8.0.0
psycopg2-binary>=2.9.0
sqlalchemy>=2.0.0

# Optional - for data structures visualization
matplotlib>=3.5.0
numpy>=1.21.0

# Optional - for API projects
requests>=2.28.0
flask>=2.3.0
```

## 🎯 How to Use This Repository
- **Beginners**: Start with 01_basics/ and progress sequentially
- **Intermediate**: Jump to 02_intermediate/ or 03_oop/
- **Advanced**: Explore 04_data_structures_algorithms/
- **Practice**: Solve problems in 06_problem_solving/
- **Build**: Create projects in 07_projects/

## 📝 Practice Methodology
- Read the comments explaining concepts
- Run the example code
- Modify the code to experiment
- Solve the exercises provided in comments
- Create your own variations

## 🤝 Contributing
### Feel free to contribute by:
- Adding more exercises
- Improving solutions
- Fixing bugs
- Adding comments and documentation
- Creating new projects

### 📚 Additional Resources
- Official Python Documentation
- Python Package Index (PyPI)
- LeetCode for algorithm practice
- HackerRank Python challenges

## ⭐ Show Your Support
### If you find this repository helpful, please consider giving it a star! It helps others discover this resource.

## 🤩 Happy Coding! 🖥️
### 🚀 Remember: Consistency is key in mastering Python. Practice daily, even if it's just for 30 minutes.
