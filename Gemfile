source "https://rubygems.org"
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby "3.2.2"
gem "rails", "~> 7.0.0"
gem "sprockets-rails"
gem "pg", "~> 1.1"
gem "puma", "~> 5.0"
gem "importmap-rails"
gem "turbo-rails"
gem "stimulus-rails"
gem "tailwindcss-rails"
gem "jbuilder"
gem "redis", "~> 4.0"
gem "tzinfo-data", platforms: %i[ mingw mswin x64_mingw jruby ]
gem "bootsnap", require: false
gem "rspec-rails", "~> 6.0", :groups => [:development, :test]
gem "slim-rails", "~> 3.6"
gem "sassc-rails"
gem 'devise'


group :development, :test do
  gem "debug", platforms: %i[ mri mingw x64_mingw ]
  gem 'rubocop', require: false
  gem 'rubocop-rails'
  gem 'rubocop-performance'
  gem 'rubocop-rspec'
  gem 'dotenv-rails'
  gem 'brakeman', require: false
end

group :test do
  gem 'factory_bot_rails'
  gem 'faker'
  gem 'shoulda-matchers'
  gem 'capybara'
  gem 'simplecov'
end

group :development do
  gem "web-console"
  gem 'pry-rails'
  gem 'guard'
  gem 'letter_opener'
  gem 'awesome_print'
  gem 'bullet'
  gem 'rack-mini-profiler'
  gem 'rails-erd'
  gem 'rails_best_practices'
end


