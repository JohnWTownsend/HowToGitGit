# HowToGitGit
## A Beginner's Guide to Git

### Aim to answer/accomplish these questions/tasks.
- [ ] What is Git?
- [ ] Why use Git?
- [ ] What is GitHub?
- [ ] Let's make a repo
- [ ] Let's clone that repo
- [ ] Let's add some files and make a commit
- [ ] Let's branch
- [ ] Let's merge that branch back to master
- [ ] Let's show how I can pull those changes on another computer
- [ ] Some useful commands
- [ ] Let's review



## What is Git?

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;  Git is a source control system that allows for historical snapshotting of files and sharing of those files amongst one or more people. Basically it's Google Drive with the ability to snapshot your file changes (but with so, so much more). This allows you to better keep track of changes in a filebase, give yourself access to your files from any machine with access to the internet, and the ability to implement new features to a repository without stepping on your fellow collaborator's toes. Also, Git was created by Linus Torvalds in 2005 for development of the Linux kernel, so there is your ethos appeal.

- [X] What is Git?



## Why use Git?

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;  It will make your life as a developer (or just user of files) easier. Sure you have to learn some stuff, but once you do, you will have the ability to control your codebase in a centralized, backed up, and efficent way. On top of that, knowledge of git increases your employability. Every real world developer position you will find will utilize some form of source control. If they don't, I would encourage you to seek opportunities elsewhere. Haven't convinced you yet? GIT IS FREE! and there are tons of free git hosting services.


&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; While git is awesome, it isn't the only Version Control System out there. Some other ones include Apache Subversion (SVN) and Mercurial, or Microsoft's Team Foundation Version Control. I don't know much about these, but as far as popularity via Google search goes, Git reigns supreme.

![gitmetrics](gitMetrics.png)


- [X] Why use Git?

## What is GitHub?

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Well now that we have an idea of what Git is, we need to talk about git hosting platforms. Git hosting platforms are what make Git as a technology available on the web. Without some sort of centralized server/hosting platform, Git would only give you the ability to snapshot and divide your filebase locally. All of the sharing capabilities and bells and whistles come from a hosting platform. Github is among the most popular of these platforms. Github currently hosts more than 28 million users, more than 85 million repositories, and is home to many prestigious open source projects. 

![prestigiousProjects](gitHubProjects.png)

- [X] What is GitHub?

# LIVE DEMO

## Let's Make a Repository! 

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; A repository is just the directory that has all of your files you would like to version control. It is easiest to create a new one from GitHub online.

- [X] Let's make a repo

## Let's Clone it! 
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Cloning is essentially just like downloading a repo. It takes the code from the server and makes a copy on your own machine. The special thing about cloning is that you are able to send changes back to the server more easily and elegantly.

Most easily done from GitHub online or GitHub Desktop

If we ever need to update our local version of the repo, we do so using a **pull**.

  Commands: <br/>
  `git pull // get latest version of current branch from server`<br/>

- [X] Let's clone that repo

## Let's add some files and commit!
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Once you have cloned your repository, you can now CRUD (create, read, update, delete). Once you have flung some CRUD, your next goal is to get it back out to the server! Since the changes we made are all local, we must do a commit and push. The "commit" portion is just saving all the operations you have done locally, this allows you to organize your changes as well, by putting changes in respective commits. The "push" portion is what actually sends your changes to the server (GitHub).

  Can easily do this on GitHub Online or GitHub Desktop
  
  To complete this from the command line we:<br/>
    `git add [filename]            // Add file to the commit`<br/>
    `git commit -m [commitMessage] // Commit our changes with a message, without opening VIM`<br/>
    `git push                      // Send this commit to the remote branch (at this point our branch is just master)`<br/>

- [X] Let's add some files and make a commit

## Branching!
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Up until this point, we have only been making changes on 1 branch, the master branch. Generally when working features, we make branches off of our main codebase (master). In these _branches_ we can make many commits and pushes but never change our main, working codebase (master). 

There are many ways to work with branches in GitHub Online and Desktop, but most of the time, the command line is the most useful.

  Commands:<br/>
  `git branch                          // lists all branches`<br/>
  `git checkout [nameOfBranch]         // switches to the branch specified`<br/>
  `git checkout -b [nameOfNewBranch]   // creates a new branch with the name specified and switches to it`<br/>
  `git branch -D [nameOfBranch]        // deletes the branch specified`<br/>

- [X] Let's branch

When we are convinced that we have completed a feature, we want to get our changes from our branch into master. We do this either by making a **merge** or a **pull request**. These two methods basically take all of the files we have changed in our branch, and seemlessly add our changes to the master branch. **Pull requests** are specific to GitHub and allow you to set some more rules and reviews before "merging" a branch into master, this is especially useful when using Git in a team.

  Commands:<br/>
  `git merge [branchName]    // merges the code from the specified branch into the current branch`<br/>
  
- [X] Let's merge that branch back to master


## Collaboration!

- [X] Let's show how I can pull those changes on another computer



## Useful commands


- [X] Some useful commands

## Review

- [X] Let's review


## Resources

[Markdown Cheatsheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)<br/>
I learned how to make this readme [here](https://help.github.com/articles/basic-writing-and-formatting-syntax/#links).<br/>
