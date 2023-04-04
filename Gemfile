# frozen_string_literal: true

source "https://rubygems.org"
ruby "2.3.7"

gem "activesupport", ">= 6.1.7.3"
gem "figaro"
gem "honeybadger"
gem "httparty", ">= 0.21.0"
gem "nokogiri", "~> 1.13.9"
gem "rake", ">= 12.3.3"
gem "redis"
gem "require_all"
gem "resque", "~> 2.0.0"
gem "rubocop", "~> 0.49.1", require: false
gem "thor"

group :test do
  gem "rspec"
end

group :development, :test do
  gem "rspec_junit_formatter"
end
