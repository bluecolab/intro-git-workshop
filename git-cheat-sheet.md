Git Cheat Sheet
===============

###### Git Cheat Sheet © 2024 by Leanne Keeley & Sebastian Roman is licensed under Attribution-NonCommercial 4.0 International. To view a copy of this license, visit http://creativecommons.org/licenses/by-nc/4.0/

*Last updated 2024-03-28*

> [!WARNING]
> **Please make sure Git is installed first!**  
> [Here is a guide on how to install Git](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git)

Git terms
---------

__Branch__:  
&nbsp; &nbsp; &nbsp; &nbsp; A separate version of the code, used for testing new features

__Develop (Branch)__:  
&nbsp; &nbsp; &nbsp; &nbsp; Usually the branch that you merge changes to

__Fork__:  
&nbsp; &nbsp; &nbsp; &nbsp; <sub>noun</sub> A copy of a repository  
&nbsp; &nbsp; &nbsp; &nbsp; <sub>verb</sub> To create a copy of a repository

__Head__:  
&nbsp; &nbsp; &nbsp; &nbsp; The most recent commit

__Master/main (Branch)__:  
&nbsp; &nbsp; &nbsp; &nbsp; The main branch of your repository

__Pull request__:  
&nbsp; &nbsp; &nbsp; &nbsp; Ask the owner of a repository to merge your changes into the project

__Remote/Origin/Upstream__:  
&nbsp; &nbsp; &nbsp; &nbsp; These refer to the location of the repository online. This is where changes are pushed to ([github](https://github.com/), [gitlab](https://gitlab.com/), etc.)

__Repository/Repo__:  
&nbsp; &nbsp; &nbsp; &nbsp; A container for your project

__Merge conflict__:  
&nbsp; &nbsp; &nbsp; &nbsp; When there are conflicting changes between the main branch and branch you are working on

__.gitignore__:  
&nbsp; &nbsp; &nbsp; &nbsp;This is a file that contains the names of things you want git to ignore

Git Commands
------------

> [!NOTE]
> **These comands are structured as `git [command] [flags] [arguments]`**  
> Example: `git checkout -b main`   
> In this example, `checkout` is the command, `-b` is the flag, and `main` is the argument

`add [file]`:  
&nbsp; &nbsp; &nbsp; &nbsp; Adds the named file to your git repository

`branch`:  
&nbsp; &nbsp; &nbsp; &nbsp; Shows you the branch you are currently in

`clone https://github.com/[username]/[repository].git`:  
&nbsp; &nbsp; &nbsp; &nbsp; Copies a repository onto your local machine

`checkout [branch or file]`:  
&nbsp; &nbsp; &nbsp; &nbsp; Switch to a different branch, or pull the last committed version of a file

&nbsp; &nbsp; &nbsp; &nbsp; `-b` flag allows you to create a new branch

`commit`:  
&nbsp; &nbsp; &nbsp; &nbsp; Adds a save point with new changes. Descriptive comments made it much easier to understand what change you saved

&nbsp; &nbsp; &nbsp; &nbsp; `-am '[comment]'` flag allows you to add comment without going into a text editor

`fetch`:  
&nbsp; &nbsp; &nbsp; &nbsp; Download copies of all the files in a branch to your local machine

`init`:  
&nbsp; &nbsp; &nbsp; &nbsp; Creates a new git repository

`log`:  
&nbsp; &nbsp; &nbsp; &nbsp; Show you all the commits, merges, etc. to the current branch

`merge [branch]`:  
&nbsp; &nbsp; &nbsp; &nbsp; Combines the changes from the current branch into the named branch

`pull`:  
&nbsp; &nbsp; &nbsp; &nbsp; Same as fetch, but also merges those changes into the current branch

`push`:  
&nbsp; &nbsp; &nbsp; &nbsp; Send committed changes to the origin (ex. github)

`rebase [branch]`:  
&nbsp; &nbsp; &nbsp; &nbsp; Update the current branch to the status of the named branch

`reset old-commit / revert head`:  
&nbsp; &nbsp; &nbsp; &nbsp; Undoes commits, takes your project back to a previous state

`stash`:  
&nbsp; &nbsp; &nbsp; &nbsp; Stashes and removes uncommitted changes

`stash pop`:  
&nbsp; &nbsp; &nbsp; &nbsp; Reapply changes previously stashed

`status`:  
&nbsp; &nbsp; &nbsp; &nbsp; Shows you the current status of your repository. Use this often!
