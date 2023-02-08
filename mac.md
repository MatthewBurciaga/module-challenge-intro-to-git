## Research Questions 

Now that you are all set up, it's time to learn a little more about the tools of the trade. Edit this file and answer the following questions. You are going to need to start familiarizing yourself with the [GitHub docs](https://docs.github.com/en). Docs (short for documentation) are the instructions on how to use a languge or program. A large part of your job as a developer will be learning how to read and work with documentation. Please reference the GitHub docs when answering the questions below. If you cannot find what you are looking for in the docs, you can always start to practice your Google skills!

1. What is Git?
Git is a version control system, it keeps track of all the changes made to files in a 
directory on your computer.
2. What is the difference between Git and GitHub?
git is a version control system which keeps track of all the changes and github is a 
repository in which you can upload your git changes and edits.
3. Why do we create a branch? 
We create branches because it keeps the changes isolated in a contained area.
4. What is the purpose of a Pull Request?
The purpose of a pull request lets you tell others about the changes you've pushed to a branch 
in a repository.
5. What is the command you can use to switch between branches? For example you are working on FIRST
NAME-LASTNAME branch and you want to switch back to main.
git checkout command.
6. Explain the difference between `git fetch`, `git merge` and `git pull`. What does each command do?
Git fetch is the command that tells the local repository that there are changes available in the remote 
repository without bringing the changes into the local repository. Git merge lets you take the independent 
lines of development created by a git branch and integrate them into a single branch. Git pull is used to 
fetch and download content from a remote repository and imediately update the local repository to match 
that content.
 7. What is a merge conflict?
A merge conflict occurs when competing changes are made to the same line of a file, or when one person 
edits a file and another person deletes the same file.
 8. How do you resolve a merge conflict?
You reslove a merge conflict by going back into the code and making any necessary changes, after editing 
the file we can use the git add a command to stage the new merged content, then create a new commit with 
the git command and then git will create a new merge commit to finalize the merge.
