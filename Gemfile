source "https://rubygems.org"
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby "3.0.3"

gem "rails", "~> 7.0.1"
gem "pg", "~> 1.1"
gem "puma", "~> 5.0"

gem "sprockets-rails"
gem "jsbundling-rails"
gem "turbo-rails"
gem "stimulus-rails"
gem "cssbundling-rails"

# Use Redis adapter to run Action Cable in production
gem "redis", "~> 4.0"

# Reduces boot times through caching; required in config/boot.rb
gem "bootsnap", require: false

group :development do
  gem "web-console"
  gem "rack-mini-profiler"
end

group :test do
  # Use system testing [https://guides.rubyonrails.org/testing.html#system-testing]
  gem "capybara"
  gem "selenium-webdriver"
  gem "webdrivers"
end

gem "hotwire-livereload", "~> 1.1", :group => :development
