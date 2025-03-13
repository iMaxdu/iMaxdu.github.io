# imaxdu.github.io

[Demo](https://imaxdu.github.io/)

## Prerequisites

### Requirements

* [Ruby](https://www.ruby-lang.org/en/downloads/) version **2.7.1.**, including all development headers (ruby version can be checked by running `ruby -v`)
* [RubyGems](https://rubygems.org/pages/download) (which you can check by running `gem -v`)
* [GCC](https://gcc.gnu.org/install/) and [Make](https://www.gnu.org/software/make/) (in case your system doesn't have them installed, which you can check by running `gcc -v`,`g++ -v`  and `make -v` in your system's command line interface)

More info: [Requirements](https://jekyllrb.com/docs/installation/#requirements)

## Instructions

1. Run <code>gem install jekyll bundler</code>.
2. Copy the theme in your desired folder.
3. Enter into the folder by executing <code>cd name-of-the-folder</code>.
4. Run <code>bundle install</code>.
5. If you want to access and customize the theme, use <code>bundle exec jekyll serve</code>. This way it will be accessible on <code>http://localhost:4000</code>.
6. Upload the content of the compiled <code>_site</code> folder on your host server.
