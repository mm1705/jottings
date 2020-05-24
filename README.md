# Welcome to Jottings!

The website is hosted **[here](https://mm1705.github.io/jottings/)**.
 
This website contains a curated list of:
- Phrases,
- Quotes,
- Poems,
- Shayari, etc...

collected over-time, in **Hindi** and **English** languages.

This is a static-website generated from [Jekyll]([https://jekyllrb.com/](https://jekyllrb.com/)).
Refer to Help_jekyll.txt file on website or in repo for more details about static vs dynamic websites and jekyll.

## Setup instructions:

Installation requirements: 
- Install Ruby
- Install RubyGems
- Install Node.js
- Install GCC, Make
- Install Jekyll [more details [here](https://jekyllrb.com/docs/installation/)]

The commands for installation may vary depending on the Operating System.
The commands required for installation in Ubuntu 18.04 OS are as follows:

Installing Ruby & RubyGems:
>sudo apt-get install ruby-full

To check if Ruby & RubyGems is properly installed, use following command:
>ruby -v
>gem -v

Update RubyGems:
>sudo gem update --system 3.0.6 <br />
[Version 3.0.6 is mentioned as the latest RubyGems version has ConfigMap deprecation warning. More on this issue here: https://github.com/rubygems/rubygems/issues/3068]

Install Node.js:
>curl -sL https://deb.nodesource.com/setup_14.x | sudo -E bash -
>sudo apt-get install -y nodejs

To check if GCC/g++/Make are installed, use following commands:
>gcc -v
>g++ -v
>make -v

After installing pre-requisites, clone the repo using:
>git clone https://github.com/mm1705/jottings.git

Inside jottings/ folder, execute this command to run website on localhost: 
>bundle exec jekyll serve --watch

Now, the Jekyll website is running on localhost:4000. [URI can be changed from _config.yml file.]

## Directories/Files Info:
- Directory:
	- _includes: Files that get included on all or certain pages (e.g. code to make the header)
	- _layouts: Code that controls how the pages on your site look (default.html), as well as customizations of that code to further style blog posts (post.html) and pages (page.html)
	- _posts: Individual files that each represent a blog post on your website. 
	- _sass: SCSS files that control the visual design of the site
	- _site: HTML pages that appear on the web are generated and stored 
	- css: CSS converted from SCSS that controls the visual design of the site

- Files:
	- _config.yml: Provides basic settings information about site, e.g. website’s title,URI configuration
	- index.md: Place to add content that you want to appear on your homepage
	- feed.xml: Allow users to follow the RSS feed of your blog posts
	- index.html: Controls the structuring of content on your site’s homepage

Note that an `_` in the prefix of name indicates the directory or file has been auto-generated by Jekyll.

## Themes:
This website uses [`minima`](https://github.com/jekyll/minima) Jekyll theme. <br />
Before getting started with playing around with Jekyll themes, since this website is hosted on Github Pages, we need to make sure the theme is supported by Github Pages. You can find themes supported by Github Pages [here](https://pages.github.com/themes/). <br />

- [ ] TODO: Add 'themes' folder and try some themes like Midnight.

## Miscellaneous: 

In order to create a Pull request, use this branch:
>gh-pages

**[Reference for getting started with Jekyll](https://programminghistorian.org/en/lessons/building-static-sites-with-jekyll-github-pages)**

Also, if you need help with markdown files, see [this](https://stackedit.io/app#). <br />
To validate RSS feed, see [this](https://validator.w3.org/feed/)

### Notes:
Before overriding Jekyll theme, take care of [these](https://github.com/jekyll/minima/issues/375#issuecomment-499904189).
