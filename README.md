# Edition

Product documentation template for Jekyll. Browse through a [live demo](https://long-pig.cloudvent.net/).
Start documenting your product, application, service or website with this configurable theme.

![Docs Site template screenshot](images/_screenshot.png)

Docs Site was forked from Edition by [CloudCannon](http://cloudcannon.com/), the Cloud CMS for Jekyll.
Find more templates and themes at [Jekyll Tips](http://jekyll.tips/templates/).

Learn Jekyll with step-by-step tutorials and videos at [Jekyll Tips](http://jekyll.tips/).

## Features

### From Edition

* Two column layout
* Full text search
* Pre-styled components
* Auto-generated navigation based on category
* Optimised for editing in [CloudCannon](http://cloudcannon.com/)
* Change log
* RSS/Atom feed
* SEO tags
* Google Analytics

### Added Features



## Setup

Add your site and author details in `_config.yml`.

## Develop

Edition was built with [Jekyll](http://jekyllrb.com/) version 3.3.1, but should support newer versions as well.

Install the dependencies with [Bundler](http://bundler.io/):

~~~bash
$ bundle install
~~~

Run `jekyll` commands through Bundler to ensure you're using the right versions:

~~~bash
$ bundle exec jekyll serve
~~~

## Editing

You should only have to edit pages of markdown, and the site should be able to handle the rest.

### Documentation pages

* Add, update or remove a documentation page in the *Documentation* collection.
* Change the category of a documentation page to move it to another section in the navigation.
* Documentation pages are organised in the navigation by category, with URLs based on the path inside the `_docs` folder.

### Change log

* Add, update or remove change log entries from your posts.
* Tag entries as minor or major in the front matter.

### Search

* Add `excluded_in_search: true` to any documentation page's front matter to exclude that page in the search results.

### Navigation

* Change `site.show_full_navigation` to control all or only the current navigation group being open.
