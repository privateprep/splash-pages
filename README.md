# splash-pages

These are simple, flat files that we can use instead of the heroku defaults in the event of planned maintenance or an unplanned timeout error.

These are linked the heroku app(s) via ENV vars as prescribed here: https://devcenter.heroku.com/articles/error-pages#configure-your-application

At the time of this writing (12/18/2018), the active pages are deployed to a free-tier surge account that only Dan has access to. Obviously, this is suboptimal and in the future, they should be moved to either 1) gh-pages or 2) a public s3 bucket.

If for some reason, you are having trouble, you will likely be able to dig up a workable version the files on codepen here: https://codepen.io/collection/nxzbbk/
