
## Downloading
Downloading Git: https://git-scm.com/
(Recommend) VS Code: https://code.visualstudio.com/
(Optional) Downloading GitHub CLI: https://github.com/cli/cli/releases/

## Terms
See the: [git-cheat-sheet](./git-cheat-sheet.md) - here's a quick intro to Git terms and commands.

## Development Process

### Setup

You need to first set up Git on your machine with a username and email. You only do this once. 
```cmd
git config --global user.name "<your name>"
git config --global user.email "<your email>"
```

### Getting Started
To clone (copy) your first repo (project), open a terminal/command line. Any terminal should work, but Git Bash (installed with Git) works best.

Generally when you first open a terminal window it will open in the home directory (where your personal files are stored). Change the current working directory to the location where you want the project. 

For example if you have a "BlueCoLab_Projects" folder in your "Documents" folder you would first enter:
```
cd Documents/BlueCoLab_Projects
```

Then to clone it, replace the <url> of the following command with the URL of the repo:
```
git clone <url>
```

For example, if you wanted to clone this repo you would do:
```
git clone https://github.com/bluecolab/intro-git-workshop
```

If the repo you clone is private, you may be prompted to log in. Follow the instructions carefully to log into your GitHub account. 

Now you can start working on the project. If you installed VS Code, enter the following command to open the project. Replace <name of reoo> with name of GitHub repo:
```
code <name of reoo> 
```

In this case it would be:
```
code intro-git-workshop
```

Once you're set up the easiest terminal to use is generally the one built into the code editor you are using. For example in VS Code you can open a new terminal via Terminal > New Terminal. 

### VS Code Integration:
If you would like to use VS Code's UI for the following steps, please follow this set up guide: https://code.visualstudio.com/docs/sourcecontrol/github#_getting-started-with-github-pull-requests-and-issues (don't clone yet, just log in to GitHub).  

### GH CLI Integration:
If you want to use GitHub's CLI for following steps related to pull request creation, follow this guide: https://docs.github.com/en/github-cli/github-cli/quickstart#some-useful-commands

To set up VS Code as the default editor for GH CLI follow: https://docs.github.com/en/get-started/git-basics/associating-text-editors-with-git for your OS.

### Development
At Blue CoLab, we work in a collaborative environment. Here are suggestions on how to use Git and GitHub to help us. For these steps remember to run the terminal from the directory of your project. (`Documents/BlueCoLab_Projects/intro-git-workshop` for example)

#### Starting 

When starting new work make sure you are on the `main` branch and have the latest changes. You can run the following commands to due so:

```
git checkout main; git pull origin main
```

Create a new branch, the branch name should be relevant to the changes you're planning to make. Replace `<new-branch-name>` with the name of your branch.

```
git branch <new-branch-name>
```

Now switch to that branch with:

```
git checkout <new-branch-name>
```
#### Committing Changes

Once you're ready to commit the changes do the following command. The commit message should be short (less then 50 characters). You can add more details (less then 72 characters)

```
git commit -am "<replace this with your message>"  -m "<Optional details>"
```

#### Pushing your changes

To push your changes to GitHub do the following for the first time:
```
git push --set-upstream origin <new-branch-name>
```

If you do that once, next time you add anything to this branch it should be a simple:
```
git push
```

#### Creating a pull request

There are three ways to create a pull request:

**Via VS Code:**
Please follow: https://code.visualstudio.com/docs/sourcecontrol/github#_creating-pull-requests

**Via GitHub CLI**
To create a new PR:
```
gh pr create
```

When it asks "Where should we push the '<new-branch-name>' branch?




