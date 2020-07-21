# Git: Version Control System :rocket:
Git is a version control system for managing your code as a **'repository'** . You can collaborate and write your code with your team without blocking one another.

## TL;DR
[Use this video as referense](https://www.youtube.com/watch?v=HkdAHXoRtos) and [this repository](https://github.com/RazionAsukaru/example)

## Installing Git  - Windows
You can install git from [here](https://git-scm.com/downloads). Click next until you are asked for adjusting your path environment. choose **"Run Git from the windows Command Prompt"** click next and choose **'Checkout Windows-style, commit Unix-style line endings'** until installation finished.

## Initiate Git Repository
### Prequisite
- I REALLY RECOMMEND to organize your project first thing first in your directory, seperate backend business logic (query and setting to db) anb frontend (webapp and templates).
- I recomend using vscode as your code editor, as it is a powerful tool for writing your code with many great extionsion to help you out, like built in git source control. Steps below can be followed from your terminal (cmd / powershell).
### Git Init
- Go to your project directory and open it on vscode.
- Open vscode terminal with Ctrl + `. Make sure your default terminal is cmd .
- copy this command in terminal ```git init```

Now you can see source control is active and giving you marks in vscode.

## First Commit
- add all your code to stages with ```git add .``` 
- commit your stage ```git commit -m "Initial Commit [you can add another message here]"```

You can add file 1 by one or by directory i.e. : ```git add ./webapp/index.html``` or ```git add ./webapp```

## Push Your Code to Remote Repository
- Login to your github account.
- Create new Repository with your project name as a Private Repository.
- Go back to vscode and run this command. Dont forget to chage git url wit your project url. ```git remote add origin git@github.com:RazionAsukaru/example.git && git push origin master```

## Congratulation!!
Now You are using git and your project has a remote repository.

## Good thing to learn after this
- Adding ssh-key to github
- Node Package Manager