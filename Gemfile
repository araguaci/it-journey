source "https://rubygems.org"
# RTD - /docs/ruby/gemfile
# Create your own gem here https://guides.rubygems.org/
# Hello! This is where you manage which Jekyll version is used to run.
# When you want to use a different version, change it below, save the
# file and run `bundle install`. Run Jekyll with `bundle exec`, like so:
#
#     bundle exec jekyll serve
#
# This will help ensure the proper Jekyll version is running.
# Happy Jekylling!

# dependancies https://pages.github.com/versions/
gem 'github-pages' , '231'
gem 'jekyll' , '3.9.5'

# This is the default theme for new Jekyll sites. You may change this to anything you like.
# If you want to use GitHub Pages, remove the "gem "jekyll"" above and
# uncomment the line below. To upgrade, run `bundle update github-pages`.

# https://docs.github.com/en/pages/setting-up-a-github-pages-site-with-jekyll#installing-jekyll
# , group: :jekyll_plugins

# If you have any jekyll plugins, put them here!
group :jekyll_plugins do
  # gem 'jekyll-algolia' 
  # gem 'jekyll-assets', "~> 1.0.0"
  # gem 'jekyll-mermaid'
  # gem 'jekyll-admin'
  # gem 'jekyll-spaceship'

# these are all part of the github-pages gem
  gem 'jekyll-feed', "~> 0.17"
  gem 'jekyll-sitemap' , "~> 1.4.0"
  gem 'jekyll-seo-tag', "~> 2.8.0"
  gem 'jekyll-paginate', '~> 1.1'
  # gem 'jekyll-redirect-from'
  # gem 'jemoji' # Doesn't work for some reason
end

# TODO: build a bootstrap plugin for jekyll

#  bootstrap https://getbootstrap.com/docs/5.1/getting-started/introduction/
#  https://github.com/twbs/bootstrap-rubygem/blob/main/README.md
# gem "bootstrap",  ">=5.3.3"
# gem 'bootstrap-icons', '~> 1.0', '>= 1.0.14'
# gem 'jquery-rails'
# gem "minima", "~> 2.5"

# Windows and JRuby does not include zoneinfo files, so bundle the tzinfo-data gem
# and associated library.
platforms :mingw, :x64_mingw, :mswin, :jruby do
  # gem "tzinfo", "~> 1.2"
  # gem "tzinfo-data"
  # gem "webrick"
  # gem 'eventmachine', github: 'eventmachine/eventmachine'
  # gem "eventmachine" --platform ruby
end
# gem "eventmachine", "1.2.0"

# Live Reload Compatibility
# platforms :x64-mingw32 do
  # gem "eventmachine" ~> 1.2.7
# end

# Performance-booster for watching directories on Windows
# gem 'wdm', '>= 0.1.0' if Gem.win_platform?
# gem "wdm", "~> 0.1.1", :platforms => [:mingw, :x64_mingw, :mswin]

# Mac OS compatibility fix

# gem "webrick", "~> 1.7"
# gem "rack", ">= 2.1.4"

# gem "jekyll-postcss"

# gem "kramdown", "~> 2.3.2"
# gem "kramdown-parser-gfm", "~> 1.1.0"
# gem "rouge", "~> 3.36.0"

# gem "algolia"
gem "jekyll-algolia"
# gem "html-proofer"