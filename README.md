# dotfiles
## setup

### Step 1- clone the repo
````
git clone "https://github.com/Saraesabbagh/dotfiles.git" ~/.dotfiles
````
### Step 2- symlink the profile

````
ln -sf ~/.dotfiles/.zprofile ~/.zprofile
````
### Step 3- Run the Brewfile

````
cd ~/.dotfiles && brew bundle
````
