source 'https://rubygems.org'

# FRAMEWORK
gem 'rails', '4.2.5.1'
gem 'configoro'
gem 'responders'

# MODELS
gem 'pg'
gem 'paperclip'

# ASSETS
gem 'sass-rails'
gem 'less-rails'
gem 'uglifier'
gem 'coffee-rails'
gem 'therubyracer', platforms: :ruby
gem 'jquery-rails'
gem 'turbolinks'
gem 'font-awesome-rails'
gem 'sprockets-rails'

# VIEWS
gem 'jbuilder'
gem 'slim-rails'
gem 'nokogiri'

# IMPORTING
gem 'sqlite3'

# CRON
gem 'whenever'

group :development do
  #DEPLOYMENT
  gem 'capistrano-rvm'
  gem 'capistrano-bundler'
  gem 'capistrano-rails'
  gem 'capistrano-passenger'

  # DEVELOPMENT
  gem 'spring'
  gem 'web-console'
end

group :doc do
  gem 'yard', require: false
  gem 'redcarpet', require: 'false'
end

group :test do
  gem 'rspec-rails'
  gem 'rspec-its', require: 'rspec/its'
  gem 'factory_girl_rails'
  gem 'database_cleaner'
end

group :production do
  gem 'aws-sdk', '< 2.0' # incompatible with Paperclip < 5
end
