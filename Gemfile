source "https://rubygems.org"
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby "3.2.2"

# backend
gem "bootsnap", require: false
gem "dotenv-rails"
gem "puma", "~> 6.0"
gem "rails", "~> 7.0.6"
gem "redis", "~> 5.0"
gem "sqlite3", "~> 1.4"
gem "tzinfo-data", platforms: %i[mingw mswin x64_mingw jruby]

# shopify
gem "polaris_view_components", "~> 1.1.0"
gem "shopify_app", "~> 21.6"
gem "shopify_graphql", "~> 1.2"

# frontend
gem "jsbundling-rails"
gem "sprockets-rails"
gem "stimulus-rails"
gem "turbo-rails"

group :development, :test do
  gem "debug", platforms: %i[mri mingw x64_mingw]
  gem "rubocop-rails-omakase", require: false
end

group :development do
  gem "hotwire-livereload"
  gem "pry-rails"
  gem "web-console"
end

group :test do
  gem "capybara"
  gem "selenium-webdriver"
  gem "webdrivers"
end
