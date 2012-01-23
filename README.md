### Downloading and configuring a local copy of supermodel5.com:

    git clone git@github.com:dsimmons/supermodel5.git
	cd supermodel5

*Assuming rbenv, you're on your own for RVM*

	gem install bundle
	rbenv rehash
	bundle install

	git checkout site
	mkdir _deploy
	cd _deploy
	

- Make any website code modifications in \_source.
- The **site** branch is for storing the source code.
- The **gh-pages** branch is what's rendered when http://dsimmons.github.com/supermodel5 is requested.
