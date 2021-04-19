# myapp
# added files to a new project using git CLI

INSTALLING GIT using CLI

Linux(debian)
$ sudo apt-get install git

Linux(Fedora)
$ sudo yum install git

Mac
http://git-scm.com/download/mac

Windows
http://git-scm.com/download/win

// create a project
mkdir myapp
cd myapp
touch index.html
touch app.js

//add or track file(s) to index
$ git add index.html 
$ git add app.js  
$ git add .  //adds all file changes

// initialize local git repository
$ git init 
$ git config –global user.name ‘adeyadavid’
$ git config –global user.email ‘adeyadavid@gmail.com’

// check status of working tree or see changes since last commit
$ git status 
$ git rm –cached index.html
$ git add *.html
$ git rm –cached app.js 

// commit(save) changes in index
$ git commit -m ‘my first app’

// send commit’s to github I.e from local storage to virtual
$ git remote add origin <copy paste Http url for repository created here>
$git remote
$ git push -u origin master
$ git push

// pull latest from remote repository
$ git pull 
// clone repository into a new directory
$ git clone <copy paste git url to be cloned here>
 
