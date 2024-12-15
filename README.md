# Getting Started

## Step 1: Determine your OperatingSystem, Copy it Down
1. Mac users: About this Mac > Mac OS
2. Windows users: Start > Settings > System > About

## Step 2: Start a chat with a chatGPT Paid Accounts
1. Go to [chatgpt.com](chatgpt.com). Login with your credentials or those that I provides. Open a window
2. Enter this prompt to get started. This will allow chatGPT to help you problem solve issues you encounter when I'm not availble to chat/ work through them with you.  Most of the instructions should be covered in this document, but chatGPT can help interpret or adjust guidance. **When you 
>>I am learning Python and Visual Studio. I have not coded before.  This is my Operatin system: [ENTER YOUR OS].  Can you help me get started?

3. **Important!** You will encounter errors along the way. When you do (during this setup process or throughout your journey as a coder) send the entire error message to this chatGPT conversation. Add as much context as possible, including these instructions. ChatGPT should be able to help you troubleshoot and resolve, though it often takes many re-tries. 

## Step 3: Download & Install Visual Studio Code 
1. [Download VS Code](https://code.visualstudio.com/) based on your Operating System. 
2. Install VS code. If prompted, make sure to select the option to add VS Code to your PATH (so you can open it from the command line)



##  Step 4: [Create a github.com account](https://github.com)
Save your account credentials somewhere so you can access later

## Step 6: Create an 'SSH Key' on your Local Machine  (enables Cloning Github Repositories)
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

## Step 5: Install Python 

### Mac Users - How to Install Python

### Windows Users - How to Install Python

## Step 6: Restart your laptop and re-open vs code
Otherwise VS Code may not recognize python,,

## Step 7: 

##
## Dependencies / Requirements
1. Download & Install the [latest Python Release](https://www.python.org/downloads/) that is compatible with your Operating System
2. Download & Install Visual Studio Code ('VS Code')

## Code blocks
```
this is where code goes
```