# Advanced Ed:

Steps to getting Ed running as a local development server.

1. Getting the environment setup:
	1. Ruby + Git on OSX:
		* `xcode-select --install` to install XCode command line tools
		* OSX has Git + Ruby
	1. Ruby + Git on Windows:
		* Install [Choclatey](https://chocolatey.org/)
		* `choco install git`
		* `choco install ruby --version 2.2.4`
		* `choco instlal ruby2.devkit`
1. `mkdir Projects`
	* In home directory somewhere
1. `cd Projects`
1. On GitHub, fork https://github.com/oncomouse/ed and rename (optional)
1. `git clone https://github.com/username/repositoryname`
1. `cd ed`
1. `gem install bundle`
1. `bundle install`
1. `git checkout gh-pages`
1. `jekyll serve`