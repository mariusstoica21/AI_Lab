<p align="left">
  <img 
    src="https://github.com/mariusstoica21/AI_Lab/blob/main/images/header.png"
  >
</p>

## 🔗 Useful videos

### Lab 1 - Python Introduction

- 🌐 Python Interview questions: https://www.geeksforgeeks.org/python-interview-questions/
- ▶️ Write Beautiful Code in Python: https://www.youtube.com/watch?v=OSGv2VnC0go&t=802s
- ▶️ Python OOP Tutorials: https://www.youtube.com/watch?v=ZDa-Z5JzLYM&list=PL-osiE80TeTsqhIuOqKhwlXsIBIdSeYtc

### Lab 2 - Install Ubuntu, PyCharm, Python 2.7 and Create New Project
- ▶️ Ubuntu Installation using Oracle VirtualBox: https://www.youtube.com/watch?v=hYaCCpvjsEY&t=185s
- ▶️ Debugging in PyCharm: https://www.youtube.com/watch?v=sRGpvbhOhQs

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
10. **Lambda functions**
11. Pass in Python
12. **Exceptions in Python**
13. Pass function as argument in Python
14. *args and **kwargs in Python
15. **Scope in Python**
16. **Break, continue, pass in Python**
17. **Built-in data types**
18. xrange vs range
19. **Dictionary comprehension**
20. **Tuple comprehension**
21. **List vs Tuple**
22. **Shallow vs Deep copy**
23. **Iterators**
24. **Generators**
25. Inheritance, Abstraction, Polymorphism, Encapsulation
26. **Zip (Write Beautiful Code in Python)**
27. **GIL (Global Interpreter Lock, Concurrency in Python)**
28. **OOP: Classes and methods, Class variables, classmethods and staticmethods, Inheritance (Subclasses), Dunder methods, Decorators (getters and setters)**
  
## 📂 Lab 2 - Install Ubuntu, PyCharm, Python 2.7 and Create New Project

1. Download and install Oracle VirtualBox and install Ubuntu 22.04 LTS, by watching the tutorial https://www.youtube.com/watch?v=hYaCCpvjsEY&t=185s
2. Open Ubuntu VM
3. Install Python 2.7 in Ubuntu 22.04 VM
   - Open Terminal (CTRL + ATL + T) 
   - Run the following commands in order to install Python 2.7
     - sudo apt update
     - sudo apt upgrade
     - sudo apt install python2
     - sudo apt install python2.7 python2.7-dev
   - Check version:
     - python2 --version
   - Search for folder (will be needed when configuring interpreter):
     - which python2.7
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
      - Provide name: For example 'AI_Labs'
      - Provide location: For example '/home/username/Documents'
      - Provide interpreter: Insert path of the Python 2.7 interpreter
         - In order to get the interpreter path, open a terminal and write the following command
            - which python2.7
   - Download search.zip by opening from https://s3-us-west-2.amazonaws.com/cs188websitecontent/projects/release/search/v1/001/search.zip
   - Move search.zip file into PyCharm folder created above (AI_Labs for example)
   - Unzip search.zip
      - After unzipping, copy the content from 'search' folder directly into AI_Labs folder, and remove the search.zip file and search folder
   - Run file 'pacman.py' by right-clicking the file, and selecting 'Run pacman.py'
   - Enjoy the game!

<p align="center">
  <img 
    src="https://github.com/mariusstoica21/AI_Lab/blob/main/images/img1.jpeg"
    width = "500"
    height = "auto"
  >
  <em>Img. 1 - Welcome to PyCharm</em>
</p>  
<p align="center">
  <img 
    src="https://github.com/mariusstoica21/AI_Lab/blob/main/images/img2.jpeg"
    width = "500"
    height = "auto"
  >
  <em>Img. 2 - New Project Frame</em>
</p>
  
<p align="center">
  <img 
    src="https://github.com/mariusstoica21/AI_Lab/blob/main/images/img3.jpeg"
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
