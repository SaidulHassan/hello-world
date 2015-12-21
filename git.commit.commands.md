tyr@nt ~/GitRepo $ cd hello-world/
tyr@nt ~/GitRepo/hello-world $ git add *
tyr@nt ~/GitRepo/hello-world $ git add .
tyr@nt ~/GitRepo/hello-world $ git commit -m "Commit message"
[master 52ce3db] Commit message
 8 files changed, 113 insertions(+)
 create mode 100644 #my_first_simple_script.py#
 create mode 100644 Terminal.markdown
 create mode 100644 install-git-to-create-and-share-your-own-projects-on-github-repository.pdf
 create mode 100644 lpthw/ex1.py
 create mode 100644 lpthw/ex2.py
 create mode 100644 lpthw/test.txt
 create mode 100644 my_first_simple_script.py
 create mode 100644 my_first_simple_script.pyc
tyr@nt ~/GitRepo/hello-world $ git push origin master
Counting objects: 11, done.
Delta compression using up to 4 threads.
Compressing objects: 100% (9/9), done.
Writing objects: 100% (11/11), 574.46 KiB | 0 bytes/s, done.
Total 11 (delta 0), reused 0 (delta 0)
To git@github.com:SaidulHassan/hello-world.git
   f5cf618..52ce3db  master -> master
tyr@nt ~/GitRepo/hello-world $ html2pdf http://rogerdudler.github.io/git-guide/ "git - the simple guide - no deep shit.pdf"
Loading page (1/2)
Printing pages (2/2)                                               
Done                                                           
tyr@nt ~/GitRepo/hello-world $ git add .
tyr@nt ~/GitRepo/hello-world $ git commit -m "branch test"
[master 5877bdc] branch test
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 git - the simple guide - no deep shit.pdf
tyr@nt ~/GitRepo/hello-world $ git checkout -b branch-20151219
Switched to a new branch 'branch-20151219'
tyr@nt ~/GitRepo/hello-world $ git push origin branch-20151219 
Counting objects: 3, done.
Delta compression using up to 4 threads.
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 199.04 KiB | 0 bytes/s, done.
Total 3 (delta 1), reused 0 (delta 0)
To git@github.com:SaidulHassan/hello-world.git
 * [new branch]      branch-20151219 -> branch-20151219
tyr@nt ~/GitRepo/hello-world $ html2pdf http://readwrite.com/2013/09/30/understanding-github-a-journey-for-beginners-part-1 "GitHub For Beginners- Don't Get Scared, Get Started - ReadWrite.pdf"
Loading page (1/2)
Printing pages (2/2)                                               
Done                                                           
tyr@nt ~/GitRepo/hello-world $ git add "GitHub For Beginners- Don't Get Scared, Get Started - ReadWrite.pdf"
tyr@nt ~/GitRepo/hello-world $ git commit -m "branch-test-continues"
[branch-20151219 eb4247c] branch-test-continues
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 GitHub For Beginners- Don't Get Scared, Get Started - ReadWrite.pdf
tyr@nt ~/GitRepo/hello-world $ git status
On branch branch-20151219
nothing to commit, working directory clean
tyr@nt ~/GitRepo/hello-world $ html2pdf https://www.linux.com/learn/tutorials/796387-beginning-git-and-github-for-linux-users "Beginning Git and Github for Linux Users - Linux.com.pdf"
Loading page (1/2)
Warning: SSL error ignored                                        
Printing pages (2/2)                                               
Done                                                           
tyr@nt ~/GitRepo/hello-world $ 

