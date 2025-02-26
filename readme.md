step:1  PS C:\Users\umesh\OneDrive\Desktop\Gits>   
       git --version
       git version 2.45.1.windows.1


step:2 git config --global user.name "Your Name"
       git config --global user.email "your.email@example.com"



<!-- PS C:\Users\umesh\OneDrive\Desktop\Gits>  git config --global user.name
Umesh Kumar Verma
PS C:\Users\umesh\OneDrive\Desktop\Gits>  git config --global user.email
umeshkumarhzb145@gmail.com
PS C:\Users\umesh\OneDrive\Desktop\Gits> -->

step:3 

step:4 track file
        git add <fileName>  or add all the use
        git add .



step 1 install git
2   check virsion
3   git create name and email
4   create new rep in github
5   copy origin link on github
6   


PS C:\Users\umesh\OneDrive\Desktop\Gits> git init
Reinitialized existing Git repository in C:/Users/umesh/OneDrive/Desktop/Gits/.git/
PS C:\Users\umesh\OneDrive\Desktop\Gits> git add .
PS C:\Users\umesh\OneDrive\Desktop\Gits> git commit -m "test"
[main 6b84ede] test
 1 file changed, 9 insertions(+)
PS C:\Users\umesh\OneDrive\Desktop\Gits> git remote add origin https://github.com/umesh9608/Gits.git
PS C:\Users\umesh\OneDrive\Desktop\Gits> git push -u origin main   

second time only use PS C:\Users\umesh\OneDrive\Desktop\Gits> git push 


Counting objects: 100% (5/5), done.
PS C:\Users\umesh\OneDrive\Desktop\Gits> git branch
* main
PS C:\Users\umesh\OneDrive\Desktop\Gits> git branch test
PS C:\Users\umesh\OneDrive\Desktop\Gits> git branch     
* main
  test
PS C:\Users\umesh\OneDrive\Desktop\Gits> git switch test
M       index.html
M       readme.md
Switched to branch 'test'
PS C:\Users\umesh\OneDrive\Desktop\Gits> git branch     
  main
* test
PS C:\Users\umesh\OneDrive\Desktop\Gits> git checkout main
M       index.html
M       readme.md
Switched to branch 'main'
Your branch is up to date with 'origin/main'.
PS C:\Users\umesh\OneDrive\Desktop\Gits> git branch       
* main
  test