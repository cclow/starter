source 'https://rubygems.org'

gem 'rails', '3.2.9'

# Bundle edge Rails instead:
# gem 'rails', :git => 'git://github.com/rails/rails.git'

gem 'sqlite3'


# Gems used only for assets and not required
# in production environments by default.
group :assets do
  gem 'sass-rails',   '~> 3.2.3'
  gem 'coffee-rails', '~> 3.2.1'

  # Need JS runtime for compiling assets
  # See https://github.com/sstephenson/execjs#readme for more supported runtimes
  gem 'therubyracer', :platforms => :ruby

  gem 'uglifier', '>= 1.0.3'
end

gem 'jquery-rails'

# Using haml as HTML template
gem 'haml-rails'

# To use ActiveModel has_secure_password
# gem 'bcrypt-ruby', '~> 3.0.0'

# To use Jbuilder templates for JSON
# gem 'jbuilder'

# Use unicorn as the app server
# gem 'unicorn'

# Deploy with Capistrano
# gem 'capistrano'

# To use debugger
# gem 'debugger'

group :development, :test do
  # Use Rspec for rails testing framework
  gem 'rspec-rails'

  # Random test data generator
  gem 'faker'

  # Fixture replacement, test object factory
  gem 'factory_girl_rails'

  # Turn off assets pipeline logging
  gem 'quiet_assets'
end

group :development do
  # guards for bundler, migrate, and rspec
  gem 'guard-bundler'
  gem 'guard-migrate'
  gem 'guard-rspec'

  # OS X file system event monitoring
  gem 'rb-fsevent'

  # Notification gem for OS X 10.8 notifications
  gem 'terminal-notifier-guard'

  # Profiling tool for client-side, DB and server
  gem 'rack-mini-profiler'

  # DB optimisation tool
  gem 'bullet'
end

group :test do
  # Additional Rails matchers from thoughtbot
  gem 'shoulda-matchers'

  # Capybara for web application testing
  # also requires dependencies which are strangely not speced into the gem
  gem 'capybara'
  gem 'nokogiri'
  gem 'xpath'

  # Launchy for open_and_save_page support
  gem 'launchy'

  # DatabaseCleaner manages the database cleaning strategies between tests
  gem 'database_cleaner'
end
