What is Git?
- Git is essential version control technology for web developers & programmers
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