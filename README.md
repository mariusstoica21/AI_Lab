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

### Lab 5 - Wumpus World (Simple example)
- ▶️ Wumpus world lecture in Artificial intelligence: https://www.youtube.com/watch?v=R32KPiOBBxg

### Lab 7 - First Order Logic
- ▶️ Represent Facts or Knowledge using Predicate Logic in AI by Mahesh Huddar: https://www.youtube.com/watch?v=tFYngFwDuJQ
- ▶️ Was Marcus loyal to Ceasar? Did Marcus hate Ceasar? using Predicate Logic in AI by Mahesh Huddar: https://www.youtube.com/watch?v=Z0vTGofo2n8&t=225s

### Lab 8 - Inference in First Order Logic
- ▶️ Resolution (Part 1) - Resolution to Prove Predicate Facts to First Order Logic FOL Artificial Intelligence Mahesh Huddar: https://www.youtube.com/watch?v=CbI-Q2a5rUU&t=300s
- ▶️ Resolution (Part 2) - Conversion of First Order Logic FOL to CNF Prove Predicate using Resolution Tree Mahesh Huddar: https://www.youtube.com/watch?v=7g6cB3kIHJI
- ▶️ Skolemization : https://www.youtube.com/watch?v=vRSVeINP4h8&t=84s

### Lab 9 - Constraint satisfaction problems
- ▶️ Constraint Satisfaction: the AC-3 algorithm: https://www.youtube.com/watch?v=4cCS8rrYT14&t=240s
- ▶️ Lecture 16 | CSP 6: Stochastic Local Search : https://www.youtube.com/watch?v=E0l8xIXYSY4&t=967s
- ▶️ CryptArithmetic Problem in Artificial Intelligence | SEND + MORE = MONEY Solution | Pratiksha Jain: https://www.youtube.com/watch?v=jWvWOUb0hOI


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
    alt="Img. 2.1. - Welcome to PyCharm"
  >
  <br>
  <em>Img. 2.1. - Welcome to PyCharm</em>
</div>
  
<div align="center">
  <img 
    src="https://github.com/mariusstoica21/AI_Lab/blob/main/images/img5.jpeg"
    width="500"
    height="auto"
    alt="Img. 2.2. - New Project Frame"
  >
  <br>
  <em>Img. 2.2. - New Project Frame</em>
</div>

<div align="center">
  <img 
    src="https://github.com/mariusstoica21/AI_Lab/blob/main/images/img7.jpeg"
    width="250"
    height="auto"
    alt="Img. 2.3. - Run pacman"
  >
  <br>
  <em>Img. 2.3. - Run pacman</em>
</div>

<div align="center">
  <img 
    src="https://github.com/mariusstoica21/AI_Lab/blob/main/images/img4.jpeg"
    width="400"
    height="auto"
    alt="Img. 2.4. - Pacman Game"
  >
  <br>
  <em>Img. 2.4. - Pacman Game</em>
</div>

## 📂 Lab 2.2. - Debugging with arguments (Create new configuration), Autograder, Depth First Search

### Debugging with arguments (Create new configuration)

1. In PyCharm IDE, go to the top menu, and click Run/Edit Configurations...

<div align="center">
  <img 
    src="https://github.com/mariusstoica21/AI_Lab/blob/main/images/img11.PNG"
    width="400"
    height="auto"
    alt="Img. 2.5. - Edit Configurations"
  >
  <br>
  <em>Img. 2.5. - Edit Configurations</em>
</div>

2. In the window 'Run/Debug Configurations', click the + button in the left pane, and select Python

<div align="center">
  <img 
    src="https://github.com/mariusstoica21/AI_Lab/blob/main/images/img13.PNG"
    width="200"
    height="auto"
    alt="Img. 2.6. - Create new configuration"
  >
  <br>
  <em>Img. 2.6. - Create new configuration</em>
</div>
  
3. Provide name, for example 'pacman tinyMaze search', provide script (pacman.py) and arguments '-l tinyMaze -p SearchAgent -a fn=tinyMazeSearch'

<div align="center">
  <img 
    src="https://github.com/mariusstoica21/AI_Lab/blob/main/images/img12.PNG"
    width="500"
    height="auto"
    alt="Img. 2.7. - Add configuration name, script and parameters"
  >
  <br>
  <em>Img. 2.7. - Add configuration name, script and parameters</em>
</div>

## 📂 Lab 3 - Informed search (A*)

A* uses the following concepts:
- **Heuristic**: distance from current node, to end node: (Manhattan Distance, Euclidean Distance)
  - Example: given the node P: (5,5) (Pacman Node) and the node G:(1,1) (Goal Node) the heuristic (Euclidean distance) is:
<p align="center">
  d(P, G) = √( (xP - xG)² + (yP - yG)²)
</p>

- **Cost**: cost between nodes, as weights.  
- **Priority Queue**: add elements into Priority Queue based on the (Cost + Heuristic) value.
Homework: implement A* algorithm in the Pacman framework.

Tips & tricks:
- Each element in the Priority Queue will contain the following information:
  - **Current node**
  - **Cost**
  - **Cost + Heuristic**: in order to add elements to the queue in an informed way (taking into consideration the distance from the current node until the end node)
  - **Previous node**: in order to compute the path.

For more implementation details, please watch the following video: https://www.youtube.com/watch?v=ySN5Wnu88nE&t=27s

## 📂 Lab 5 - Propositional logic

## 📂 Lab 5.1. - Install Prover9 and Mace4

1. Download https://www.cs.unm.edu/~mccune/mace4/download/LADR-2009-11A.tar.gz (it has downloaded LADR-2009-11A.tar.gz)
2. Go to /Home/Documents and create folder 'Prover9' (you can name it as you wish, and can choose the desired location)
3. Place the LADR-2009-11A.tar.gz file into /Home/Documents/Prover9 folder
4. Unzip the LADR-2009-11A.tar.gz file (Right click on file -> Extract here)
5. Go into the LADR-2009-11A folder -> Right click -> Open in terminal
6. Write the following command: make all
7. After writing the command, the following error will show up:
<div align="center">
  <img 
    src="https://github.com/mariusstoica21/AI_Lab/blob/main/images/img14.jpeg"
    width="500"
    height="auto"
    alt="Img. 5.1. - Error Prover9"
  >
  <br>
  <em>Img. 5.1. - Error Prover9</em>
</div>

8. In order to resolve the error, go to provers.src folder and open 'Makefile' with text editor
9. In lines 66,69,72,75,78,81,84 place the '-lm' parameter at the end of the line and save the file

<div align="center">
  <img 
    src="https://github.com/mariusstoica21/AI_Lab/blob/main/images/img15.jpeg"
    width="500"
    height="auto"
    alt="Img. 5.2. - Move the -lm parameter at the end of the line"
  >
  <br>
  <em>Img. 5.2. - Move the '-lm' parameter at the end of the line</em>
</div>

10. Redo steps 5 and 6 (Go into the LADR-2009-11A folder -> Right click -> Open in terminal and write the following command: make all)
11. If the following message is displayed, **you have succesfully installed Prover9 and Mace4**.

<div align="center">
  <img 
    src="https://github.com/mariusstoica21/AI_Lab/blob/main/images/img16.jpeg"
    width="500"
    height="auto"
    alt="Img. 5.3. - Message displayed if installation is successfull"
  >
  <br>
  <em>Img. 5.3. - Message displayed if installation is successfull</em>
</div>

## 📂 Lab 5.2. - Run files in Prover9

1. Go to Home/Documents/Prover9 and open /bin folder
2. Right click -> Open in Terminal
3. Run the following command 'gedit socrates.in'
4. Copy the content from https://github.com/mariusstoica21/AI_Lab/blob/main/files/lab6/socrates.in into the socrates.in file and save it
6. Run the following command './prover9 -f socrates.in' from 'Home/Documents/Prover9/bin'
7. The following message should be displayed:

<div align="center">
  <img 
    src="https://github.com/mariusstoica21/AI_Lab/blob/main/images/img17.jpeg"
    width="500"
    height="auto"
    alt="Img. 5.4. - Theorem proved"
  >
  <br>
  <em>Img. 5.4. - Theorem proved</em>
</div>

## 📂 Lab 5.3. - Propositional logic rules

<div align="center">
  <img 
    src="https://github.com/mariusstoica21/AI_Lab/blob/main/images/img18.jpeg"
    width="500"
    height="auto"
    alt="Img. 5.5. - Propositional logic main rules"
  >
  <br>
  <em>Img. 5.5. - Propositional logic main rules</em>
</div>

## 📂 Lab 5.4. - Propositional logic examples


**1. Modus Ponnes**

- Download the file https://github.com/mariusstoica21/AI_Lab/blob/main/files/lab6/modus_ponens.in
- Place the file into Home/Documents/Prover9/bin folder
- Open terminal in the path
- Run the command: ./prover9 -f modus_ponens.in
- Verify if the theorem is proved: "THEOREM PROVED"

 ```text
assign(max_seconds, 30).
set(binary_resolution).
set(print_gen).

formulas(assumptions).
    P.                 % Assume P is true
    P -> Q.            % If P is true, then Q is true
end_of_list.

formulas(goals).
   Q.                  % Goal: Prove Q is true
end_of_list.
 ```
**2. Modus Tollens**

- Download the file https://github.com/mariusstoica21/AI_Lab/blob/main/files/lab6/modus_tollens.in
- Place the file into Home/Documents/Prover9/bin folder
- Open terminal in the path
- Run the command: ./prover9 -f modus_tollens.in
- Verify if the theorem is proved: "THEOREM PROVED"

 ```text
assign(max_seconds, 30).
set(binary_resolution).
set(print_gen).

formulas(assumptions).
    -Q.                % Assume Q is false
    P -> Q.            % If P is true, then Q is true
end_of_list.

formulas(goals).
   -P.                 % Goal: Prove P is false
end_of_list.
 ```

**3. Hypothetical Syllogism**

- Download the file https://github.com/mariusstoica21/AI_Lab/blob/main/files/lab6/hypothetical_syllogism.in
- Place the file into Home/Documents/Prover9/bin folder
- Open terminal in the path
- Run the command: ./prover9 -f hypothetical_syllogism.in
- Verify if the theorem is proved: "THEOREM PROVED"
 
 ```text
assign(max_seconds, 30).
set(binary_resolution).
set(print_gen).

formulas(assumptions).
    P -> Q.           % If P is true, then Q is true
    Q -> R.	     % If Q is true, then R is true
end_of_list.

formulas(goals).
   P -> R.            % Goal: Prove if P is true, then R is true
end_of_list.
 ```

## 📂 Lab 6 - Models in propositional logic

## 📂 Lab 6.1. - Princesses and tigers

**Problem description (Sentences):**

A prisoner is given by the King holding him the opportunity to improve his situation if he solves a puzzle. He is told there are three rooms in the castle: one room contains a lady and
the other two contain a tiger each. If the prisoner opens the door to the room containing the lady, he will marry her and get a pardon. If he opens a door to a tiger room though, he will be
eaten alive. Of course the prisoner wants to get married and be set free than being eaten alive. The door of each room has a sign bearing a statement that may be either true or false. The
sign on the door of the room containing the lady is true and at least one of the signs on the doors of the rooms containing tigers is false. The signs say respectively:
- (The sign on the door of room #1): There is a tiger in room #2.
- (The sign on the door of room #2): There is a tiger in this room.
- (The sign on the door of room #3): There is a tiger in room #1.

**Question:**

Can you tell in which room the lady is?

**Formalizing in FOL**

**Step 1: There is a lady in room number 1, 2 or 3**

 ```text
%assign(max_seconds, 30).
%set(binary_resolution).
%set(print_gen).

formulas(assumptions).
   l1 | l2 | l3.
end_of_list.

formulas(goals).
end_of_list.
 ```
Command: ./mace4 -c -n 2 -m -1 -f lady1.in

<div align="center">
  <img 
    src="https://github.com/mariusstoica21/AI_Lab/blob/main/images/img35.png"
    width="500"
    height="auto"
    alt="Img. 6.1. - Models found for step 1"
  >
  <br>
  <em>Img. 6.1. - Models found for step 1</em>
</div>

**Step 2: No lady in more than 1 room (the princess is unique)**

 ```text
%assign(max_seconds, 30).
%set(binary_resolution).
%set(print_gen).

formulas(assumptions).
   l1 | l2 | l3.
   l1 -> -l2.
   l1 -> -l3.
   l2 -> -l1.
   l2 -> -l3.
   l3 -> -l1.
   l3 -> -l2.
end_of_list.

formulas(goals).
end_of_list.
 ```
Command: ./mace4 -c -n 2 -m -1 -f lady2.in

<div align="center">
  <img 
    src="https://github.com/mariusstoica21/AI_Lab/blob/main/images/img36.png"
    width="500"
    height="auto"
    alt="Img. 6.2. - Models found for step 2"
  >
  <br>
  <em>Img. 6.2. - Models found for step 2</em>
</div>

**Step 3: Add the whole Knowledge Base**

 ```text
%assign(max_seconds, 30).
%set(binary_resolution).
%set(print_gen).

formulas(assumptions).
   %there is a lady in room 1,2 or 3
   l1 | l2 | l3.
   
   %no lady in more than 1 room
   l1 -> -l2.
   l1 -> -l3.
   l2 -> -l1.
   l2 -> -l3.
   l3 -> -l1.
   l3 -> -l2.
   
   %there are 2 tigers in 2 of the rooms 1,2 or 3
   t1 & t2 | t1 & t3 | t2 & t3.
   
   %no tiger in the room where the lady stays
   l1 -> -t1.
   l2 -> -t2.
   l3 -> -t3.
   
   %clue on door #1 : there is a tiger in room #2
   l1 -> t2.
   
   %clue on door #2 : there is a tiger here
   l2 -> t2.
   
   %clue on door #3 : there is a tiger in room #1
   l3 -> t1.
   
   %at least one of the clues on tiger room lies
   (t1 & t2) -> (-t2 | -t2).
   (t2 & t3) -> (-t2 | -t1).
   (t1 & t3) -> (-t2 | -t1).
end_of_list.

formulas(goals).
end_of_list.
 ```
Command: ./mace4 -c -n 2 -m -1 -f lady3.in

<div align="center">
  <img 
    src="https://github.com/mariusstoica21/AI_Lab/blob/main/images/img36.png"
    width="500"
    height="auto"
    alt="Img. 6.3. - Models found for step 3"
  >
  <br>
  <em>Img. 6.3. - Models found for step 3</em>
</div>

## 📂 Lab 7 - First Order Logic

**Sentences:**
1. Marcus was a man.
2. Marcus was a Pompeian.
3. All Pompeians were Romans.
4. Caesar was a ruler.
5. All Romans were either loyal to Caesar or hated him.
6. Everyone is loyal to someone.
7. People only try to assassinate rulers they are not loyal to.
8. Marcus tried to assassinate Caesar.
9. All men are people.

**Formalize in First Order Logic:**
1. man(Marcus).
2. Pompeian(Marcus).
3. all x (Pompeian(x) -> Roman(x)).
4. ruler(Caesar).
5. all x (Roman(x) -> loyalto(x,Caesar) | hate(x,Caesar)).
6. all x (exists y (loyalto(x, y))).
7. all x (all y (person(x) & ruler(y) & tryassassinate(x,y) -> -loyalto(x,y))).
8. tryassassinate(Marcus,Caesar).
9. all x (man(x) -> person(x)).

**Inferences**
1. Was Marcus loyal to Caesar?
- loyalto(Marcus,Caesar).
2. Did Marcus hate Caesar?
- hate(Marcus,Caesar).

<div align="center">
  <img 
    src="https://github.com/mariusstoica21/AI_Lab/blob/main/images/img33.png"
    width="500"
    height="auto"
    alt="Img. 7.1. - Proof that Marcus was not loyal to Caesar"
  >
  <br>
  <em>Img. 7.1. - Proof that Marcus was not loyal to Caesar</em>
</div>

<div align="center">
  <img 
    src="https://github.com/mariusstoica21/AI_Lab/blob/main/images/img34.png"
    width="500"
    height="auto"
    alt="Img. 7.2. - Proof that Marcus hated Caesar"
  >
  <br>
  <em>Img. 7.2. - Proof that Marcus hated Caesar</em>
</div>


## 📂 Lab 9 - Constraint satisfaction problems

## 📂 Lab 9.1. - Solving CSP by consistency checking

##  Lab 9.1.1. - Setup

1. Go to http://www.aispace.org/downloads.shtml
2. Download Consistency Based CSP Solver: Version 4.6.1. (.jar download)
3. In Documents folder, create a new folder 'CSP_Solver'
4. Copy 'constraint.jar' file downloaded at step 2, and paste into Documents/CSP_Solver folder created at step 3.
5. In folder Documents/CSP_Solver, right click and "Open in Terminal"
6. Run the following command in order to open CSP Solver "java -jar constraint.jar"

<div align="center">
  <img 
    src="https://github.com/mariusstoica21/AI_Lab/blob/main/images/img19.png"
    width="500"
    height="auto"
    alt="Img. 9.1. - CSP Solver G.U.I."
  >
  <br>
  <em>Img. 9.1. - CSP Solver G.U.I.</em>
</div>

##  Lab 9.1.2. - Create Problem

1. Create the following problem that shall be solved using AC-3 algorithm: https://www.youtube.com/watch?v=4cCS8rrYT14&t=240s
1.1. Create variables: A = {1,2,3}, B = {1,2,3}, C = {1,2,3}
- Select 'Create Varible' button and left-click into the white screen
- Provide 'Variable Name' (for example, 'A')
- Provide 'Domain Type' (for example, 'Integer')
- Provide 'Domain' (for example, '1,2,3')
- Create all the remaining variables

<div align="center">
  <img 
    src="https://github.com/mariusstoica21/AI_Lab/blob/main/images/img20.png"
    width="500"
    height="auto"
    alt="Img. 9.2. - Create Variable"
  >
  <br>
  <em>Img. 9.2. - Create Variable</em>
</div>

<div align="center">
  <img 
    src="https://github.com/mariusstoica21/AI_Lab/blob/main/images/img21.png"
    width="500"
    height="auto"
    alt="Img. 9.3. - All variables created"
  >
  <br>
  <em>Img. 9.3. - All variables created</em>
</div>

1.2. Create constraints: A > B, B = C
- Select 'Create Constraint' button and choose the variables contained by the constraint (for example, 'A' and 'B' for 'A > B')
- Choose 'Constraint Type' (for example 'GreaterThan') and click 'OK' button
- Create all the remaining constraints

<div align="center">
  <img 
    src="https://github.com/mariusstoica21/AI_Lab/blob/main/images/img22.png"
    width="500"
    height="auto"
    alt="Img. 9.4. - Create Constraint"
  >
  <br>
  <em>Img. 9.4. - Create Constraint</em>
</div>

<div align="center">
  <img 
    src="https://github.com/mariusstoica21/AI_Lab/blob/main/images/img23.png"
    width="500"
    height="auto"
    alt="Img. 9.5. - All constraints created"
  >
  <br>
  <em>Img. 9.5. - All constraints created</em>
</div>

##  Lab 9.1.3. - Solve Problem

1. Change to 'Solve mode'
2. Click 'Auto Arc-Consistency' and wait
3. Check the solution found: A = {2,3}, B = {1,2}, C = {1,2}

<div align="center">
  <img 
    src="https://github.com/mariusstoica21/AI_Lab/blob/main/images/img24.png"
    width="500"
    height="auto"
    alt="Img. 9.6. - Auto Arc-Consistency"
  >
  <br>
  <em>Img. 9.6. - Auto Arc-Consistency</em>
</div>

##  Lab 9.1.4. - Save CSP

1. Click on File -> Save CSP
2. In the new windows, go to 'Documents/CSP_Solver' and provide a name (for example, CSP_1.xml)
3. Click 'Save' button

##  Lab 9.1.5. - Load CSP

1. Click File -> Load from File
2. Go to 'Documents/CSP_Solver' and select CSP_1.xml
3. Click 'Open' button

## 📂 Lab 9.2. - Solving CSP with stochastic local search

##  Lab 9.2.1. - Setup

1. Go to http://www.aispace.org/downloads.shtml
2. Download Stochastic Local Search Based CSP Solver: Version 4.6.0. (.jar download)
3. In Documents folder, create a new folder 'CSP_Solver_SLS'
4. Copy 'hill.jar' file downloaded at step 2, and paste into Documents/CSP_Solver_SLS folder created at step 3.
5. In folder Documents/CSP_Solver_SLS, right click and "Open in Terminal"
6. Run the following command in order to open CSP Solver "java -jar hill.jar"

<div align="center">
  <img 
    src="https://github.com/mariusstoica21/AI_Lab/blob/main/images/img25.png"
    width="500"
    height="auto"
    alt="Img. 9.7. - CSP Solver Stochastic Local Search G.U.I."
  >
  <br>
  <em>Img. 9.7. - CSP Solver Stochastic Local Search G.U.I.</em>
</div>

##  Lab 9.2.2. - Load Sample Problem

1. Click on File -> Load Sample CSP
2. Select 'Five Queens Problem' and click 'Load'
   
<div align="center">
  <img 
    src="https://github.com/mariusstoica21/AI_Lab/blob/main/images/img26.png"
    width="500"
    height="auto"
    alt="Img. 9.8. - Load sample CSP"
  >
  <br>
  <em>Img. 9.8. - Load sample CSP</em>
</div>

<div align="center">
  <img 
    src="https://github.com/mariusstoica21/AI_Lab/blob/main/images/img27.png"
    width="500"
    height="auto"
    alt="Img. 9.9 - Five Queens Problem"
  >
  <br>
  <em>Img. 9.9. - Five Queens Problem</em>
</div>

##  Lab 9.2.3. - Solve Problem

1. Go to 'Solve mode'
2. Click 'Initialize' button
3. Go to Hill Options -> Algorithm Options
4. At 'Local Search Steps' choose 'Random Walk'/'Greedy Descent'
5. At 'Termination' select maximum number of steps (for example 100)
6. Click 'OK'
7. Click 'Auto Solve' and wait to find a solution (depending on the algorithm selected)
8. Click 'Batch Run' in order to see a comparison between the selected algorithms
9. Click 'Show Plot' in order to see the number of conflicts present at each step

<div align="center">
  <img 
    src="https://github.com/mariusstoica21/AI_Lab/blob/main/images/img29.png"
    width="500"
    height="auto"
    alt="Img. 9.10. - Batch Run: Random Walk vs Greedy Descent"
  >
  <br>
  <em>Img. 9.10. - Batch Run: Random Walk vs Greedy Descent</em>
</div>

<div align="center">
  <img 
    src="https://github.com/mariusstoica21/AI_Lab/blob/main/images/img28.png"
    width="500"
    height="auto"
    alt="Img. 9.11. - Five Queens Problem - Show Plot Random Walk"
  >
  <br>
  <em>Img. 9.11. - Five Queens Problem - Show Plot Random Walk</em>
</div>

<div align="center">
  <img 
    src="https://github.com/mariusstoica21/AI_Lab/blob/main/images/img30.png"
    width="500"
    height="auto"
    alt="Img. 9.12. - Five Queens Problem - Show Plot Greedy Descent"
  >
  <br>
  <em>Img. 9.12. - Five Queens Problem - Show Plot Greedy Descent</em>
</div>

## 📂 Lab 10 - Classical planning

## 📂 Lab 10.1. - Install FastDownward

1. In folder 'Documents', create a new folder named 'FD'
2. Go to "https://github.com/aibasel/downward" and click the green 'Code' button
3. Click 'Download ZIP'
4. Go to 'Downloads' and copy 'downward-main.zip'
5. Paste 'downward-main.zip' file into 'Documents/FD' folder created at step 1
6. Right click the 'downward-main.zip' file and click 'Extract Here'
7. Go into the 'downward-main' folder created
8. Right click and 'Open in Terminal'
9. Run the following commands:
- sudo apt install cmake g++ make python3
- export cplex_DIR=/opt/ibm/ILOG/CPLEX_Studio2211/cplex
- sudo apt install libgmp3-dev
- wget https://github.com/scipopt/soplex/archive/refs/tags/release-710.tar.gz -O - | tar -xz
- cmake -S soplex-release-710 -B build
- cmake --build build
- export soplex_DIR=/opt/soplex-7.1.0
- cmake --install build --prefix $soplex_DIR
- ./build.py

<div align="center">
  <img 
    src="https://github.com/mariusstoica21/AI_Lab/blob/main/images/img31.png"
    width="500"
    height="auto"
    alt="Img. 10.1. - Administrative priviliges error that is supposed to arrive, after that run './build.py'"
  >
  <br>
  <em>Img. 10.1. - Administrative priviliges error that is supposed to arrive</em>
</div>

## 📂 Lab 10.2. - Create domain.pddl and generate problem.pddl using GENERATOR

1. In 'Documents/FD/downward-main' create folder 'Gripper'
2. Go to 'https://fai.cs.uni-saarland.de/hoffmann/ff-domains.html' to the 'Gripper' section
3. From the Gripper section, download 'domain.pddl'
4. Paste the 'domain.pddl' file into 'Documents/FD/downward-main/Gripper' folder
5. From the Gripper section, download 'GENERATOR.tar.gz' into 'Documents/FD/downward-main/Gripper' folder
6. Right click the 'GENERATOR.tar.gz' and 'Extract Here'
7. Go into the 'GENERATOR' folder
8. Right click in the folder and click 'Open in Terminal'
9. Run 'make'
10. Run './gripper -n 8' (Create a problem with 8 balls)
11. Copy content printed in terminal into 'problem.pddl' file created in the folder 'Documents/FD/downward-main/Gripper'
12. Go to 'Documents/FD/downward-main' and run the command './fast-downward.py Gripper/domain.pddl Gripper/problem.pddl --search "astar(lmcut())'
13. Check if 'Solution found'

<div align="center">
  <img 
    src="https://github.com/mariusstoica21/AI_Lab/blob/main/images/img32.png"
    width="500"
    height="auto"
    alt="Img. 10.2. - Solution found"
  >
  <br>
  <em>Img. 10.2. - Solution found</em>
</div>
  


### Icons

<ul>
  <li><a href="https://www.flaticon.com/free-icons/artificial-intelligence" title="artificial intelligence icons">Artificial intelligence icons created by rukanicon - Flaticon</a></li>
</ul>
