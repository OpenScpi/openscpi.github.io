# OpenScpi GitHub Pages Site

This is the website for the OpenScpi project. Link to published location: [openscpi.github.io](https://openscpi.github.io)

## For developers:

### No software, just markdown:
To just post a new blog post without installing things and using just a text editor, you can also just add new file `./_posts/<YEAR>-<MONTH>-<DAY>-<TITLE>.md`. And include this text in the file:
```
---
layout: post
title: <TITLE HERE>
date: 2024-08-10 22:07 -0400 <obviously update the date>
---

<body of post goes here...>
```

### Jekyll Environment with testing and stuff

Install Ruby and Jekyll. Recommend using the RubyInstaller [from these instructions](https://jekyllrb.com/docs/installation/windows/). See also the [Prerequistes GitHub Pages doc](https://docs.github.com/en/pages/setting-up-a-github-pages-site-with-jekyll/creating-a-github-pages-site-with-jekyll#prerequisites). You need Ruby, RubyDevkit, MSYS2, MINGW, Jekyll, and bundler.
Use `bundle install` in the repo folder once you have the prerequistes and the repo cloned. That will install everything you need.

Uses the [`jekyll-compose` plugin](https://github.com/jekyll/jekyll-compose), so you can use various helper commands.
 * To create a new blog post, use `bundle exec jekyll post "New Post Name"`
 * To create a new page, use `bundle exec jekyll page "New Page Name"`

To test locally ([full GitHub Pages docs here](https://docs.github.com/en/pages/setting-up-a-github-pages-site-with-jekyll/testing-your-github-pages-site-locally-with-jekyll)):
 1. `bundle install`
 2. `bundle exec jekyll serve`
 3. Navigate to [http://localhost:4000](http://localhost:4000).