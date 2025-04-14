# frozen_string_literal: true

source "https://rubygems.org"
gemspec

gem "jekyll", ENV["JEKYLL_VERSION"] if ENV["JEKYLL_VERSION"]
gem "kramdown-parser-gfm" if ENV["JEKYLL_VERSION"] == "~> 3.9"
gem "github-pages", group: :jekyll_plugins
gem "webrick"
gem "csv"
gem "base64"

group :jekyll_plugins do
  gem "jekyll-feed"
end
