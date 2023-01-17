* cd-  (move to previous directory)
my git token :: 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

pali account access token 3002   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

1.  git rm --cached "file name"  (to remove the file from staging area)
2. git rm "file name" (remove both from staging area and hard disk)
3. touch .gitignore
4. touch logs.log (this will ignore all the log file in the staging area)
5. git add "Directory"/\*.txt (add all the txt file in directory and its subdirectories in tje staging area)
6.  
`shellLists the files in your .ssh directory, if they exist
``$ ls -al ~/.ssh
7. ``````to generate a new ssh key
$ ssh-keygen -t ed25519 -C "your_email@example.com"
8. ```shell "to add the ssh key to ssh agent"
$ eval "$(ssh-agent -s)"
> Agent pid 59566

9.  ```shell to add your ssh key to your github account 
$ ssh-add ~/.ssh/id_ed25519
10.  ```shell to copy your ssh key to the clipboard
$ cat ~/.ssh/id_ed25519.pub
 Then select and copy the contents of the id_ed25519.pub file
 displayed in the terminal to your clipboard

11.  touch "filename.ext"  add a new blank file
12. 
13. 
14.  passphrase of ssh key of github : Vaibhav30@

git --version
git status
git init
git config
git add -a
git add .  (adds all the things at once)
git add "file name"
git commit -m "file name" or "what you have modified in the files"
git checkout -f    "matches all files with the previous document"
git log "show all my commits"
git diff "compare  the working area with the staging area"

git rm --cached "file name"  
git commit -a -m "skip the staging area"{
git add is required inititially but it can be skipped after first add;}
git log -p -n   "shows n commits in the log book"

git status -s               (short status)
![[
![[Pasted image 20230112225800.png]]
]
shows modification in working and staged area "in green and red 'm' "

/* log
/* txt
folder/
## .gitignore
![[Pasted image 20230112230715.png]]
create .gitignore
add all the files to be ignored in .gitignore
if u want to force stage the files in .gitignore  
then use  'git add -f "filename" '


### Branches
git branch "newbranchname"
git checkout "newbranch"
git checkout -b "branchname"  (to switch to branch while creating it)
git branch --delete "branchname"



to merge{
move to master
git merge "new branch"  
}

# Github
we need to push our local repo in the remote repo


git remote add origin (linkofrepo).git
git remote remove origin
git push origin master (this pushed the master to the origin i.e my remote repository)
git push origin master --force (this force pushes master to origin)
git  remote -v

git push origin -d "branchname"

git pull origin master      (pull master from origin)




