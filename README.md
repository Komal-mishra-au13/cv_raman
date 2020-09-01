# demo

## This is description
step1. create a github repo
 To create a new repo we have to follow these steps:-
 i)In github account click on "+" -> click on "New repository"
 ii)Write the name in "Repository name" as cv_raman box and click on "create repository"
A new repository created called "cv_raman"
Step 2.  Clone it as a folder as first_repo eg git clone <urL> first_repo
i)git init (command will initialize empty git repository in local directory)
ii)git clone https://github.com/komal-mishra-au13/cv_raman.git first_repo
(it will create First_repo empty directory in local directory)
iii) cd first_repo ( going inside first_repo folder)
iv) touch README.md (creting a file inside first_repo)
v)code README.md ( open README file in VS)
adding title of that file using # demo. 
vi)git add . (to add README file for tracked)
vii) git commit -m "README file" ( commit readme file)
viii)git push ( pushing README.md file my repo cv_raman)
ix) cd.. ( coming outside from first_repo)
x)git clone https://github.com/komal-mishra-au13/cv_raman.git second_repo ( create second_repo repository in local directory)
xii)cd second_repo (going inside second_repo)
xiii)ls (listing files)
xiv) code README.md (open README.md file in VS)
xv)git add . 
xvi)git commit -m "README file changed"
xvii)git push
xviii)cd ..
xiv)cd first_repo
xv)code README.md
xvi)git pull