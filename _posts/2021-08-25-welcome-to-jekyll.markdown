---
layout: post
title:  "Why I Chose GitHub Pages as my Content Management System"
date:   2021-08-25 19:50:29 -0600
categories: content-management-systems
---

I selected GitHub Pages as my content management system because it is stupidly simple, assuming you know the following technologies:

* [Markdown](https://www.markdownguide.org/)
* [Bundler](https://bundler.io/)
* [Jekyll](https://jekyllrb.com/)
* [Git](https://git-scm.com/)

GitHub Pages allows you to serve a static site--something like a blog or API documentation--completely for free, however you want it to be, if you do the heavy lifting of creating the content the old fashioned way--using a text editor and a terminal. So here's my workflow:

```bash
$ bundle exec jekyll draft my-new-draft
$ emacs _posts/YYYY-MM-DD-my-new-draft.markdown
$ git add .
$ git commit -am 'Create a new post'
$ git push
```

And then I have the site up. I have used this service in the past to publish [a couple](https://cincospenguinos.github.io/LaMortVoit/) [webgames](https://cincospenguinos.github.io/FATHER/), as well as [my professional blog](https://cincospenguinos.github.io/blog/).
