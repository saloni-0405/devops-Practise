\# Assignment 5: Git \& GitHub



\## 1) Git and GitHub Basics Workflow



\### A. Clone Repository

git clone <repository-url>



\### B. Create README and Commit

touch README.md

git add README.md

git commit -m "Added README"



\### C. Configure Git

git config --global user.name "Your Name"

git config --global user.email "your@email.com"



\### D. Pull Repository

git pull origin main



\### E. Edit and Add Files

touch index.html

git add README.md index.html



\### F. Push Changes

git push -u origin main



\---



\## 2) Branching Workflow



\### Create commits

echo "<h1>Heading</h1>" >> README.md

git add README.md

git commit -m "C0"



touch file.txt

git add file.txt

git commit -m "C1"



echo "update" >> file.txt

git add file.txt

git commit -m "C2"



git push origin main



\---



\### Create branch iss53

git checkout -b iss53

touch index.html

git add index.html

git commit -m "C3"



git diff C1 C2

git push origin iss53



\---



\### Create hotfix branch

git checkout main

git checkout -b hotfix

echo "fix" >> file.txt

git add file.txt

git commit -m "C4"

git push origin hotfix



\---



\### Merge hotfix

git checkout main

git merge hotfix

git branch -d hotfix



\---



\### Merge iss53

git checkout main

git merge iss53

git branch -d iss53

