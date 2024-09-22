<p align="left">
  <img 
    src="https://github.com/mariusstoica21/AI_Lab/blob/main/images/header.png"
  >
</p>

## 🔗 Useful videos
- Ubuntu Installation using Oracle VirtualBox: https://www.youtube.com/watch?v=hYaCCpvjsEY&t=185s
- Debugging in PyCharm: https://www.youtube.com/watch?v=sRGpvbhOhQs
  
## 📂 Lab 1 - Install Ubuntu, PyCharm, Python 2.7 and Create New Project

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
<p align="center">
  <img 
    src="https://github.com/mariusstoica21/AI_Lab/blob/main/images/img1.jpeg"
    width = "500"
    height = "auto"
  >
</p>

   - In the 'New Project' window, do the following steps:
      - Provide name: For example 'AI_Labs'
      - Provide location: For example '/home/username/Documents'
      - Provide interpreter: Insert path of the Python 2.7 interpreter
         - In order to get the interpreter path, open a terminal and write the following command
            - which python2.7     

<p align="center">
  <img 
    src="https://github.com/mariusstoica21/AI_Lab/blob/main/images/img2.jpeg"
    width = "500"
    height = "auto"
  >
</p>

   - Download search.zip by opening from https://s3-us-west-2.amazonaws.com/cs188websitecontent/projects/release/search/v1/001/search.zip
   - Move search.zip file into PyCharm folder created above (AI_Labs for example)
   - Unzip search.zip
      - After unzipping, copy the content from 'search' folder directly into AI_Labs folder, and remove the search.zip file and search folder
   - Run file 'pacman.py' by right-clicking the file, and selecting 'Run pacman.py'
    
<p align="center">
  <img 
    src="https://github.com/mariusstoica21/AI_Lab/blob/main/images/img3.jpeg"
    width = "250"
    height = "auto"
  >
</p>

   - Enjoy the game!
<p align="center">
  <img 
    src="https://github.com/mariusstoica21/AI_Lab/blob/main/images/img4.jpeg"
    width = "400"
    height = "auto"
  >
</p>


## Tutorials



## Links
