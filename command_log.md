git init
touch .gitignore
ls
ls -a
touch file1.txt
ls
git ls-files
git status
git add .
git status -s
git commit -m "Add files to master branch"
git checkout -b feature1
touch file2.txt
touch file3.txt
git status
git status -s
git ls-files
git add .
git status
git commit -m "Add files to feature1 branch"
echo "Added content to file2" > file2.txt
git status -s
git diff
git status -s
git add "file2.txt"
git commit -m "Add modified file2 to feature1 branch"
git status 
git log
echo "Temp file" > temp.txt
git status -s
git stash
git status -s
git add "temp.txt"
git status -s
git stash
git status
git stash list
git remote add origin git@github.com:AshiyaAjare/GIT-Basics-Assignment.git
git push -u origin feature1
git checkout -b feature2
ls
git rm file1.txt
ls
git add .
git status -s
git commit -m "remove file 1 from feature2"
git ls-files
git status -s
git reset --soft HEAD~1
git reset --hard HEAD~1
git log
echo "This is file2" > file2.txt
git diff
git push -u origin feature2
touch command_log.md
history > command_log.md
