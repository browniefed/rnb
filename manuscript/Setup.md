#Setup

There is already a great step by step guid at [http://facebook.github.io/react-native/docs/getting-started.html](http://facebook.github.io/react-native/docs/getting-started.html). I'll break it out a bit but check it out for an official guide.

## Check List

- A Mac.
- Xcode 6.3 or higher. However if you are on Mavericks you can run Version 6.2 (6C131e) and React Native will still work.
- Homebrew
- NVM - ( Node Version Manager).
- NPM - (Node Package manager).
- iojs or node installed. iojs is recommended, however Node and iojs are merging together so this eventually will just be node.
- Watchman, this is for watching for file changes to reload.
- [OPTIONAL] - Flow for type checking your JavaScript. This is an optional install, and we won't be covering it.
- react-native-cli globally installed. This will help us initialize a project


If you have all of these installed and are ready to go then you can skip this next section.


## Steps

### Install Xcode

[Xcode](https://developer.apple.com/xcode/downloads/) can be downloaded here. It will require that you setup a developer account, however that is free. Download which ever the latest version it prompts you with.
As said before you will need 6.3 or higher, or if you are on Mavericks 6.2 (6C131e) will do.

If you already have Xcode installed make sure you have one the recommended versions and we'll move on.


### Install Homebrew

[Homebrew](http://brew.sh/) is a package manager for OSX. It's quite standard for developers to use it. It allows for easy installations, and upgrades of many packages on the web. Check the website for install instructions, however all that is needed is to run this command in a terminal

```
ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
```

There are alternative installation instructions here [https://github.com/Homebrew/homebrew/blob/master/share/doc/homebrew/Installation.md#installation](https://github.com/Homebrew/homebrew/blob/master/share/doc/homebrew/Installation.md#installation).


### Install NVM

You could install iojs/node with Homebrew however it is highly recommended to install NVM as it allows you to easily install, and switch between any version of iojs/node.

The installation instructions can be found here [https://github.com/creationix/nvm#installation](https://github.com/creationix/nvm#installation).

However it just recommends a few one liners.

```
curl -o- https://raw.githubusercontent.com/creationix/nvm/v0.25.4/install.sh | bash
```

or if you prefer `wget`

```
wget -qO- https://raw.githubusercontent.com/creationix/nvm/v0.25.4/install.sh | bash
```

### Install iojs

Once nvm is installed open up a new terminal and run 

```
nvm install iojs && nvm alias default iojs
```

This will install iojs and alias `node` on your system to always use the nvm install iojs.

If you don't want this you can always install any version of node with nvm and re-alias it.


### Install Watchman

Now with brew installed run the command below.

```
brew install watchman
```

Watchman isn't necessarily needed, but it is highly recommended otherwise you may hit node file watching bugs.
I will say watchman is a constant source of issues filed on github so make sure you stay up to date with it.

For troubleshooting, installation, and upgrade guides check out [https://facebook.github.io/watchman/docs/install.html](https://facebook.github.io/watchman/docs/install.html).

The basic upgrade for brew apps is simply running

```
brew update && brew upgrade
```

### Install reat-native-cli

The React Native CLI will setup projects for you and get you writing an application fast.

```
npm install -g react-native-cli
```


## Create an App

Now with all of that installed lets get started.

Open up a terminal and find somewhere you want your project to live. When ready run

```
react-native init CoolProject
```

You will now have a folder called `CoolProject` with a sample application created by the React Native ClI.

To get started open up `CoolProject.xcodeproj`. This should open up Xcode and then click on the Play button in the top left corner.

To see the code that is running you will need to open the `index.ios.js` file.

You have now successfully created a new React Native app!