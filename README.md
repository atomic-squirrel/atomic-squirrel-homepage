# Atomic Squirrel Homepage

This is the code for the [Atomic Squirrel Home Page](http://www.atomic-squirrel.net).

# Quick start

1. Use Git to clone this repo
1. Make sure you have [Jekyll](http://jekyllrb.com/docs/installation/) installed
1. Just the first time: `bundle install`
1. To build the site and serve it: `bundle exec jekyll serve`
1. To test: `http://localhost:4000`

See the [Jekyll](http://jekyllrb.com/) and [GitHub Pages](https://pages.github.com/)
documentation for more info.

# Docker quick start

As an alternative to installing Ruby and Jekyll, if you're a user of
[Docker](https://www.docker.com/) and [Docker 
Compose](https://docs.docker.com/compose/), you can run a Docker image of 
atomic-squirrel-homepage that has all the dependencies already setup for you.

On Linux:

1. `git clone` this repo
2. `docker-compose up`
3. Go to `http://localhost:4000` to test 

On OS X, using the [docker-osx-dev](https://github.com/brikis98/docker-osx-dev)
project:

1. `git clone` this repo
2. `docker-osx-dev`
3. `docker-compose up`
4. Go to `http://dockerhost:4000` to test

# Technologies

1. Built with [Jekyll](http://jekyllrb.com/). This website is completely static, 
   using basic HTML for everything.
1. Hosted on [GitHub Pages](https://pages.github.com/). It's using the 
   [GitHub Pages Gem](https://help.github.com/articles/using-jekyll-with-pages/)
   and only Jekyll plugins that are 
   [available on GitHub Pages](https://help.github.com/articles/repository-metadata-on-github-pages/).
1. [Basscss](http://www.basscss.com/), [Sass](http://sass-lang.com/),
   [Font Awesome Icons](http://fortawesome.github.io/Font-Awesome/icons/),
   and [Google Fonts](https://www.google.com/fonts) for styling.
1. [UptimeRobot](http://uptimerobot.com/) and 
   [Google Analytics](http://www.google.com/analytics/) for monitoring and
   metrics.

# License

This code is released under the MIT License. See LICENSE.txt.