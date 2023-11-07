just a readme file for testing

Cheatsheet: 
https://www.cs.columbia.edu/~sedwards/classes/2017/1102-spring/Command%20Prompt%20Cheatsheet.pdf
https://education.github.com/git-cheat-sheet-education.pdf


GIT CLONE:
git clone  # puts a copy of the remote repository on our machine

GIT PUSH:
git push  # after we worked on the local version of the repository, we can push those changes to the remote
git push -u origin main  # only for first push
git push  # you can just git push after you setup the -u (upstream flag) on whatever branch you specified (main)

GIT PULL:
git pull  # pulls the latest version of the remote repository to our machine.
        # We use this after we have already cloned a copy of the remote repository to our local machine,
        # because someone else may have updated the remote in the meantime.
        # So we want to make sure we have the most up to date version.

GIT STAGE:
git add .

GIT COMMIT:
git commit –m "a descriptive message"

Unix/Linux Commands
ls - lists available directories for you to cd to
cd directoryName - change current directory to the specified directory
touch fileName - Create a file named fileName
pwd - prints your current directory

Command Prompt(Windows) Commands
dir - lists available directories for you to cd to
cd directoryName - change current directory to the specified directory
echo example > fileName - Creates a file named fileName and writes the string example inside
echo %cd% - prints your current directory
code . - opens an instance of VS Code at your current directory

EXERCISE:
https://github.com/susanwinters214/PizzaAlgoCsharp