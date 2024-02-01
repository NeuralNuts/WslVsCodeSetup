# WslVsCodeSetup

# Installing git & github
```console
sudo apt update && sudo apt upgrade && sudo apt install git && sudo apt install gh
```

# Logging in with github cli
```console
gh auth login
```
Then follow the provided options
* Github.com
* HTTPS
* Login with web browser
* Copy the ont-time code
* Press enter to open the github web page and paste the one-time into it

# Cloning the repo
The repo will be cloned in the dir that you are currently in
```console
git clone https://github.com/NeuralNuts/CloudGlimpseRust
```

Now we need to cd into the cloned repo
```console
cd CloudGlimpse
```

The git checkout command switches to the provided git branch
```console
git checkout cloud-glimpse-web
```

# Opening VS Code
This will open vs code within your current dir
```console
code .
```

# Git commands
To pull the current branches code
```console
git pull
```

To add all your code
```console
git add --a
```

To commit your code
```console
git commit -m "commit message"
```

To push your code
```console
git push
```
