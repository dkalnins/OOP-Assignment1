# Part 3 Answers

David Kalnins

## Introduction
Imagine you are working at a game studio, and they want you to help with installing Git. 

## 1.	Write instructions on installing git on a windows system. Making sure to include
### a.	What are the requirements to install Git on a system.
### b.	If you had issues installing Git the workplace, give instructions on who you could you enquire about the installation disruption.

System Requirements: 
Git for Windows requires Windows 7 Service Pack 1 or later. The last version to support Windows Vista and Server 2008 was v2. 37.1. The last version of Git for Windows to support Windows XP and Windows Server 2003 is v2.

Installation Steps:
* Go to the GIT SCM homepage https://git-scm.com/download/win
* Choose the latest Standalone Installer 64 bit version
* Execute the Installer
* Follow these dialog box options
	* Screen 1: click next
	* Screen 2: choose "Notepad++" as the default editor and click next
	* Screen 3: keep the middle option selected "Git fro the command line and also from 3rd-paty software". Click next.
	* Screen 4: keep "Use bundled OpenSSH" selected. click next
	* Screen 5: change to "Use Windows' default console window". Click next
	* Screen 6: do not click any checkboxes, we don't use experimental versions. Click next


Troubleshooting:
* Please contact Helpdesk on 5555-1234 for help, or contact the helpline at this URL (Example only) https://www.atlassian.com/service-desk


## 2.	Do research on some principles/techniques of industry standard best practices creating and working with repositories and branches in Git. 
### a.	List the most important principles/techniques for creating and working with repositories
* Make incremental small changes
* Keep commits atomic
* Develop using branches, not on the main track
* Write descriptive commit messages
* obtain feedback through code reviews
* identify a branching strategy

### b.	List the most important principles/techniques for creating and working with branches
* Clear documentation on what branches should be named
* Understanding what each branch is for, what it should be cloned from and merged back to
* Knowing who is working on which branches
* Strategies for merging branches
* Knowing what fixes and features are included in releases


## 3.	List the steps in a Git workflow that the team should follow when working on projects.
In our studio we will follow GitFlow. This includes the use of the following branches:
* Main - Where release and release candidate versions are stored
* Develop - where main development for the new version is carried out
* Feature - for new features branched from development
* Release - used in preparation for a release. Changes get merged back into master and development
* Hotfix - used to support fixes for important problems. Normlly brances are forked from Main.

Note: Master is renamed to Main for this implementation




