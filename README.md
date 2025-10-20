# 🐍 Python Practice Projects - 11 Mini Projects

A collection of **11 simple, focused projects** to practice and remember Python concepts. Each project targets specific topics with clear examples and exercises.

Perfect for beginners and intermediate learners who want to solidify their Python fundamentals!

## 📚 What's Inside?

| # | Project | Topics Covered | Lines |
|---|---------|---------------|-------|
| 1 | **Text Formatter** | Variables, Strings, Dicts, f-strings | ~50 |
| 2 | **Number Analyzer** | For/While Loops, If/Elif/Else | ~60 |
| 3 | **Grade Calculator** | Functions, Lambda, Map/Filter | ~50 |
| 4 | **Data Transformer** | List/Dict/Set Comprehensions | ~45 |
| 5 | **Note Saver** | File I/O, JSON, Context Managers | ~60 |
| 6 | **Text Extractor** | Regex, Collections.Counter | ~55 |
| 7 | **Lottery Simulator** | Random Module, Choices/Sample | ~50 |
| 8 | **Safe Calculator** | Try/Except/Finally, Custom Exceptions | ~70 |
| 9 | **Simple Bank** | Classes, Methods, Static/Class Methods | ~65 |
| 10 | **Vehicle System** | Inheritance, Polymorphism, @property | ~70 |
| 11 | **Timing Decorator** | Decorators, @wraps, Decorator Factory | ~60 |


## 🚀 Quick Start

### Clone and Run
```bash
git clone https://github.com/yourusername/python-practice-projects.git
cd python-practice-projects
python practice_projects.py
```

### Run Individual Projects
```python
# Import and run specific project
from practice_projects import text_formatter_project

text_formatter_project()  # Run only this project
```

## 📖 How to Use

### 1️⃣ **Learn by Running**
Run all projects to see Python concepts in action:
```bash
python practice_projects.py
```

### 2️⃣ **Practice One Topic at a Time**
Focus on specific modules you want to improve:
```python
# Practice loops
number_analyzer_project()

# Practice OOP
simple_bank_project()
vehicle_system_project()
```

### 3️⃣ **Study and Modify**
- Read the code for each project
- Understand the patterns
- Try the exercises at the bottom
- Modify and experiment

## 🎯 Learning Path

### **Beginner** (Week 1-2)
- Project 1: Text Formatter
- Project 2: Number Analyzer
- Project 3: Grade Calculator
- Project 4: Data Transformer

### **Intermediate** (Week 3-4)
- Project 5: Note Saver
- Project 6: Text Extractor
- Project 7: Lottery Simulator
- Project 8: Safe Calculator

### **Advanced** (Week 5-6)
- Project 9: Simple Bank
- Project 10: Vehicle System
- Project 11: Timing Decorator
- Project 12: Data Streamer

## 💡 Key Features

- ✅ **Simple & Focused**: Each project is 30-70 lines
- ✅ **Real Examples**: Practical use cases, not just theory
- ✅ **Clear Comments**: Explains what you're practicing
- ✅ **Working Code**: All projects run without errors
- ✅ **Practice Exercises**: Additional challenges included
- ✅ **Quick Reference**: Syntax reminders at the end

## 📝 Practice Exercises

Each project includes practice exercises. For example:

**Text Formatter Exercises:**
- Add word counter function
- Create username generator
- Build text reverser

**Number Analyzer Exercises:**
- Find largest/smallest numbers
- Calculate median and mode
- Create prime number checker

*See the full list of exercises in the code comments!*

## 🏆 Mini Challenges

Combine multiple concepts:

1. **Contact Manager** - OOP + File I/O + Regex
2. **Expense Tracker** - OOP + Comprehensions + Collections
3. **Quiz Game** - Loops + Functions + Random
4. **Data Pipeline** - Generators + Decorators + Lambda
5. **Simple API Client** - Error Handling + JSON + Decorators

## 📚 Concepts Covered

- **Variables & Data Types**: strings, integers, floats, lists, dicts
- **Control Flow**: for/while loops, if/elif/else
- **Functions**: def, return, parameters, lambda, map/filter
- **Comprehensions**: list, dict, set comprehensions
- **File Operations**: reading/writing files, JSON
- **Text Processing**: regex patterns, string manipulation
- **Randomization**: random.choice, randint, shuffle
- **Error Handling**: try/except/finally, custom exceptions
- **OOP Basics**: classes, methods, attributes, __init__
- **Advanced OOP**: inheritance, polymorphism, @property, encapsulation
- **Decorators**: function decorators, @wraps, decorator factories
- **Generators**: yield, generator expressions, infinite sequences

## 🔖 Quick Reference

```python
# Strings
text.strip(), .upper(), .lower(), .title()
f"{variable}"

# Loops
for item in list:
while condition:

# Functions
def func(param):
lambda x: x * 2
map(func, list)
filter(func, list)

# Comprehensions
[x for x in list]
{k: v for k, v in dict.items()}
{x for x in list}

# File I/O
with open('file.txt', 'r') as f:
json.dump(data, f)
json.load(f)

# Regex
re.findall(pattern, text)
re.sub(pattern, replace, text)

# Random
random.choice(list)
random.randint(a, b)
random.shuffle(list)

# Error Handling
try:
    # code
except ErrorType:
    # handle
finally:
    # cleanup

# OOP
class MyClass:
    def __init__(self):
        self.attribute = value
    
    def method(self):
        return self.attribute

# Decorators
@decorator
def function():
    pass

# Generators
def generator():
    yield value
```

## 📂 Project Structure

```
python-practice-projects/
├── practice_projects.py    # Main file with all 12 projects
└── README.md              # This file
```

## 🤝 Contributing

Feel free to:
- Add more practice projects
- Improve existing examples
- Add more exercises
- Fix bugs or typos

**How to contribute:**
1. Fork the repository
2. Create your feature branch (`git checkout -b feature/new-project`)
3. Commit your changes (`git commit -m 'Add new project'`)
4. Push to the branch (`git push origin feature/new-project`)
5. Open a Pull Request

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 🙏 Acknowledgments

Created as a learning resource for Python beginners and intermediate learners.

## 📧 Contact

Questions or suggestions? Feel free to open an issue!

---

⭐ **If you find this helpful, please star the repository!** ⭐

Happy Coding! 🚀
