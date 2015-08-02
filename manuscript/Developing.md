# Developing

There are really few recommendations for how to setup your development environment for React Native. If you have a favorite IDE or editor for writing JavaScript in then it will do just fine.

## Xcode

You won't do much in Xcode. Occasionally you'll need to add some additional libraries or components the community has created, however most of the time I hit play, the simulator opens and I switch over to my IDE.

## Text Edtior

Any ole text editor will work, however I highly recommend something along the lines of [Sublime Text](http://www.sublimetext.com/) or [Nuclide](http://nuclide.io/). Nuclide is a set of plugins released by Facebook built on the [Atom](https://atom.io/) code editor. Atom is "a hackable text editor" produced by Github. The full suite of Nuclide plugins have yet to be released from Facebook however a few packages have.

If you have a preference for how you write JavaScript I'd stick with that. React Native doesn't care.


## RNPlay

[RNPlay](https://rnplay.org/) aka React Native Playground is fantastic for sharing your code and app online. It provides an editor and a iPhone simulator courtesy of [appetize.io](http://appetize.io). It's as simple as typing code and pressing play. Additionaly they added the ability to push up to a git repository. So if you wanted to install various things from NPM or build an app and show it off online then that is easily done.

There are some restrictions, such as not being able to add images to your xcodeproject as assets. Not necessarily an issue as the `Image` tag supports network images, but for a real application you don't want to have to depend on an internet connection to use image assets.