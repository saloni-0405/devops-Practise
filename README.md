\# DevOps Practice Repository



This repository is created to practice Git and GitHub commands for my exam.



\## Added new section for practice



🔹 SETUP (First Time)

git config --global user.name "Your Name"

git config --global user.email "your@email.com"



\--------------------------------------------------



🔹 CLONE REPOSITORY

git clone <repo-url>

cd <repo-folder>



\--------------------------------------------------



🔹 BASIC WORKFLOW

(edit files)

git add .

git commit -m "message"

git push -u origin main



\--------------------------------------------------



🔹 DAILY COMMANDS

git status          → check changes

git add file        → add specific file

git add .           → add all files

git commit -m ""    → save changes

git push            → upload changes

git pull origin main→ get latest changes



\--------------------------------------------------



🔹 FILE COMMANDS

ls                  → list files

cd folder-name      → go inside folder

cd ..               → go back

touch file.txt      → create file

notepad file.txt    → edit file



\--------------------------------------------------



🔹 FIRST PUSH FIX

git branch -M main

git push -u origin main



\--------------------------------------------------



🔹 COMMON ERRORS \& FIXES



1\. destination path exists

&#x20;  → folder already present (ignore or delete)



2\. cd.. not working

&#x20;  → use: cd ..



3\. wrong folder name

&#x20;  → check with ls (case-sensitive)



4\. couldn't find remote ref main

&#x20;  → repo empty → push first



5\. Please tell me who you are

&#x20;  → run config commands



6\. src refspec main error

&#x20;  → git branch -M main

&#x20;    git push -u origin main



\--------------------------------------------------



🔹 KEY CONCEPTS

Repository = project

Clone = download repo

Add = stage files

Commit = save changes

Push = upload to GitHub

Pull = download updates



\--------------------------------------------------



🔹 GOLDEN ORDER

edit → add → commit → push

