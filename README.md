# splash-pages

These are simple, flat files that we can use instead of the heroku defaults in the event of planned maintenance or an unplanned timeout error.

These are linked the heroku app(s) via ENV vars as prescribed here: https://devcenter.heroku.com/articles/error-pages#configure-your-application

These pages are linked to the heroku app via a gh-pages static site.

If for some reason, you are having trouble with these files, you will likely be able to dig up a workable version the files on codepen here: https://codepen.io/collection/nxzbbk/

## Deploying Changes

To adjust or otherwise make a change to any of these static pages:

1. Pull down repo
1. Commit change
1. Push change master
1. Rebase gh-pages branch over master and force push

Note: changes to gh-pages sites may take up to a few minutes to be realized.

If you are having difficulty see more information here: https://pages.github.com/
