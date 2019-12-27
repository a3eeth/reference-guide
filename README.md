<!-- This is a personal reference/cheat sheet. Feel free to share. -->

# initialising via local machine
    mkdir mynewproject
*creates new directory*

    cd mynewproject
    touch > index.html
    touch > app.js
    touch > style.css
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

*this pushes all changes into staging*

    git commit -m "second commit to cloud"

    git push
