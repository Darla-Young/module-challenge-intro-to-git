## Research Questions 

Now that you are all set up, it's time to learn a little more about the tools of the trade. Edit this file and answer the following questions. You are going to need to start familiarizing yourself with the [GitHub docs](https://docs.github.com/en). Docs (short for documentation) are the instructions on how to use a languge or program. A large part of your job as a developer will be learning how to read and work with documentation. Please reference the GitHub docs when answering the questions below. If you cannot find what you are looking for in the docs, you can always start to practice your Google skills!

1. What is Git?
    a system that manages the files on your computer
2. What is the difference between Git and GitHub?
    GitHub is a public directory, Git is local
3. Why do we create a branch?
    so that we don't overwrite working code, and so that we can work individually from others on the team
4. What is the purpose of a Pull Request?
    to get the latest version of the file
5. What is the command you can use to switch between branches? For example you are working on the FIRSTNAME-LASTNAME branch and you want to switch back to main.
    git checkout (without the -b)
6. Explain the difference between `git fetch`, `git merge` and `git pull`. What does each command do?
    git fetch with download the files, but not change your local ones
    git merge will merge the differences after fetching
    git pull will fetch & merge in one
7. What is a merge conflict?
    when two developers have both modified the same line of code in different ways and git cannot determine which to keep
8. How do you resolve a merge conflict?
    open the offending file and make the necessary changes manually.
