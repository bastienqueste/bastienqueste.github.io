source "https://rubygems.org"
# Hello! This is where you manage which Jekyll version is used to run.
# When you want to use a different version, change it below, save the
# file and run `bundle install`. Run Jekyll with `bundle exec`, like so:
#
#     bundle exec jekyll serve
#

# gem "jekyll", "~> 4.3.1"
# Run github pages instead
gem 'github-pages', '~> 232'

# Breaks without...
gem "webrick"

# Use the bulma-clean-theme template
gem "bulma-clean-theme"

group :jekyll_plugins do
    gem "jekyll-feed", "~> 0.6"
    gem "jekyll-sitemap"
    gem "jekyll-paginate"
    gem "jekyll-seo-tag"
    gem 'jekyll-redirect-from'
end

# This is the default theme for new Jekyll sites. You may change this to anything you like.
gem "minima", "~> 2.5"


# Windows and JRuby does not include zoneinfo files, so bundle the tzinfo-data gem
# and associated library.
platforms :mingw, :x64_mingw, :mswin, :jruby do
  gem "tzinfo", ">= 1", "< 3"
  gem "tzinfo-data"
end

# Performance-booster for watching directories on Windows
gem "wdm", "~> 0.1.1", :platforms => [:mingw, :x64_mingw, :mswin]

# Lock `http_parser.rb` gem to `v0.6.x` on JRuby builds since newer versions of the gem
# do not have a Java counterpart.
gem "http_parser.rb", "~> 0.6.0", :platforms => [:jruby]

# Bibliography add-on (BYQ 2025/03/05)
gem 'jekyll-scholar'
