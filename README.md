# Learning the git

## Link to tutorial
#### Git
https://www.youtube.com/watch?v=SWYqp7iY_Tc
#### Git fix Mistakes
https://www.youtube.com/watch?v=FdZecVxzJbk
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
```