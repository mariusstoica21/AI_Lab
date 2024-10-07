<p align="left">
  <img 
    src="https://github.com/mariusstoica21/AI_Lab/blob/main/images/header_1.png"
  >
</p>

## 🔗 Useful links

### Lab 1 - Python Introduction

- 🌐 Python Interview questions: https://www.geeksforgeeks.org/python-interview-questions/
- ▶️ Write Beautiful Code in Python: https://www.youtube.com/watch?v=OSGv2VnC0go&t=802s
- ▶️ Python OOP Tutorials: https://www.youtube.com/watch?v=ZDa-Z5JzLYM&list=PL-osiE80TeTsqhIuOqKhwlXsIBIdSeYtc

### Lab 2.1. - Install Ubuntu, PyCharm, Python 3.9 and Create New Project
- ▶️ Ubuntu Installation using Oracle VirtualBox: https://www.youtube.com/watch?v=hYaCCpvjsEY&t=185s
- ▶️ Debugging in PyCharm: https://www.youtube.com/watch?v=sRGpvbhOhQs
- 🌐 Pacman Framework, Python 3: https://inst.eecs.berkeley.edu/~cs188/fa24/assets/projects/search.zip
  
### Lab 2.2. - Debugging with arguments (Create new configuration), Autograder, Depth First Search
- 🌐 Berkeley Pacman Framework, Python 3: https://inst.eecs.berkeley.edu/~cs188/fa24/projects/proj1/
- ▶️ Depth First Search Algorithm: https://www.youtube.com/watch?v=iaBEKo5sM7w&t=83s
- ▶️ Breadth First Search Algorithm: https://www.youtube.com/watch?v=QRq6p9s8NVg&t=126s

## 📂 Lab 1 - Python Introduction

1. Python General Info
2. Python benefits
3. **Python - compiled or interpreted (Compilation process in C vs Python)**
4. **Comments in Python**
5. **List vs Tuple vs Set**
6. **Mutable and Immutable data types**
7. **Dictionary**
8. Arguments passed by value or reference
9. **List Comprehension (generate even numbers list, squares list)**
10. **Dictionary comprehension**
11. **Lambda functions**
12. Pass in Python
13. **Exceptions in Python**
14. Pass function as argument in Python
15. **Args and Kwargs in Python**
16. **Scope in Python**
17. **Break, continue, pass in Python**
18. **Built-in data types**
19. xrange vs range
20. **Shallow vs Deep copy**
21. **Iterators**
22. **Generators**
23. Inheritance, Abstraction, Polymorphism, Encapsulation
24. **Zip (Write Beautiful Code in Python)**
25. **GIL (Global Interpreter Lock, Concurrency in Python)**
26. **OOP: Classes and methods, Class variables, Decorators(class methods, static methods, abstract methods, getters and setters) Inheritance (Subclasses), Dunder methods**
  
## 📂 Lab 2 - Install Ubuntu, PyCharm, Python 3.9 and Create New Project

1. Download and install Oracle VirtualBox and install Ubuntu 22.04 LTS, by watching the tutorial https://www.youtube.com/watch?v=hYaCCpvjsEY&t=185s
2. Open Ubuntu VM
3. Install Python 3.9 in Ubuntu 22.04 VM
   - Open Terminal (CTRL + ATL + T) 
   - Run the following commands in order to install Python 3.9
     - sudo apt update
     - sudo apt upgrade
     - sudo add-apt-repository ppa:deadsnakes/ppa
     - sudo apt install python3.9
   - Check version:
     - python3 --version
   - Search for folder (will be needed when configuring interpreter):
     - which python3.9
5. Install PyCharm in Ubuntu 22.04 VM
   - Go to https://www.jetbrains.com/pycharm/download/?section=windows
   - Create folder PyCharm in Ubuntu 22.04 LTS
   - Download PyCharm Community Edition into the folder above
   - Extract the file (right-click and extract or by using the terminal)
   - Go to pycharm-community-2024.2.2/bin folder
   - Run the following command
     - ./pycharm.sh
6. Create new project in PyCharm
   - Open PyCharm
      - Go to pycharm-community-2024.2.2/bin folder
      - Run the following command
        - ./pycharm.sh
   - Click the button 'New Project'
   - In the 'New Project' window, do the following steps:
      - Provide name: For example 'Pacman_Framework'
      - Provide location: For example '/home/username/Documents'
      - Provide interpreter: Insert path of the Python 3.9 interpreter
         - In order to get the interpreter path, open a terminal and write the following command
            - which python3.9
   - Download search.zip by opening from https://inst.eecs.berkeley.edu/~cs188/fa24/assets/projects/search.zip
   - Move search.zip file into PyCharm folder created above (Pacman_Framework for example)
   - Unzip search.zip
      - After unzipping, copy the content from 'search' folder directly into Pacman_Framework folder, and remove the search.zip file and search folder
   - Run file 'pacman.py' by right-clicking the file, and selecting 'Run pacman.py'
   - **If the following error occurs 'ModuleNotFoundError: No module named tkinter':**
     - Open the Terminal from the PyCharm IDE
     - Run the following command:
       - sudo apt install python3.9-tk
   - Run again the file 'pacman.py' by right-clicking the file, and selecting 'Run pacman.py'
   - Enjoy the game!

<p align="center">
  <img 
    src="https://github.com/mariusstoica21/AI_Lab/blob/main/images/img6.jpeg"
    width = "500"
    height = "auto"
  >
  <em>Img. 1 - Welcome to PyCharm</em>
</p>  
<p align="center">
  <img 
    src="https://github.com/mariusstoica21/AI_Lab/blob/main/images/img5.jpeg"
    width = "500"
    height = "auto"
  >
  <em>Img. 2 - New Project Frame</em>
</p>
  
<p align="center">
  <img 
    src="https://github.com/mariusstoica21/AI_Lab/blob/main/images/img7.jpeg"
    width = "250"
    height = "auto"
  >
  <em>Img. 3 - Run pacman</em>
</p>

<p align="center">
  <img 
    src="https://github.com/mariusstoica21/AI_Lab/blob/main/images/img4.jpeg"
    width = "400"
    height = "auto"
  >
  <em>Img. 4 - Pacman Game</em>
</p>

### Icons

<ul>
  <li><a href="https://www.flaticon.com/free-icons/artificial-intelligence" title="artificial intelligence icons">Artificial intelligence icons created by rukanicon - Flaticon</a></li>
</ul>
