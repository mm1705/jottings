---
layout: page
title: Jekyll
permalink: /jekyll/
---

Basic help for website generated via Jekyll "minima" theme.

#### Commands:

- sudo gem install jekyll bundler
- jekyll new jottings [to create basic website files in folder 'jottings']
- bundle exec jekyll serve --watch [to start website locally]

[While the site is running, after making changes to website files: save the files and refresh the webpage to see the changes—except for the _config.yml file, for which we must stop running the website and restart running the website to see changes.]

--------------------------------------------------------------------------------------
<br />

#### Directories/Files:

- _site folder => This is where Jekyll puts the HTML files it generates from the other files in your website folder.(e.g. you’ll write and save posts as Markdown files, but Jekyll will convert these to HTML for display in a web browser)
- _config.yml => Provides basic site configuration settings like information about website, such as the site’s title, how to structure links to posts (e.g. should they follow the pattern MySite.com/year/month/day/post-title?).
- _includes folder => Contain files that get included on all or certain pages (e.g. code to make the header contain your site title and main menu on every page of the site).
- _layouts folder => Contains code that controls how the pages on your site look (default.html), as well as customizations of that code to further style blog posts (post.html) and pages (page.html)
- _posts folder => Files that each represent a blog post on your website. Adding a new post to this folder will make a new blog post appear on your website, in reverse chronological order (newest post to oldest).
- _sass folder => Holds SCSS files that control the visual design of the site
- index.md => Place to add content that you want to appear on your homepage, such as a biography blurb to appear above the “Posts” list
- about.md => Example Jekyll page. It’s already linked in the header of your website, and you can customize its text by opening and writing in that file.
- css folder => Holds CSS converted from SCSS that controls the visual design of the sitec
- feed.xml => Allow people to follow the RSS feed of your blog posts.
- index.html => Controls the structuring of content on your site’s homepage

--------------------------------------------------------------------------------------
<br />

#### Posts and pages:
Pages and posts are just two types of written content that’s styled differently. <br />
Pages are content (like an “About” page) that isn’t organized or displayed chronologically, but might be included in your website’s main menu.<br />
Posts are meant to be used for content best organized by publication date. The URLs (links) for pages and posts are also different by default (although you can change this): page URLs look like MySite.com/about/, while post URLs look like MySite.com/2016/02/29/my-post-title.html.

To create a new page in addition to the “About” page that already exists on the site (and can be customized or deleted), create a copy of the about.md file in the same folder (the main website folder) and change its filename to the title you wish, using hyphens instead of spaces (e.g. resume.md or contact-me.md). Also change the title and permalink in the file’s front matter, and the content of the file. The new page should automatically appear in the main menu in the site’s header.

Note: Make sure any Markdown cheatsheets you look at are for the “kramdown” flavor of Markdown, which is what GitHub Pages supports.

--------------------------------------------------------------------------------------
<br />

#### Front matter:

In about.md file:
> The stuff between the -– dashes is called “front matter”

Front matter guidelines:
> layout: Keep this as-is (it should say page/post). <br />
> title: Change this to the desired page title (unlike posts, no quotation marks around the title). <br />
> permalink: change the text between the two forward slash marks to the word (or phrase—but you’ll need to use hyphens and not spaces!) that you want to follow your site’s main URL to reach the page. For example, permalink: /about/ locates a page at localhost:4000/yourwebsitefoldername/about/

--------------------------------------------------------------------------------------
<br />

#### "Minima" theme:

This is the base Jekyll theme. You can find out more info about customizing your Jekyll theme, as well as basic Jekyll usage documentation at [jekyllrb.com](https://jekyllrb.com/)

You can find the source code for Minima at GitHub:
[jekyll][jekyll-organization] /
[minima](https://github.com/jekyll/minima)

You can find the source code for Jekyll at GitHub:
[jekyll][jekyll-organization] /
[jekyll](https://github.com/jekyll/jekyll)


[jekyll-organization]: https://github.com/jekyll


[Getting started with Jekyll and github-pages](https://programminghistorian.org/en/lessons/getting-started-with-markdown)