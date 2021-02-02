[![Work in Repl.it](https://classroom.github.com/assets/work-in-replit-14baed9a392b3a25080506f3b7b6d57f295ec2978f6f33ec97e36a161684cbe9.svg)](https://classroom.github.com/online_ide?assignment_repo_id=3936377&assignment_repo_type=AssignmentRepo)

# Data structures and algorithms

## Description
This repository contains work for week 1 DSA content implementation

## Requirements
Requirements to run any of these scripts are highlighted under *requirements.txt*, in addition to that you need:
- Tkinter:
> sudo apt-get install python3-tk (*Linux specific*)
- Python 3: some modules might not be "compatible" with **Python 2**

## Test
For you to test what we have worked on yout should follow the following steps:
- Clone the repository to your local computer
- Install pip or pip3 based on your OS
- Install a virtual environment and set up the environment:
> pip3 install virtualenv
>
> virtualenv -p python3 venv
>
> source venv/bin/activate (*activates venv, Linux specific*)
>
> pip3 install -r requirements.txt    
- **Cd** in the appropriate directory
- To run memory check run:
> python3 -m memory_profiler memory_time_test.py
- To run memory and time check with plots run:
> mprof run memory_time_test.py && mprof plot