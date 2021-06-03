source 'https://rubygems.org'
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby '2.6.5'

# Core
gem 'rails', '~> 6.1.3', '>= 6.1.3.2'
# Config
gem 'dotenv-rails', '~> 2.2'
gem 'rails-i18n'
gem 'config'
#Middleware
gem 'puma', '~> 5.0'
gem 'pg', '~> 1.1'
# Use Puma as the app server
#View/Front
gem 'webpacker', '~> 5.0'
gem 'coffee-rails', '~> 5.0'
gem 'jquery-rails'
gem 'haml-rails', '~> 2.0', '>= 2.0.1'
gem 'sass-rails', '>= 6'
# Backend
gem 'devise'
gem 'jbuilder', '~> 2.7'
gem 'enumerize'
gem 'omniauth'
gem 'omniauth-twitter'
gem 'omniauth-github'
gem 'carrierwave'
gem 'cloudinary'
gem 'gon'
gem 'jquery-rails'
gem 'turbolinks', '~> 5'
# Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder

# Reduces boot times through caching; required in config/boot.rb

group :development, :test do
  # Call 'byebug' anywhere in the code to stop execution and get a debugger console
  gem 'byebug', platforms: [:mri, :mingw, :x64_mingw]
end

group :development do
  # Access an interactive console on exception pages or by calling 'console' anywhere in the code.
  gem 'web-console', '>= 4.1.0'
  # Display performance information such as SQL time and flame graphs for each request in your browser.
  # Can be configured to work on production as well see: https://github.com/MiniProfiler/rack-mini-profiler/blob/master/README.md
  gem 'rack-mini-profiler', '~> 2.0'
  gem 'listen', '~> 3.3'
  # Spring speeds up development by keeping your application running in the background. Read more: https://github.com/rails/spring
  gem 'spring'
end

group :test do
  # Adds support for Capybara system testing and selenium driver
  gem 'capybara', '>= 3.26'
  gem 'selenium-webdriver'
  # Easy installation and use of web drivers to run system tests with browsers
  gem 'webdrivers'
end

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]
