# Getting Started

## Step 0: Find something you want  to analyze
Find (or think of) a dataset (or other data source) you want to programmatically analyze. Can be a a final you have stored locally (easier) or hosted publically or both. Could also be a website you want to scrape. 

## Step 1: Determine your OperatingSystem, Copy it Somewhere, will need at times
1. Mac users: About this Mac > Mac OS
2. Windows users: Start > Settings > System > About

## Step 2: Start a chat with a chatGPT Paid Accounts
1. Go to [chatgpt.com](chatgpt.com). Login with your credentials or those that I provides. Open a window
2. Enter this prompt to get started.  Allows chatGPT to help you problem solve issues independently. If you hit errors throughout any of the follow steps, send a description of the error to *this conversation* in Chat GPT and see if it can help you through it.  
>>I am learning Python and Visual Studio. I have not coded before.  This is my Operatin system: [ENTER YOUR OS].  Can you help me get started?


## Step 3: Download & Install Visual Studio Code 
* [Download VS Code](https://code.visualstudio.com/) based on your Operating System. If prompted, make sure to select the option to add VS Code to your PATH (so you can open it from the command line)



##  Step 4: [Create a github.com account](https://github.com), store your credentials somwhere
Visit the [homepage of this tutorial](https://github.com/jessicayeats/YeatsPythonTutorial) will have an up-to-date version of this guidance

## Step 5: Create an 'SSH Key' on your Local Machine  (enables Cloning Github Repositories)
1. Open VS Code and Open Terminal: In the VS Code Menu Bar --> Terminal --> "New Terminal". It should open up int he bottom panel 
2. Run this command, replacing your_email@gmail.com with you email address
```
ssh-keygen -t ed25519 -C "your_email@gmail.com"
```
3. Press "enter" for the next 3 commands (e.g., enter file where to save, enter passphrase, enter passphrase again)
4. Copy the output of this command 
```
cat ~/.ssh/id_ed25519.pub
```
5. Login to your github account and go to the SSH setting https://github.com/settings/keys
6. Press 'New SSH Key' and paste this key into the box . Give the key any name you want


## Step 6: Create a folder on your laptop called 'Development' and always keep coding stuff in here
* Open terminal within VS Code and navigate to your home directory
``` cd ~/.```
* Write down the path to your home directory somwewhere, find it with this command
``` pwd ```
* Create a folder within your home directory called 'Development' with this command (if that fails you can create it manually using folder)
``` mkdir Development ```
* Run this command to set expansive read/write 'permissions' within this directory. Also save the 'Development' directory to your 'favorites'
``` chmod -R 777 Development ```



## Step 6: Clone the GitHub repository (within your 'Development' folder) with other steps in tutorial
1. Open Terminal in VS Code (should be open from previous step)
2. Navigate to the 'Development' Folder (you will do this a lot)
``` cd ~/Development ```
2. Clone the repo with this command:
```
git clone git@github.com:jessicayeats/YeatsPythonTutorial.git
```

## Step 7: Install Python3 if not already installed
1. Check if its pre-installed (must be python 3.9 or later). Enter this in Terminal
```
python3 --version 
```
2. If not installed or < version 3.7, [Download and install python](
python.org/downloads/)  Make sure to select the option to add Python to your PATH during installation. 
3. After you install python, restart your laptop and VS Code (otherwise VS code sometimes does not recognize)


## Step 8: Install  dependencies in 'requirements.txt' in this repo
* Note: best way to do this is with a virtual environment using 'conda' or 'venv' - probably too much for 101 but keep this in mind as your progress
* Open Terminal, navigate to the 'repository' directory
``` cd ~/Development/YeatsPythonTutorial ```
* Install the requirements in requirements.txt (will fail if you didn't install python correctly) 
``` python3 -m pip install -r requirements.txt  ```
* Note - normally if you want to install a single pacakge you do with this statement. the command above lets you install everything in a .txt file at once
``` python3 -m pip install <package_name> ```


## Dependencies / Requirements
1. Download & Install the [latest Python Release](https://www.python.org/downloads/) that is compatible with your Operating System
2. Download & Install Visual Studio Code ('VS Code')

## Code blocks
```
this is where code goes


* Install pip 
* Add an example .csv in the directory 
* Add 'add code extention'
* Show an example of opening a file with 'code xxx'
```