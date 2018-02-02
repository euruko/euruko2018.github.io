# Euruko 2018 website

## Get up and running

1. Clone the repository:

    $ git clone https://github.com/euruko/euruko2018.github.io.git

2. Install dependencies:

    $ bundle install

3. Start up the server:

    $ jekyll server --incremental

## Where what is?

You'll find site-related configurations in `_config.yml`.

The main layout is in `_layouts/default.html`.

Stylesheets are in `assets/css/style.scss`. We're currently using the github
pages theme [Cayman](https://github.com/pages-themes/cayman). You can find
variables and junk to override
[here](https://github.com/pages-themes/cayman/blob/master/_sass/). Their docs
are very handy, too!

The landing page is currently in `index.html`.
