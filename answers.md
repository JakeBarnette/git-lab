Answer 1)>>
git version 2.31.1.windows.1

Answer 2)>>
diff.astextplain.textconv=astextplain
filter.lfs.clean=git-lfs clean -- %f
filter.lfs.smudge=git-lfs smudge -- %f
filter.lfs.process=git-lfs filter-process
filter.lfs.required=true
http.sslbackend=openssl
http.sslcainfo=C:/Program Files/Git/mingw64/ssl/certs/ca-bundle.crt
core.autocrlf=true
core.fscache=true
core.symlinks=false
pull.rebase=false
credential.helper=manager-core
credential.https://dev.azure.com.usehttppath=true
init.defaultbranch=master
core.editor="C:\Users\ROD\AppData\Local\Programs\Microsoft VS Code\Code.exe" --wait
user.name=Jake Barnette
user.email=jb172617@ohio.edu

Answer 3)>>
The git add --help command redirected me to a website on the commands and description of the git add command

Answer 4)>>
 PS C:\Users\ROD\Desktop\CS2400-Lab\git-lab> git status    
On branch master

No commits yet

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        README.md
        answers.md

nothing added to commit but untracked files present (use "git add" to track)

Answer 5)>>
PS C:\Users\ROD\Desktop\CS2400-Lab\git-lab> git status    
On branch master

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
        new file:   README.md

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        answers.md

Ansswer 6)>>
PS C:\Users\ROD\Desktop\CS2400-Lab\git-lab> git status    
On branch master

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
        new file:   README.md
        new file:   answers.md

Answer 7)>>
PS C:\Users\ROD\Desktop\CS2400-Lab\git-lab> git status    
On branch master
nothing to commit, working tree clean

Answer 8)>>
PS C:\Users\ROD\Desktop\CS2400-Lab\git-lab> git log       
commit a06e38edd30d7651b2ce3485230270978d503ee6 (HEAD -> master)
Author: Jake Barnette <jb172617@ohio.edu>
Date:   Fri May 14 12:19:00 2021 -0400

    Initial commit

Answer 9)>>
PS C:\Users\ROD\Desktop\CS2400-Lab\git-lab> git status    
On branch main
Your branch is up to date with 'origin/main'.

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   README.md
        modified:   answers.md

no changes added to commit (use "git add" and/or "git commit -a")

Answer 10)>>
nothing happened to my local copy when i added a commit through github

Answer 11)>>
it failed to push and gave me a bunch of errors and hints 

Answer 12)>>
When i used the pull command it updated my local copy of README.md to the copy that is located on github

Answer 13)>>
PS C:\Users\ROD\Desktop\CS2400-Lab\git-lab-2> gci



Mode                 LastWriteTime         Length Name     
----                 -------------         ------ ----     
-a----         5/14/2021  12:47 PM            302 .gitign  
                                                  ore      
-a----         5/14/2021  12:47 PM             11 README.  
                                                  md       


