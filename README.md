## First Push
``` bash
1. git init # initialize git
2. git add <filename> # add file
3. git commit -m "message" # commit message
4. git branch -M main # create main branch
5. git remote add origin <url> # add url origin
6. git push -u origin main # push to main
``` 


## Edit & Push
``` bash
1. git add <filename> # add file
2. git commit -m "message" # commit message
3. git push origin main # push to main
``` 

## Branch
``` bash
git brach # check branch
git branch <branch-name> # create new branch
git switch <branch-name> # change branch
git push -u origin <branch-name> # push code to branch 
```
## Git Collap
``` bash
git fetch origin # fetch remote changes
git switch <branch-name> # change branch
git pull origin <branch-name> # pull code to branch 
```

# Clone Project 
```bash
git clone <url> # clone project in same folder
git clone <url> folder-name # clone project in specific folder
git clone -b <branch-name> <url> # clone specific branch
```


## Flow how to work Githup Team
```bash
- add memeber to git repository
- git clone <url> # clone project in same folder
- git branch <branch-name> # create new branch
- git switch <branch-name> # change branch
- git add <filename> # add file
- git commit -m "message" # commit message
- git push origin <branch-name> # push code to branch 
# wait for merge to main 

## after merge pull code to branch 
- git pull origin main
#  now you can work on new branch


```