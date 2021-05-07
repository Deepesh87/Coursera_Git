#more git commands
Base Command was present in the code.py file before git init.
When I do git status it tells me a new file was added i.e. code.py
When I add command #1, and run git status it tells me file modified along with a new file was added for the same code.py
When i git add code.py it tell me Changes ready to be commited.

To ignore a file with name test.txt do this
1) echo test.txt > .gitignore, use >> if youw ant to append
2) git add .gitignore
3) git commit -m 'message'

to undo the chnages that has been made to an already being tracked file
with the chgs being not added yet, we use the git checkout filename command

git checkout filename --> used on unstaged but tracked files. Chnages made will be lost

git reset HEAD filename --> used on staged files (changes will be lost) brings us back to unstaged level


git commit --amend --> edit ( add comments, add more files etc) to previous commit

