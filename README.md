This is part of my walkthrough of the Rails tutorial: 

Setup to make this app work is here:

http://www.railstutorial.org/book/beginning

Important steps:

brew install libtool libxslt libksba openssl

brew install libyaml

Here's the db setup:
https://github.com/perfectionist/sample_project/wiki/Convert-to-PostgreSQL

need to install the pg gem:

and create some dbs:

create database first_app_test;

create database first_app_development;

Install Loggly to see logs:

- had to add my credit card

heroku addons:add loggly
- Adding loggly on ctierney-first-app... done, v9 (free)
  Use `heroku addons:docs loggly` to view documentation.



