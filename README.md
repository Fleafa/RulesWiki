## RulesWiki theme for Webhook

This is a site theme based on Dave Snider's [Wyrm Sass](http://www.wyrmsass.org)
frontend framework. 

## Usage

1. After installing through Webhook close your local runserver.
2. Run `bower install`. This requires bower, which can be installed by running `npm install -g bower`.
3. Run `grunt copy` to copy the bower dependencies into `/static/`
4. Run `grunt sass` to build a css file.
5. Restart your runserver. Editing sass will rebuild css automatically.
