# GitProcess
We will talk about our git process and how to use git, with github. 

Our Process follows a typical git-process. 

We have a master branch aptly named "Master"

and we have a develop branch named, you guessed it "Develop"


##A few Scenarios

Consider the following ticket:

**Ticket Number** - _AP-100_

**Accecptance Critera** 

1. Create two new files named **1.html** and **2.html**                   

2. File **1.html** should contain the following text: 
  1. "This is file 1"

3. File **2.html** should contain the following text: 
  1. "This is file 2"

###How to git command

1. Go to develop.
  1. `git checkout develop`

2. Get the latest version of develop 
  1. `git pull`
    1. git pull will actually replace your working directory with the most updated version of the branch you are in. 

3. Create a new branch off of develop using the name of the ticket as your branch name. 
  1. `git checkout -b AP-100`

4. Edit your files. 

5. Add your files to staging to be pushed out to origin
  1. `git add 1.html`
  2. You can also add all files edited quickly with `git add *`
