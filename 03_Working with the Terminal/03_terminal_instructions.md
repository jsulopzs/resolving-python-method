# #03 | Working with the Terminal

## Basic Commands

The working directory in which you are right now


```bash
pwd
```

    /Users/user/resolving-python-data-science/02_Promote Your Portfolio

Make a new folder

```bash
mkdir new_folder
```

Make new folders

```bash
mkdir hi how are you
```

List of files & directories within the current directory

**Windows**

```bash
dir
```

    02_portfolio_instructions.md

**Mac**

```bash
ls 
```

    02_portfolio_instructions.md


Change the working directory to the previous directory


```bash
cd ..
```

The files & folders aren't the same ones as before


```bash
ls
```

    00_Introduction Motivation & Philosophy
    01_The Use of Functions
    02_Promote Your Portfolio
    03_Working with the Terminal
    04_Master the Python Syntax
    05_Reading Data into Python
    06_Transforming Basic Objects into the Powerful DataFrame
    07_The Python Resolver Discipline
    08_Masking & Filtering
    09_Manipulate the DataFrame Like a Pro for Data Visualization
    10_Many Paths to Rome with Data Visualization
    11_What Is Next
    99_Extras
    LICENSE
    README.md
    data


Because we have changed the working directory


```bash
pwd ..
```

    /Users/user/resolving-python-data-science


## GitHub Commands

Download your online repository from your terminal using the Git application


```bash
git clone https://github.com/your_user_name/pandas_exercises
```

Change the working directory to the downloaded folder


```bash
cd pandas_exercises
```

Modify a file & upload the changes 

1. Add the changes to the qeue


```bash
git add -A
```

2. Commit the changes with a message


```bash
git commit -m "your message"
```

3. Upload the changes to the online repository


```bash
git push
```
