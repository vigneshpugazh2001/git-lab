Answer 1: git version 2.28.0.windows.1


Answer 2:
 PS C:\Users\vigne\cs2400\git-lab> git config --list
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
credential.helper=manager
user.name=Vignesh Pugazhenthi
user.email=vp995218@ohio.edu

Answer 3: took me to another website

file:///C:/Program%20Files/Git/mingw64/share/doc/git-doc/git-add.html

Answer 4: 
PS C:\Users\vigne\cs2400\git-lab> git status
On branch master

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
        new file:   README.md

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        answers.md

Answer 5: 
PS C:\Users\vigne\cs2400\git-lab> git status
On branch master

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
        new file:   README.md

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        answers.md

Answer 6:
PS C:\Users\vigne\cs2400\git-lab> git status
On branch master

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
        new file:   README.md

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        answers.md

Answer 7:
PS C:\Users\vigne\cs2400\git-lab> git status
On branch master
Untracked files:
  (use "git add <file>..." to include in what will be committed)
        answers.md

nothing added to commit but untracked files present (use "git add" to track)

Answer 8: 

PS C:\Users\vigne\cs2400\git-lab> git log
commit cab6448a550e98c58c156ff5865527312b803a28 (HEAD -> master)
Author: Vignesh Pugazhenthi <vp995218@ohio.edu>
Date:   Tue Sep 1 16:47:31 2020 -0400

    Initial commit

Answer 9:
PS C:\Users\vigne\cs2400\git-lab> git push -u origin master
Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Delta compression using up to 8 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 271 bytes | 271.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/vigneshpugazh2001/git-lab.git
 * [new branch]      master -> master
Branch 'master' set up to track remote branch 'master' from 'origin'.

Answer 10:

I recorded my answers within the answers.md file

Answer 11:

PS C:\Users\vigne\cs2400\git-lab> git push
To https://github.com/vigneshpugazh2001/git-lab.git
 ! [rejected]        master -> master (fetch first)
error: failed to push some refs to 'https://github.com/vigneshpugazh2001/git-lab.git'
hint: Updates were rejected because the remote contains work that you do
hint: not have locally. This is usually caused by another repository pushing
hint: to the same ref. You may want to first integrate the remote changes
hint: (e.g., 'git pull ...') before pushing again.
hint: See the 'Note about fast-forwards' in 'git push --help' for details.

Answer 12:

PS C:\Users\vigne\cs2400\git-lab> git pull
remote: Enumerating objects: 5, done.
remote: Counting objects: 100% (5/5), done.
remote: Compressing objects: 100% (3/3), done.
remote: Total 3 (delta 1), reused 0 (delta 0), pack-reused 0
Unpacking objects: 100% (3/3), 694 bytes | 77.00 KiB/s, done.
From https://github.com/vigneshpugazh2001/git-lab
   175bb98..3428c4c  master     -> origin/master
Updating 175bb98..3428c4c
Fast-forward
 README.md | 2 +-
 1 file changed, 1 insertion(+), 1 deletion(-)
