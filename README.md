<!-- This is a personal reference/cheat sheet. Feel free to share. -->

# initialising via local machine
    mkdir mynewproject
*creates new directory*

    cd mynewproject
    touch > index.html
    touch > app.js
    touch > style.css
    touch > .gitignore

*end of setting up folders*

    git init

*this sets up the .git folder in working directory*

    git config --global user.name 'abeeth'
    git confg --global user.email 'axs@cisi.org'
    git config --global core.autocrlf true

*optional settings*

    git commit -m "this is the first commit"

*this is the first push to staging*

## now go back to github.com

### make new repository without readme or any of the bonus addons *this will take you to the setup page*

## back to terminal

    git remote add origin https://github.com/a3eeth/mynewproject.git

*this links the working directory with the repository in the cloud*

    git remote

*if things went right this should show ```origin```*

    git add .

> with node_modules this might not work - and if .gitignore.txt is being a pain to configure
> in order to remove those files 

    git rm -r --cached node_modules/

*this pushes all changes into staging*

    git commit -m "second commit to cloud"

    git push

# grabbing from an existing project on github

    git clone https://github.com/a3eeth/mynewproject.git

# git branch - used for working parallel

    git branch <branch-name>

*this creates branch locally*

*once necessary changes are made push to remote by*

    git push -u <remote> <branch-name>

*to view the branches*

    git branch

*OR*

    git branch --list

*to delete a branch*

    git branch -d <branch-name>

# document git pull
# document git merge