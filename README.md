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

## Add an announcement

Create a new .md file in the `_posts` folder. The name should follow the convention `year-month-day-title.md`.
In the file please add the metadata needed (see the other posts for reference) and your content. 
By default, the first paragraph will be displayed on the home page, and only the subpage will display
the entire content of the announcement.

## Contribute

You're welcome to add content, tweak UI, etc. To do so, please create a new branch based on master 
with the name `year-month-name`, eg `18-02-homepage-ui`. Continue working in that branch, 
merging master back into it periodically. When you're happy with your changes please
submit a PR on GitHub and ask someone from the website core organisation team to review
your changes. Upon approval either you or that person will take care of merging your branch
back into master and deploying the changes live.

Jekyll documentation: https://jekyllrb.com/docs/home/