git config --global user.name "Khushboo"
git config --global user.email "khushbooyadav7964@gmail.com"
git config --global core.editor "code --wait"
git config --global core.autocrlf

git installation

stages:
u-untracted
A-added or staged
C-commited

1. make saved check point - make a file, add, message commit , then it make the file at the check point
2. want to know the how many saved points = git log --oneline
3. how to go back to the previous check point in the code =
   git reset --hard HEAD~1 / soft
   # when you go back to the check point it gets deleted there is no way of going after the file
