---
layout: post
title: How to Use Command Line to Add Post in Jekyll Blog
date: 2024-09-10 14:43 -0500
tags:
  - jekyll
  - portfolio
  - github
---
---
## SETTING UP
---

Add this line to your gemfile:

````
gem 'jekyll-compose', group: [:jekyll_plugins]
````

cd to project directory and run:

```
bundle
```

* Installs the gems into your project
* Updates the gemfile.lock file

Next run:
```
bundle exec jekyll post "My New Post"
```
* Creates post with proper frontmatter
* Find new post in `_posts` dir
* **Tip: use a markdown editor, such as Obsidian, to add content to your post to speed up your writing**

#### OPTIONAL
Start your live preview in your local browser
```
bundle exec jekyll serve --livereload
```



