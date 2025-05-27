# Git cheatsheet

> [Installation guide](git-scm.com)

## CLI commands
1. To check version of git installed 
```
git --version 

```
2. To set your user 
```
git config  --global user.name "Sahasrad"
```
3. To set your email
```
git config  --global user.email "sahasrad.tech@gmail.com"
```
4. To check if data is successfully inserted into Git
```
git config  user.name
git config  user.email

```

5. To prepare particular file to be versioned (moving file from working directory to staging area)
```
git add <file_name>
```

6. To transfer file from staging area to local repository
```
git commit
git commit -m "<sample_message>"
```

7. To start a Git repository in a particular folder
```
git init
```

8. To see current status of of working directory and staging area
```
git status
```

9. To view history
```
git log
git log --oneline [displays SHA1 value of commit]
```

10. To view specialised info about commit (by default, last commit)
```
git show
git show <commitHash>
```

11. If you want to temporarily go back to a different commit,
```
git checkout <commitHash>
```

12. To rollback/reset a Git commit by moving branch pointer
```
git reset <SHA1value>
git reset current~<relative_number_before_current_tag>
```

13. To revert a Git commit by adding a new commit at the end of the chain to "cancel" changes
```
git revert HEAD
```

14. To create a remote repository and connect to local repository
```
git remote add origin <HTTPS_web_url_of_remote_repository>
git branch -M main
git push -u origin main
```

15. To clone remote repositories to local machine
```
git clone <HTTPS_web_url_of_remote_repository>

```



