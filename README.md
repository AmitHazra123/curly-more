# Site settings
description: A blog about teaching GitHub
baseurl: "/curly-more/" # the subpath of your site, e.g. /blog/
url: "" # the base hostname & protocol for your site

# User settings
username: Amit Hazra
user_description: Web Developer at Microsoft Trianing Association
user_title: Web Developer
email: shivahazra@gmail.com
twitter_username: githubtraining
github_username:  useramit2153
gplus_username:  lorem_ipsum
disqus_username: lorem_ipsum

# Build settings
markdown: kramdown
highlighter: pygments
permalink: /:title/


# html minify
compress_html:
  clippings: all
  comments: all
  endings: []
  profile: false

# Links to include in menu navigation
# For external links add external: true
links:
  - title: Home
    url: /
  - title: Series
    url: /series
  - title: Tags
    url: /tags
  - title: About Me
    url: /about

# exclude my node related stuff
exclude: ['package.json', 'src', 'node_modules']
