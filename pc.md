## Research Questions

Now that you are all set up, it's time to learn a little more about the tools of the trade. Edit this file and answer the following questions. You are going to need to start familiarizing yourself with the [GitHub docs](https://docs.github.com/en). Docs (short for documentation) are the instructions on how to use a language or program. A large part of your job as a developer will be learning how to read and work with documentation. Please reference the GitHub docs when answering the questions below. If you cannot find what you are looking for in the docs, you can always start to practice your Google skills!

1. What is Git?
   A free open-sourced file management system that tracks different file versions.
2. What is the difference between Git and GitHub?
   They're both used to manage code, but Git is local, while GitHub is online.
3. Why do we create a branch?
   To work on code separately from other developers. Branches are independent from other parts of the project.
4. What is the purpose of a Pull Request?
   A pull request updates the local version with the remote version.
5. What is the command you can use to switch between branches? For example you are working on the FIRSTNAME-LASTNAME branch and you want to switch back to main.
   git switch main
6. Explain the difference between `git fetch`, `git merge` and `git pull`. What does each command do?
   git pull brings revisions from the remote version into the local version (combination of both git fetch and git merge). git fetch downloads the data but doesn't integrate it into the local files. git merge combines changes from two branches.
7. What is a merge conflict?
   When git can't automatically resolve differences in code between two commits.
8. How do you resolve a merge conflict?
   Open the file and make any necessary changes. Try to push the corrected file.
