source "https://rubygems.org"
# Hello! This is where you manage which Jekyll version is used to run.
# When you want to use a different version, change it below, save the
# file and run `bundle install`. Run Jekyll with `bundle exec`, like so:
#
#     bundle exec jekyll serve
#
# This will help ensure the proper Jekyll version is running.
gem "jekyll", "~> 4.1.0"

gem "webrick", "~> 1.7"

# Theme
gem "evolveum-jekyll-theme", "~> 0.1.0"

# If you have any plugins, put them here!
group :jekyll_plugins do
  gem "jekyll-feed", "~> 0.12"
  gem 'jekyll-asciidoc'
  gem 'asciidoctor-bibtex'

  # Requirements: sudo apt install cmake bison flex libglib2.0-dev libcairo2-dev libpango1.0-dev libgdk-pixbuf2.0-dev libxml2-dev
  # Anyway, does not work properly. We go for MathJAX But keeping here commented out, in case it may be needed.
  #gem "asciidoctor-mathematical"
end

# Windows and JRuby does not include zoneinfo files, so bundle the tzinfo-data gem
# and associated library.
install_if -> { RUBY_PLATFORM =~ %r!mingw|mswin|java! } do
  gem "tzinfo", "~> 1.2"
  gem "tzinfo-data"
end

# Performance-booster for watching directories on Windows
gem "wdm", "~> 0.1.1", :install_if => Gem.win_platform?

gem "evolveum-jekyll-plugin"
