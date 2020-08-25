What is Git?
- Git is an essential version control technology for web developers & programmers
- A version control system allows you to track the history of a collection of files,
- It supports creating different versions of this collection.
- Each version captures a snapshot of the files at a certain point in time & allows you to switch between these version.
- These versions are stored in a specific place (repositories).
- Git is the most popular implementation of a version control system.


Git Commandds
- git --version : Allows to view the version of git
- git init : initializes an empty git repository (repo)
- git add : tracks files (eg git add index.html), git will stage and track this file
- git add . : this command will stage & track all files
- git commit -m '' : records a snapshot of all the files in your directory or all the added files. The -m allows us to add a message of what we have committed. When working with other teams, its important to write messages that make sense to other developers so that they know what the commit added does.
- git remote add origin https://github.com/............. : this commands adds files to your github account
- git push -u origin master : commits to github account.

- Changes can be made to files. Once completed,
  - git add .
  - git commit -m "enter type of change made"
  - git push

- git branch : shows the branch that you are currently working on
- git branch footer: new branch created & we need to switch to that branch
by using git checkout footer command
- once in the master branch, run the command below
- git merge footer : allows the changes made in the footer branch to reflect in the master branch
- git pull : allows you to see if the branch merges are up to date.
  
