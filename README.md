# caldervalleyscouts
Calder Valley Scouts Group website and web project

Update this readme with the steps to get set up:
# caldervalleyscouts
Calder Valley Scouts Group website and web project

# set up and install on mac os

## You will need
* a text editor: Sublime Text is free: https://www.sublimetext.com/3
* a git GUI: Gitkraken is free: https://www.gitkraken.com/
* a github account

## install the software
* open terminal
* install homebrew by pasting
``mkdir homebrew && curl -L https://github.com/Homebrew/brew/tarball/master | tar xz --strip 1 -C homebrew``
into terminal
* install hugo by typing
``brew install hugo``
into terminal

## clone the repo
* open terminal
* git clone the Scouts repo by typing
``git clone git@github.com:limograf/caldervalleyscouts.git ``
* change directory into the repo by typing
`` cd caldervalleyscouts``
* serve the website locally by typing
``hugo serve``
* look at your local website in your browser

## commit your changes
* In Gitkraken, initialise Gitflow: https://support.gitkraken.com/git-workflows-and-extensions/git-flow/
* Switch to develop branch
* (make your changes in your text editor)
* In Gitkraken, click on the files you want to 'stage'
* write a short message explaining your changes
* click the Green commit button
* click the Push button

## edit the content
* open the folder in Sublime text
* find the page in the folders
* edit it using Markdown https://www.markdownguide.org/
* save your changes and commit them to develop

## edit the code
* read the code carefully - it has lots of comments and help
* look up how to build your feature in the Hugo docs https://gohugo.io/documentation/
* test your changes on your local install
* when it is working, commit them to a feature branch https://support.gitkraken.com/git-workflows-and-extensions/git-flow/