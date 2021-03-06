# inform-mode

### An Emacs major mode for editing Inform 6 source code.

## Introduction

inform-mode supports the usual program mode functions: automatic
indentation, moving over expressions, comment and string filling, font
locking, tags-file support, starting compiles and parsing errors. You
can also run a z-code interpreter against the compiled code.

It should work on GNU Emacs (v22+) or XEmacs (v21.4+) on any supported
platform.

See [NEWS](https://github.com/rupertl/inform-mode/blob/master/NEWS) for details of recent changes.


## Installing inform-mode

See [INSTALL](https://github.com/rupertl/inform-mode/blob/master/INSTALL) for notes on installing inform-mode.


## Using inform-mode

After installation, inform-mode will be activated for any files ending
in .inf (and optionally .h) when you visit them using Emacs. Type 'C-h
m' to view the documentation for the mode. Variables governing
inform-mode can be customized; type 'M-x customize' and navigate to
Programming / Languages / inform-mode.


## License

inform-mode is free software, released under the GNU General Public License version 3 (or later). See [COPYING](https://github.com/rupertl/inform-mode/blob/master/COPYING) for further details of the license.


## Latest version

The latest stable release of inform-mode can be found at the website

http://www.rupert-lane.org/inform-mode/

Seee http://www.rupert-lane.org/inform-mode/news.html or subscribe to
the Atom feed at http://www.rupert-lane.org/inform-mode/news.xml to get
details of the latest version.

inform-mode can be donwloaded via the Marmalade package system in Emacs;
see http://marmalade-repo.org/

It is also available via anonymous FTP at ftp.ifarchive.org


## Bug reports and development

Any bugs reports, patches, feature suggestions or other feedback would
be welcomed. Please email rupert@rupert-lane.org

Development versions can be obtained via the git repository

git clone http://www.rupert-lane.org/inform-mode/inform-mode.git

Or via github:

https://github.com/rupertl/inform-mode

The 'master' branch tracks the released version; 'testing' contains the
latest development version but may not be stable.


## Authors

Rupert Lane is the current maintainer of inform-mode. inform-mode was
originally written by Gareth Rees and was previously maintained by
Michael Fessler. Many people have helped with the development and
testing of inform-mode; see [AUTHORS](https://github.com/rupertl/inform-mode/blob/master/AUTHORS) for full details.
