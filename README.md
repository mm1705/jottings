# jottings

This website contains a curated list of:
- Phrases,
- Quotes,
- Poems,
- Shayari,
<br /> collected over-time, in Hindi and English languages.

In order to create a pull-request, use branch: gh-pages

This is a static-website generated from Jekyll.
Refer to jekyll_help.txt file on website or in repo for more details about static vs dynamic websites & jekyll.

Setup instructions:

Installation requirements: [details: https://jekyllrb.com/docs/installation/]
- Install Ruby
- Install RubyGems
- Install Node.js
- Install GCC, Make
- Install Jekyll

The commands for installation may vary depending on OS.
Since I used Ubuntu 18.04 OS, the commands are as follows:

Installing Ruby & RubyGems:
sudo apt-get install ruby-full

To check if Ruby and RubyGems is properly installed, use following command:
ruby -v
gem -v

Update RubyGems:
sudo gem update --system 3.0.6 
[Version 3.0.6 is mentioned as the latest RubyGems version has ConfigMap deprecation warning. More on this here: https://github.com/rubygems/rubygems/issues/3068]

Install Node.js:
curl -sL https://deb.nodesource.com/setup_14.x | sudo -E bash -
sudo apt-get install -y nodejs

To check if GCC/g++/Make are installed, use following commands:
gcc -v
g++ -v
make -v

After installing pre-requisites, clone the repo using:
git clone https://github.com/mm1705/jottings.git

Inside jottings/ folder, execute this command to run website on localhost: 
bundle exec jekyll serve --watch

Now, Jekyll webiste is running on localhost:4000
