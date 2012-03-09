# Prolog syntax highlighting for Sublime Text 2 #

This package provides syntax highlighting for the logic programming language
Prolog. It is highly work in progress, so use with care.

## Installation ##

### Installation via Sublime Package Control ###

As soon as my pull request gets accepted, I recommend using the
[Sublime Package Control] [1] to install this package. This way is much more
convenient. It is named *Prolog syntax highlighting* there, as well.

[1]: http://wbond.net/sublime_packages/package_control

### Manual installation ###

If you want to manually install this package, please do:

	cd /tmp
	wget -O sublimeprolog.tar.gz http://github.com/alnkpa/sublimeprolog/tarball/master
	tar -xzvf sublimeprolog.tar.gz
	cd alnkpa-sublimeprolog-<commit>
	mv Prolog.tmLanguage ~/.config/sublime-text-2/Packages/User/
