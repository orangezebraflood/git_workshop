# Git Workshop

# What Is Git?

  - git is a version control system

# What is Version Control?

  - We have all made a mistake when writing code and wanted to go back.
  - a version control system allows us to do that.
  - it also allows for better collaboration without risking breaking something that your teammate is working on

# What Is Github

  - While git is the underlying tool that we use for version control
  - Github is where you make your code available for others and to store
  - Think of it like a Youtube but for videos instead of git.
  - Github provides lot of feature for collaboration, testing and much more.
    - Some of these features we will cover later in this workshop
  - Alternatives
    - Gitlab, Bitbucket, etc

# Installing git

  - Use git bash on windows
  - on Mac
  - Linux

# Using The Terminal

- For windows you can just open git bash

## Why

- It is often the fastest way to get things done
- Think of it as a more picky Google assistant
- Why are we using the terminal the

# Creating A Repo

  - mkdir git_workshop
  - cd git_workshop
  - `ls -a`
    - the -a is for all
  - ` git init `
  - `ls -a`
  - you will now see a `.git` file
    - This is called your local repository it holds all the version control data that you have tracked so far

# Adding A Change

  - In the git_workshop directory lets create a file
    - `touch README.md`
  - Now we need to tell git to start track add this change README.md
    - `git add README.md`

# Committing A Change

  - Now that git has tracked the creation of README.md lets **commit** it
    - Commits are similar to checkpoints in a video game.
    - using `git commit` we can commit this change

# Commit Messages

 - When committing our code we leave a message explaining what changed since our last commit
    - Lets just make our git message something like
    `added empty README file`
    - to do this we run ` git commit -m "added empty README file"
    - often commit messages are one line
      - you can add details by adding more "-m" flags

# Lets Put It On Github
>  TODO: add screen shots <12-10-20 Gavin Jaeger-Freeborn>
- Screen shots will be added later


# Pushing To The Git Repository
- using github as your remote repo
`git remote add origin 'https://github.com/<YourGithubAccount>/<RepositoryName>.git'

- Then we **push** our changes to github
`git push -u origin master`
or
`git push --set-upstream origin master`

- Now lets check on the repository
  - Refresh the github page and it should now show your README.md file is now there.

# Quick Github Tour

- Issues
- Pull Requests

# Forking

- What is a fork
- Why make a fork?
  - Try messing with the code
  - Creating a pull request


# Lets Fork
- Go to [https://github.com/Gavinok/git_workshop](https://github.com/Gavinok/git_workshop)
- In the top right you will see a fork option.
  - Click it
  - Now you will have your own version of the notes on this workshop

- Use `git clone https://github.com/<YourGithubAccount>/git_workshop` to get access to your fork

# Lets Create A Pull Request

1.  Make a change to the `README.md` file.
2.  Add, commit, and push this change to your fork
3.  You will see a `New Pull Request` button
4.  Set compare changes across forks
5.  Compare your fork and make a pull request
6.  create a pull request with information about what you have changed
7.  Click `create pull request` below the text box and you are done

# Self Promo

- check me out on [Youtube](https://www.youtube.com/channel/UCJetJ7nDNLlEzDLXv7KIo0w?view_as=subscriber)

# More Resources

- [collections of git resources on Github](https://try.github.io/)
- [guides on Github outside of git](https://guides.github.com/)

