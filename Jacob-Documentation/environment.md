# My Process Setting Up the Virtual Environment/Learning how to use the virtual environment

- Setting up my Virtual Environment took quite a while, so I'd like to document some of the process that I remember.
- First, I started with learning a little bit more about virtual environments, because I had never used one before
- After that I decided to run Jacob Hebbel's venv-setup in the VScode terminal, which was just a bash script that helped create the environment
- (Which worked great)
- I struggled and did make some mistakes, like using pip install globally, and I had to figure out how to get the python environment for ais 
working
- The setup folder (ais) contains:
    1. Lib (which just contains all of the python libraries in this environment)
    2. Scripts (which just contains a bunch of executables which help python run in the environment(and the actual python.exe))
- Then, I ran into a error where I could not run my python program through the virtual environment 
- And also pushing my code of the venv-setup with my practice neural network model caused an error

## How I solved these errors
- When running through the error of running my python program with Jacob Hebbel, we looked at the "Select Environment" part of VSCode
- This seemed to work perfectly fine but I couldn't run the file with the play button in the top right of vscode like usual
- Solution: Run through the terminal. The run button i learned may have been running the global python and created errors. I'm not completly
sure what went wrong but running through the terminal is always the way to go

- When pushing with the venv-setup, it took a long while to figure this issue out but it required resetting to another version of git
- Solution: I pushed the head to a previous commit and that seemed to solve things, I also saw my commit later so this might've just been a 
local issue. 
- I will definetly use gitignore next time.

## What I learned
- Check the file size of your commits so you do not have nay issues with the gui/pushing and make sure you resolve the file issue asap
- When dealing with something like a setup you are able to use gitignore. Something very important for git and something I used
in my own personal project RECS with node_modules(A setup for NodeJS)
- Gitignore is very good practice because you do not have to recommit/push/merge these libraries and not have to worry about them globally
- You will also have these setup files locally. 