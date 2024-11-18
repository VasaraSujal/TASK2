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

#### Task 5: Undoing Changes

1. To remove the file from stagging area
```bash
   git reset file1.txt
```
2. Discard uncommitted changes:  
```bash
   git checkout -- file1.txt
```

#### Task 6: Branch Management
1. Create a branch and switch to it:  
```bash
   git checkout -b feature-branch
```
2. List branches:  
```bash
   git branch
```
3. Rename a branch:  
```bash
   git branch -m feature-branch feature-enhanced
```

#### **Task 7: Merging Branches**
1. Switch to a main branch and then merge  
```bash
   git checkout main
   git merge feature-enhanced
```

#### Task 8: Handling Merge Conflicts




#### Task 9: Remote Setup

1. Add a remote repository:  
```bash
   git remote add origin url
```
2. Verify the remote:  
```bash
   git remote -v
```

#### Task 10: Push and Pull

1. Push changes to the remote repository:  
```bash
   git push -u origin main
```
2. Pull changes from the remote:  
```bash
   git pull origin main
```

#### Task 11: Cloning a Repository

1. Clone a remote repository:  
```bash
   git clone https://github.com/your-username/repo.git
```

#### Task 12: Stashing Changes

1. To save uncommitted changes:  
```bash
   git stash
```
2. Apply stashed changes:  
```bash
   git stash apply
```
3. Drop the stash:  
```bash
   git stash drop
```

#### Task 13: Tagging Commits









#### Task 16: Forking and Pull Requests

1. Fork a repository in your github account and clone it
```bash
    git clone "url"
```