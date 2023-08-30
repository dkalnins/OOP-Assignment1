# Part 2 Answers

David Kalnins

## 1.	List three major version control for software engineering.

* Visual Source Safe
* Mercurial
* Subversion

## 2.	What are the main advantages to using Git in your software development, and how is it useful for game developers.
* Allows multiple developers to work on the same project
* Brances of the code base can be created to enable new system development
* Can allow a faster release cycle for new features and bug fixes

## 3.	Define the following terms in relation to Git. Branch, Pull, Push, repository, working copy, merge
* branch - an independent line of development changes that developers can commit code against
* pull - used to copy sourcecode from one repository to another
* repository - A storage location that tracks changes made to a git project
* working copy - a local repository on a developer's machine that holds the files they are currently working on. this is distinct from the the .git folder
* merge - a git command used to incorporate changes from another repository into another repository.

## 4.	If you are working at a company, which of their policies and procedures might relate to using version control systems such as Git.
* Backup policy
* Version Control policy
* Security Policy
* WHS
## 5.	Merge conflicts can occur while using git. List merge tools or diff tools you can use to help you merge and deal with conflicts.
* meld
* opendiff
* kdiff3
* tkdiff
* xxdiff
* emerge
## 6.	In a merged source code file, how does Git let you know there is a conflict?
git uses visual markers within the file to show which parts of the source code conflict

	<<<<<<< <branch name>
	conflicting changes on the branch we are merging into
	=======
	changes in the brance we are merging from
	>>>>>>> 

## 7.	What are the steps you can take to resolve Git conflicts?
TODO

## 8.	What does git revert do, and how can you use it?
TODO

## 9.	What does git reset do, and how can you use it? 
TODO

## 10.	What is the difference between git revert and git reset?
TODO

## 11.	True or False: It is okay to commit broken code to the main branch.
False

## 12.	True or False: You should commit related changes. For example, fixing two different bugs should produce two separate commits.
True

## 13.	Describe what is DevOps, how is it useful for game developers?
Development operations support the actual process of software development and release. This includes tools to automate build cycles, automate testing, as well as deployment of software.

## 14.	List what tools can be used with DevOps. Give a brief description of each one. (at least 3)
* Jenkins - automate build, testing, and continuous integration
* Git - Software version control management software, used for manging source control brances, etc.
* Docker - OS virualization that can be used for, among other things, creating disposable test environments for software

## 15.	What is CI/CD and how can it be used to automate the game development process?
CI (Continuous Integration) refers to the process of automatically building and testing software. Its typically, but not necessarily, accompanied by use of version control software which developers make frequent commits into. This would allow for something like the a nightly build and test run, for instance.

CD (Continuous Deployment) Automatically shipping applications to production environments.

CI and CD may be combined in the game development environment to allow for, for instance, a nighly build of current features to be: (a) built / compiled / packaged, (b) Tested using automted testing, and (c) Automatically shipped or deployed to customers. Customers would more likely be a group of alpha or beta testers rather than production users in this particular example.

