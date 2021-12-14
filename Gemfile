# frozen_string_literal: true

source 'https://rubygems.org'
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby '3.0.3'

gem 'bootsnap', '>= 1.4.4', require: false
gem 'cssbundling-rails', '>= 0.2.7'
gem 'jsbundling-rails', '>= 0.2.2'
gem 'pg', '~> 1.1'
gem 'puma', '~> 5.0'
gem 'rails', '~> 7.0.0.rc3'
gem 'sprockets-rails', '>= 3.4.1'
gem 'stimulus-rails', '>= 0.7.3'
gem 'turbo-rails', '>= 0.9.0'

group :development, :test do
  gem 'debug', '>= 1.0.0', platforms: %i[mri mingw x64_mingw]
  gem 'dotenv-rails'
  gem 'factory_bot_rails'
  gem 'faker'
  gem 'rubocop'
  gem 'rubocop-minitest'
  gem 'rubocop-performance'
  gem 'rubocop-rails'
end

group :development do
  gem 'brakeman', '~> 5.1'
  gem 'bundler-audit', require: false
  gem 'letter_opener'
  gem 'web-console', '>= 4.1.0'
end

group :test do
  gem 'capybara', '>= 3.26'
  gem 'selenium-webdriver', '>= 4.0.0'
  gem 'webdrivers'
end
