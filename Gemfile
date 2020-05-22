source 'https://rubygems.org'

gem 'will_paginate',           '3.1.0'
gem 'bootstrap-will_paginate', '0.0.10'
gem 'zeroclipboard-rails', '~> 0.1.2'
gem 'jquery-tablesorter', '~> 1.23', '>= 1.23.5'
# Scheduler
gem 'whenever', :require => false
# For awesome developer fonts
gem "font-awesome-rails", ">= 4.7.0.1"
# For awesome bootstrap social buttons
gem 'bootstrap-social-rails', '>= 4.12.0'
# For token scraping for google login
gem 'httpclient'
# bootstrap
gem 'bootstrap-sass'
# poke-api
gem 'poke-go-api',
  git: "https://github.com/nabeelamjad/poke-api.git"
# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'rails', '~> 5.0.1'
# Use Puma as the app server
gem 'puma', '~> 3.12', '>= 3.12.6'
# Use SCSS for stylesheets
gem 'sass-rails', '~> 5.0', '>= 5.0.6'
# Use Uglifier as compressor for JavaScript assets
gem 'uglifier', '>= 1.3.0'
# Use CoffeeScript for .coffee assets and views
gem 'coffee-rails', '~> 4.2', '>= 4.2.1'
# See https://github.com/rails/execjs#readme for more supported runtimes
# gem 'therubyracer', platforms: :ruby

# Use jquery as the JavaScript library
gem 'jquery-rails', '>= 4.2.2'
# Turbolinks makes navigating your web application faster. Read more: https://github.com/turbolinks/turbolinks
gem 'turbolinks', '~> 5'
# Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder
gem 'jbuilder', '~> 2.5'
# Use Redis adapter to run Action Cable in production
# gem 'redis', '~> 3.0'
# Use ActiveModel has_secure_password
# gem 'bcrypt', '~> 3.1.7'

group :development, :test do
  # Call 'byebug' anywhere in the code to stop execution and get a debugger console
  gem 'byebug', platform: :mri
end

group :development do
  # Access an IRB console on exception pages or by using <%= console %> anywhere in the code.
  gem 'web-console', '>= 3.4.0'
  gem 'listen', '~> 3.0.5'
  # Spring speeds up development by keeping your application running in the background. Read more: https://github.com/rails/spring
  gem 'spring'
  gem 'spring-watcher-listen', '~> 2.0.0'
  gem 'sqlite3'
  # for GCE deploy
  gem 'capistrano', '~> 3.6'
  gem 'capistrano-rails', '~> 1.1', '>= 1.1.7'
  gem 'capistrano-rvm', '~> 0.1.2'
  gem 'capistrano-passenger'
  gem 'capistrano-rails-collection'
end

group :production do
  # Use postgres the database for Active Record
  gem 'pg'
end

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]
