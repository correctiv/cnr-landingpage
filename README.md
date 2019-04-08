# crowdnewsroom.org landingpage

This is a simple jekyll static page to serve the landingpage of https://crowdnewsroom.org

## local developement

prerequisites for UNIX-systems (ruby and rubygems):

        sudo apt-get install rubygems

on a mac:

        brew install rubygems

check out this repository

        git clone git@github.com:correctiv/cnr-landingpage.git
        cd ./cnr-landingpage/

install jekyll and dependencies (see: https://jekyllrb.com/):

        gem install bundler jekyll
        bundle install

Serve server locally to preview changes:

        bundle exec jekyll serve

## edit content

Edit the markdown files (`index.md`, `index-en.md`) and in the `_pages`-subfolder

## deployment

This will generate the html files in the `./_site`-folder

        bundle exec jekyll build

Upload the contents of the `_site`-folder via ftp to the webroot of https://crowdnewsroom.org
