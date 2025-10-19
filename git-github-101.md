
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

### Development
At Blue CoLab, we work in a collaborative environment. Here are suggestions on how to use Git and GitHub to help us:

<TBD>


