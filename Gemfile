source 'https://rubygems.org'
ruby '2.0.0'

# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'rails', '4.0.0'
gem 'bootstrap-sass', '2.3.2.0'
gem 'bcrypt-ruby', '3.0.1'

group :development, :test do
# Use sqlite3 as the database for Active Record
  gem 'sqlite3', '1.3.7'
  gem 'rspec-rails', '2.13.1' #RSpec test unit gem
  gem 'guard-rspec', '2.5.0' #gem for Guard automated tests
  gem 'spork-rails', github: 'sporkrb/spork-rails'
  gem 'guard-spork', :github => 'guard/guard-spork'
  gem 'childprocess', '0.3.6'
end

group :test do
  gem 'selenium-webdriver', '2.0.0' # Capybara dependency
  gem 'capybara', '2.1.0' #simulates user interaction using natural English-like syntax
  gem 'growl', '1.0.3'
  gem 'factory_girl_rails', '4.2.1'
end


# Use SCSS for stylesheets
gem 'sass-rails', '4.0.0'

# Use Uglifier as compressor for JavaScript assets
gem 'uglifier', '2.1.1'

# Use CoffeeScript for .js.coffee assets and views
gem 'coffee-rails', '4.0.0'

# Use jquery as the JavaScript library
gem 'jquery-rails', '2.1.1'

# Turbolinks makes following links in your web application faster. Read more: https://github.com/rails/turbolinks
gem 'turbolinks', '1.1.1'

# Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder
gem 'jbuilder', '1.0.2'

group :doc do
  # bundle exec rake doc:rails generates the API under doc/api.
  gem 'sdoc', require: false
end

group :production do
  gem 'pg', '0.15.1'
  gem 'rails_12factor', '0.0.2'
end
# Use ActiveModel has_secure_password
# gem 'bcrypt-ruby', '~> 3.0.0'

# Use unicorn as the app server
# gem 'unicorn'

# Use Capistrano for deployment
# gem 'capistrano', group: :development

# Use debugger
# gem 'debugger', group: [:development, :test]