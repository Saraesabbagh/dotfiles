# dotfiles
## setup

### Step 1- clone the repo
````
git clone "https://github.com/Saraesabbagh/dotfiles.git" ~/.dotfiles
````
### Step 2- symbolic link the profile
To ensure that your .zprofile is used from your dotfiles repository, you can create a symbolic link from your home directory to the file in the repository

````
ln -sf ~/.dotfiles/.zprofile ~/.zprofile
````
### Step 3- Run the Brewfile

````
cd ~/.dotfiles && brew bundle
````
