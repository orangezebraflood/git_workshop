# Git Workshop

# What Is Git?

  - git is a version control system

# What is Version Control?

  - We have all made a mistake when writing code and wanted to go back
  - Version control systems allows us to do that
  - Also allows for better collaboration

# What Is Github

  - Where you make your code available for others
  - Youtube but for git instead of videos
  - Provides features for collaboration, testing and much more
    - Some will be cover later in this workshop
  - Alternatives
    - Gitlab, Bitbucket, etc

# Installing git

go to [https://git-scm.com/downloads](https://git-scm.com/downloads)
  - Windows
  - Mac
  - Linux

# The Terminal

- Windows 
  - just open git bash
    - Unless you know powershell

- Mac
  -Terminal

- Linux
  - You probably know

## Why

- Often the fastest way to get things done
- Find out what the GUI is doing under the hood
- Think of it as a more picky Google assistant

# Creating A Repo

  - `mkdir git_workshop`
  - `cd git_workshop`
  - `ls -a`
    - The -a is for all
  - ` git init `
  - `ls -a`
  - You will now see a `.git` file
    - This is your local repository
      - It holds all the version control data for git

# Adding A Change

  - In the git_workshop directory lets create a file
    - `touch README.md`
  - Now we need to tell git to start track add this change README.md
    - `git add README.md`

# Committing A Change

  - Now that git has tracked the creation of README.md lets **commit** it
    - Commits are similar to checkpoints in a video game
    - using `git commit` we can commit this change

# Commit Messages

 - Message explaining what changed since the last commit and why
    - Lets just make our git message something like
    `added empty README file`
    - To do this we run `git commit -m "added empty README file"`
    - Often commit messages are one line
      - An additional `-m` flag allows for adding more details

# Lets Put It On Github
>  TODO: add screen shots <12-10-20 Gavin Jaeger-Freeborn>
- Screen shots will be added later


# Pushing To The Git Repository
- Using github as your remote repo
`git remote add origin 'https://github.com/<YourGithubAccount>/<RepositoryName>.git'`

- Then we **push** our changes to github
`git push -u origin master`
or
`git push --set-upstream origin master`

- Now lets check on the repository
  - Refresh the github page and it should now show your README.md

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
- In the top right you will see a fork option
  - Click it
  - Now you will have your own version of the notes on this workshop

- Use `git clone https://github.com/<YourGithubAccount>/git_workshop` to get access to your fork

# Lets Create A Pull Request

1. Make a change to the `README.md` file
2. Add, commit, and push this change to your fork
3. Click the green `New` or `New Pull Request` button 
4. Set compare changes across forks
5. Compare your fork and make a pull request
6. Click `create pull request`
7. explain what was changed in your fork 
8. Click the `create pull request` below the text box and you are done

# Self Promo

- Check me out on [Youtube](https://www.youtube.com/channel/UCJetJ7nDNLlEzDLXv7KIo0w?view_as=subscriber)

# More Resources

- [collections of git resources on Github](https://try.github.io/)
- [guides on Github outside of git](https://guides.github.com/)
