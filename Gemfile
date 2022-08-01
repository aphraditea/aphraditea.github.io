source "http://rubygems.org"
gem "jekyll"
gem "rack"
gem "webrick"

group :jekyll_plugins do
  gem "jekyll-feed"
  gem 'jekyll-admin', "0.9.0"
end

# Windows and JRuby does not include zoneinfo files, so bundle the tzinfo-data gem
# and associated library.
install_if -> { RUBY_PLATFORM =~ %r!mingw|mswin|java! } do
  gem "tzinfo", "~> 1.2"
  gem "tzinfo-data"
end

# Performance-booster for watching directories on Windows
gem "wdm", :install_if => Gem.win_platform?
