Summary of Deployment

## Overview
There are two folders. jekyll_site is the folder with the actual site. docs is the folder with the generated site.

There is also a custom theme called customtheme. This has it's own build of the site as well.

## Deployment
There are two main branches: master and develop

For adding a new feature to the site use feature/<name> branch from develop.

If you want to update the actual website, you will need to build the site and then copy it over to the docs folder using the build_and_copy_site.sh script.

## Deployment to Master
You will need to merge your feature branch into master and then github pages will update the site.

## Local Development

To run the site use the commmand `bundle exec jekyll serve` in the jekyll_site folder. This will serve the site in the browser while also updating the site on changes.