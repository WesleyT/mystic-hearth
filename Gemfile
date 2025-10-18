source "https://rubygems.org"

# Only include 'github-pages', NOT 'jekyll' directly
gem "github-pages", group: :jekyll_plugins

# Add CSV for Ruby 3.4+ local builds
gem "csv"

# Your theme (e.g. minima)
gem "minima", "~> 2.5"

group :jekyll_plugins do
  gem "jekyll-feed", "~> 0.12"
end

platforms :windows, :jruby do
  gem "tzinfo", ">= 1", "< 3"
  gem "tzinfo-data"
end

gem "wdm", "~> 0.2.0", :platforms => [:windows]

gem "http_parser.rb", "~> 0.6.0", :platforms => [:jruby]
