# first_project

This is my first repository in Git & i am trying to make easier to learn Git for new people .



# GitHub Useful Commands


### Configure username :
``` 					
git config --global user.name "Your_name"
```

### Configure email :
```
git config --global user.email "your_email"
```

### Creating First Repository :
```
git init
```

### Clone your Repository :
```
git clone https://github.com/Amit152116Kumar/first_project
```

### Adding file in git :
```
git add file_name.txt
```

### Adding Multiple files/folders :
```
git add .
```

### Commiting the file in repository :
```
git commit -m "Your message"
```

### View the Git Status :
```
git status
```

### View all commits of Repository :
```
git log
```

### After modifiying file :
```
git add . 	
git commit -m "messeage"
```

### See Difference between saved file and after modification :
```
git diff
```

### Delete file from Repository :
```
git rm file_name.txt
git commit -m "message"
```

### Rename the file :
```
git add new_name.txt
git rm old_name.txt
git commit -m "message"
```
		**OR**
```
git mv old_name.txt new_name.txt
git commit -m "message
```

### Moving a file :
```
git mv old_name .txt folder_name/new_name.txt
git commit -m "message"
```

### Adding remote origin :
```
git remote add origin https://github.com/Amit152116Kumar/first_project
```

### Verfies the remote url :
```
git remote -v
```

### Reset the remote url :
```
git config --unset remote.origin.url
```

### Change the remote origin :
```
git remote set-url origin https://github.com/Amit152116Kumar/first_project
```

### Push the changes to local repository :
```
git push -u origin master
```

### Show all branches in current repository :
```
git branch
```

### Create new branch :
```
git branch [branch-name]
```

### Change the branch to specified branch : 
```
git checkout [branch-name]
```

### Combines the specified branch into the current branch : 
```
git merge [branch]
```

### Deletes the specified branch : 
```
git branch -d [branch-name]
```

### Add remote from original repository in your forked repository:
```
git remote add upstream git://github.com/ORIGINAL-DEV-USERNAME/REPO-YOU-FORKED-FROM.git
git fetch upstream
```

### Updating your fork from original repo to keep update :
```
git pull upstream master
```




								
