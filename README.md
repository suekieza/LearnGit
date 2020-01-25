# Learning the git

## Link to tutorial
#### Git
<a href="https://www.youtube.com/watch?v=SWYqp7iY_Tc" target="_blank"><img src="https://www.youtube.com/watch?v=SWYqp7iY_Tc" 
alt="IMAGE ALT TEXT HERE" width="240" height="180" border="10" /></a>

#### Git fix Mistakes
<a href="https://www.youtube.com/watch?v=FdZecVxzJbk" target="_blank"><img src="https://www.youtube.com/watch?v=FdZecVxzJbk" 
alt="IMAGE ALT TEXT HERE" width="240" height="180" border="10" /></a>

#### Markdown
https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet

### Basic commands
```
$git init
$git add <file(s)>
$git status
$git commit
$git push
$git pull
$git clone
$git config --global user.name(email)
```

### Commit comments section
```
i for insert to type
esc to get out again
:wq to commit
```
####
```
$git commit -m "What changed comment"
$git remote  //check if there is a remote repo
$git remote add origin https://github.com/suekieza/LearnGit.git
$git push -u origin master
$git clone https://github.com/suekieza/LearnGit.git
$git pull
```
### Fixing Mistakes

```
$git restore <file(s)> //if file is in origin repo
$git checkout <file(s)> //if file is only in stage local
$git commit --amend -m "Change masg in commitlog" //previous commit(changes commit tag)
$git commit cherry-pick

$git reset --soft //keeps work in stage
$git reset --mixed //keeps work in folder structures
$git reset --hard //Removes all work

$git clean -df //directories and files

$git reflog //life saver see history
$git revert //fix commits without changing history
$git diff //see changes between to commits or branches
```
