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

CSS is in `assets/css/` Only add to general.scss styles used on multiple pages.
 For styles used on a single page please add a separate file.
 When adding a new page take a look at `_layouts/post.html` to see what layout 
 you need to use and what's the structure of the html code that will keep 
 the current theme.
 
Images are added in `assets/images/`.
JS is added in `assets/scripts/`.

The homepage is `index.html`.
