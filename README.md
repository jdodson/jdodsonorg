# jdodson.org uses

* jekyll
* bootstrap 4

# install

gem install bundle
bundle

# serve the pages and regenerate when there is a change
jekyll serve --watch

# build a fresh version of the site
jekyll build --destination docs
echo "jdodson.org" > docs/CNAME
