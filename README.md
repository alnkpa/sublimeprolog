# Prolog syntax highlighting for Sublime Text 2 & 3 #

[![No Maintenance Intended](http://unmaintained.tech/badge.svg)](http://unmaintained.tech/)

This package provides syntax highlighting and automated build for the logic
programming language Prolog. It is highly work in progress, so use with care.

## Auto Build System ##
To be able to use the <kbd>Ctrl</kbd>+<kbd>B</kbd> automatic build, you need to define `main/0`
where you compute the solution and you also print it. For example:

```prolog
main :- compute(input, Solution), writef('%t\n', [Solution]).
```

An indicator that this is not done (correctly) is the following error:

```
ERROR: call/2: Undefined procedure: main/1
ERROR:   However, there are definitions for:
ERROR:         main/0
```

## Installation ##

### Installation via Sublime Package Control ###

I recommend using the [Sublime Package Control](http://wbond.net/sublime_packages/package_control) to install this package. 
This way is much more convenient. It is named *Prolog*.

### Manual installation ###

If you want to manually install this package, please do:

```sh
cd /tmp
wget -O sublimeprolog.tar.gz http://github.com/alnkpa/sublimeprolog/tarball/master
tar -xzvf sublimeprolog.tar.gz
cd alnkpa-sublimeprolog-<commit>
mv Prolog.tmLanguage ~/.config/sublime-text-2/Packages/User/
```

## License ##

This Source Code Form is subject to the terms of the Mozilla Public
License, v. 2.0. If a copy of the MPL was not distributed with this
file, You can obtain one at <http://mozilla.org/MPL/2.0/>.
