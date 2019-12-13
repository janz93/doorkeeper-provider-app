# frozen_string_literal: true

source "http://rubygems.org"

ruby "2.6.2"

gem "rails", "~> 6.0"
gem "doorkeeper", "~> 5.2.3"
gem "devise", "~> 4.7"

gem "faker"
gem "jquery-rails"

gem "coderay"
gem "redcarpet"

gem "uglifier"
gem "pg", "~> 1.1", group: :production
gem "rollbar"

gem "puma"
gem "rack-timeout"

group :development do
  gem "listen"
  gem "rubocop-performance"
  gem "rubocop-rails_config"
end

group :test do
  gem "rspec-rails"
  gem "factory_bot_rails"
  gem "database_cleaner"
end

group :development, :test do
  gem "sqlite3"
  gem "pry-rails"
end
