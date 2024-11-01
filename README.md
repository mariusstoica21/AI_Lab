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
  
### Lab 2.2. - Debugging with arguments (Create new configuration), Autograder, DFS, BFS, Dijkstra
- 🌐 Berkeley Pacman Framework, Python 3: https://inst.eecs.berkeley.edu/~cs188/fa24/projects/proj1/
- ▶️ Depth First Search Algorithm: https://www.youtube.com/watch?v=iaBEKo5sM7w&t=83s
- ▶️ Breadth First Search Algorithm: https://www.youtube.com/watch?v=QRq6p9s8NVg&t=126s
- ▶️ Dijkstra's Algorithm - Computerphile: https://www.youtube.com/watch?v=GazC3A4OQTE

### Lab 3 - Informed search (A*)
- ▶️ A* (A Star) Search Algorithm - Computerphile: https://www.youtube.com/watch?v=ySN5Wnu88nE&t=27s

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
  
## 📂 Lab 2.1. - Install Ubuntu, PyCharm, Python 3.9 and Create New Project

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

<div align="center">
  <img 
    src="https://github.com/mariusstoica21/AI_Lab/blob/main/images/img6.jpeg"
    width="500"
    height="auto"
    alt="Img. 1 - Welcome to PyCharm"
  >
  <br>
  <em>Img. 1 - Welcome to PyCharm</em>
</div>
  
<div align="center">
  <img 
    src="https://github.com/mariusstoica21/AI_Lab/blob/main/images/img5.jpeg"
    width="500"
    height="auto"
    alt="Img. 2 - New Project Frame"
  >
  <br>
  <em>Img. 2 - New Project Frame</em>
</div>

<div align="center">
  <img 
    src="https://github.com/mariusstoica21/AI_Lab/blob/main/images/img7.jpeg"
    width="250"
    height="auto"
    alt="Img. 3 - Run pacman"
  >
  <br>
  <em>Img. 3 - Run pacman</em>
</div>

<div align="center">
  <img 
    src="https://github.com/mariusstoica21/AI_Lab/blob/main/images/img4.jpeg"
    width="400"
    height="auto"
    alt="Img. 4 - Pacman Game"
  >
  <br>
  <em>Img. 4 - Pacman Game</em>
</div>

## 📂 Lab 2.2. - Debugging with arguments (Create new configuration), Autograder, Depth First Search

### Debugging with arguments (Create new configuration)

1. In PyCharm IDE, go to the top menu, and click Run/Edit Configurations...

<div align="center">
  <img 
    src="https://github.com/mariusstoica21/AI_Lab/blob/main/images/img11.PNG"
    width="400"
    height="auto"
    alt="Img. 5 - Edit Configurations"
  >
  <br>
  <em>Img. 5 - Edit Configurations</em>
</div>

2. In the window 'Run/Debug Configurations', click the + button in the left pane, and select Python

<div align="center">
  <img 
    src="https://github.com/mariusstoica21/AI_Lab/blob/main/images/img13.PNG"
    width="200"
    height="auto"
    alt="Img. 6 - Create new configuration"
  >
  <br>
  <em>Img. 6 - Create new configuration</em>
</div>
  
3. Provide name, for example 'pacman tinyMaze search', provide script (pacman.py) and arguments '-l tinyMaze -p SearchAgent -a fn=tinyMazeSearch'

<div align="center">
  <img 
    src="https://github.com/mariusstoica21/AI_Lab/blob/main/images/img12.PNG"
    width="500"
    height="auto"
    alt="Img. 7 - Add configuration name, script and parameters"
  >
  <br>
  <em>Img. 7 - Add configuration name, script and parameters</em>
</div>

## 📂 Lab 3 - Informed search (A*)

A* uses the following concepts:
- **Heuristic**: distance from current node, to end node: (Manhattan Distance, Euclidean Distance)
  - Example: given the node P: (5,5) (Pacman Node) and the node G:(1,1) (Goal Node) the heuristic is: sqrt{(xP - xG)^2 + (yP - yG)^2}
- **Cost**: cost between nodes, as weights.  
- **Priority Queue**: add elements into Priority Queue based on the (Cost + Heuristic) value.
Homework: implement A* algorithm in the Pacman framework.
Tips & tricks:
- Each element in the Priority Queue will contain the following information:
  - **Current node**
  - **Cost**
  - **Cost + Heuristic**: in order to add elements to the queue in an informed way (taking into consideration the distance from the current node until the end node)
  - **Previous node**: in order to compute the path.
Example:


### Icons

<ul>
  <li><a href="https://www.flaticon.com/free-icons/artificial-intelligence" title="artificial intelligence icons">Artificial intelligence icons created by rukanicon - Flaticon</a></li>
</ul>
