# bikesandtrikes.github.io
Collaboration project between Andrea, Guy, and Joe

***To set up locally***

1. Create a local folder
2. Open with code editor
3. In command line type `git clone https://github.com/jmwalsh101/bikesandtrikes.github.io.git`
4. The repository should download
5. Type in command line `git init`
6. Type in command line ` git commit -m "initial commit"
6. Connect to the repository by typing in command line `git remote add origin https://github.com/jmwalsh101/bikesandtrikes.github.io.git`
7. Your repository is now linked to the GitHub one
8. Rebase to make sure changes are correct by typing in command line `git pull --rebase origin master`
9. Test that everything is working by adding a local .text file with your name
10. Push to the GitHub repository by typing in command line `git push -u origin master`

***Rebasing***
Before making any local changes, creating a commit, or pushing a review, make sure you rebase to the latest changes:

1. Type in command line `git pull --rebase origin master`
2. The latest changes on the GitHub repository will be updated locally
