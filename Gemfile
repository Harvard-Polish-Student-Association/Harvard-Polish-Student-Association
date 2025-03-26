source "https://rubygems.org"

# Use GitHub Pages
gem "github-pages", group: :jekyll_plugins
gem "webrick", "~> 1.7"

group :jekyll_plugins do
  gem "jekyll-feed", "~> 0.12"
  gem "jekyll-seo-tag", "~> 2.7"
end

# Lock http_parser.rb gem to v0.6.x on JRuby builds
gem "http_parser.rb", "~> 0.6.0", :platforms => [:jruby] 