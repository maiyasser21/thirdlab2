# thirdlab2
LAB 2 Github
1- 
git init 
git remote add origin git@github.com:maiyasser21/thirdlab2.git
git branch -M main
git add .
git commit -m "third"
git push -u origin main

2-
git checkout -b dev
git push origin dev
touch file1.txt
git add .
git commit -m "fileupload"
git push origin dev
git checkout -b test
touch test.txt
git add .
git commit -m "test"
git push origin test

3-
git checkout main
git merge dev
git add .
git push origin main

git merge test
git add .
git push origin main

4-
git push origin :dev

git branch -d dev
git push origin :test
git branch -d test

5- 
git stash
git checkout main

6-
git tag -a v1.7 -m "version 1.7"


7-
git push origin v1.7
git push --tags

8-
git tag

9-
remote: git push origin --delete v1.7
local: git tag -d v1.7

10-
touch readme.txt
git add readme.txt
git commit -m "readmeadded"
git push


#image 
![iti](https://user-images.githubusercontent.com/90289910/201142636-e8f2ad55-c682-4346-a0ee-00834971ba72.jpg)
