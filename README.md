# troop1000-website

A website for Troop 100 in Baltimore, MD, located at the Cathedral of Mary Our Queen.

## Developing

Requirements:
* Ruby 2.6.0
* RubyGems
* Git

First time setup on Linux or Mac:
*NOTE: Windows is not supported.*
```
git clone https://github.com/FootInMySalad/troop1000-website.git
cd troop1000-website
gem install jekyll bundler
```

Test the website with `bundle exec jekyll serve`.

This website uses **Rake** to automatically build and publish to Github. To build and publish the website, use:
```
rake blog:publish
```

If you have an error, try using
```
bundle exec rake blog:publish
```
