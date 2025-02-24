source "https://rubygems.org"

gem "jekyll", "~> 4.2.0"
gem "bundler", "~> 2.3"
gem "kramdown-parser-gfm", "~> 1.1.0"

# GitHub Pages dependencies
group :jekyll_plugins do
  gem "github-pages", group: :jekyll_plugins
end

# Lock `http_parser.rb` gem to `v0.6.x` on JRuby builds since newer versions of the gem
# do not have a Java counterpart.
gem "http_parser.rb", "~> 0.6.0", :platforms => [:jruby]
