# Exercise 4 - Adding files

1. Look git status for your directory, and paste the contents below

        git status

On branch master
Changes not staged for commit:
  (use "git restore <file>..." to discard changes in working directory)
        modified:   exercise01.md
        modified:   exercise02.md
        modified:   exercise03.md

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        my_respository/

2. Using VS Code, the command line, or your favorite code editor, create a new file named `fruits.txt`.

3. Check your git status, and paste the contents here

        git status

On branch master
Changes not staged for commit:
        modified:   exercise01.md
        modified:   exercise02.md
        modified:   exercise03.md

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        fruits.txt
        my_respository/

4. Add the new file to your index

        git add fruits.txt

On branch master
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   fruits.txt

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   exercise01.md
        modified:   exercise02.md
        modified:   exercise03.md

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        my_respository/


5. Check git status again, and paste the contents below

        git status

On branch master
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   fruits.txt

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   exercise01.md
        modified:   exercise02.md
        modified:   exercise03.md

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        my_respository/