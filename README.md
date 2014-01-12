# erc-terminal-notifier.el

OSX notifications via the [terminal-notifier gem](https://github.com/alloy/terminal-notifier) for Emacs ERC.

## Installation

### Install terminal-notifier

- As a ruby gem

        $ sudo gem install terminal-notifier

- As a binary

    Download from [here](https://github.com/alloy/terminal-notifier/downloads)

- With [homebrew](http://brew.sh)

        $ brew install terminal-notifier

### Install the package:

    $ cd ~/.emacs.d/vendor
    $ git clone git://github.com/julienXX/erc-terminal-notifier.el.git

Note: it's also available in [MELPA](http://melpa.milkbox.net)

In your Emacs config:

    (add-to-list 'load-path "~/.emacs.d/vendor/erc-terminal-notifier.el")
    (require 'erc-terminal-notifier)

## License

Copyright 2013 (c) Julien Blanchard <julien@sideburns.eu>

Released under the same license as GNU Emacs.
