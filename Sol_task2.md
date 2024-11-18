### Part 1: Git Basics

#### Task 1: Install and Configure Git

1. First install the Git from [git-scm.com](https://git-scm.com/)

2. Configure your global Git settings:  
``` bash
    git config --global user.name "Vasara Sujal"
    git config --global user.email "vasarasujal.cg@gmail.com"
```
3. Verify the configuration
```bash
    git config --list
```

#### Task 2: Initialize a Repository

1. Create a new directory and initialize the repository
``` bash
    mkdir TASK2
    cd TASK2
    git init
```

#### Task 3: Creating and Committing Files

1. Create a new file and add to the stagging area and commit
```bash
    echo "first commit" >> file1.txt
    git add file1.txt
    git commit -m "Initial commit"
```

#### Task 4: Viewing Changes

1. Make some changes in this file
```bash
    echo "Modify this file" >> file1.txt
```
2. Check file status and differences:  
```bash
   git status
   git diff
```