A simple vagrant bootstrap


## Installation

    $ vagrant plugin install vagrant-r10k

__Note__ that if you include modules from a (the) forge in your Puppetfile, i.e. in the format

    mod 'username/modulename'

instead of just git references, you will need the ``puppet`` rubygem installed and available. It
is not included in the Gemfile so that users who only use git references won't have a new/possibly
conflicting Puppet installation.

