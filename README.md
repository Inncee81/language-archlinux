# The Arch Linux Development Package
![visual-studio-code-oss PKGBUILD](http://i.imgur.com/B5McvKv.png)

This package is essentially the Arch Linux equivalent to the [`language-gentoo`](https://github.com/aegypius/language-gentoo) package of Nicolas Laurent. It provides syntax-highlighting for PKGBUILDs (with the help of the [`language-unix-shell`](https://github.com/fusion809/language-shellscript) package), along with Atom commands for running a variety of different PKGBUILD commands. Beware that you will need to have the following packages installed in order for this package to have its full functionalities:

* `namcap`
* `pacman` &mdash; which, of course, means you should be operating on Arch Linux or another platform that uses the pacman package manager.
* `pkgbuild-introspection`
