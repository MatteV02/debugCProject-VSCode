# Sample debug folder

## NOTE
- to preview this file Ctrl+Shift+V  

## Content
1.  .vscode directory, directory with configuration files
2.  main.c, the file where to paste the code to debug
3.  makefile, file configured for debugging the project

## How to use
1.  Paste your code overwriting main.c and save it
2.  Compile your code. You have 2 ways to do this:
    - press Ctrl+B
    - open an integrated terminal (Terminal *in the menu bar* ➜ New terminal) and run `make`
3.  Insert a breakpoint in your code
4.  Run Debug
    - Open the debug pane 
        - ![](/images/DebugPane.png)
    - click play

## How to debug child process
1.  Open [.vscode/launch.json](/.vscode/launch.json)
    - ![](/images/launchJSON.png)
2.  Change in this file the word "parent" to "child" on line 33
    - ![](/images/changeParentToChild.png)