# Software Site

Based on the Treat template for Jekyll.

## Setup

1. Site details in including Google Analytics/Disqus in `_config.yml`.
3. Author details in `_data/sidebar.yml`

## Develop

Requires Ruby 3.8 to run GitHub Pages.

### Docker (Windows)
`docker run --rm -p 80:4000 --volume="%CD%:/srv/jekyll:Z" --publish [::1]:4000:4000 jekyll/jekyll:3.8.5 jekyll serve`

Treat was built with [Jekyll](http://jekyllrb.com/) version 3.4.3, but should support newer versions as well.

Install the dependencies with [Bundler](http://bundler.io/):

~~~bash
$ bundle install
~~~

Run `jekyll` commands through Bundler to ensure you're using the right versions:

~~~bash
$ bundle exec jekyll serve
~~~
