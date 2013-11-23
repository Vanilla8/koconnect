source 'https://rubygems.org'

gem 'rails', '4.0.1'
gem 'bootstrap-sass', '~> 3.0.2.1'
gem 'bcrypt-ruby', '~> 3.1.2'
gem 'faker', '~> 1.2.0'
gem 'will_paginate', '~> 3.0.5'
gem 'bootstrap-will_paginate', '~> 0.0.10'
gem 'jquery-rails'
gem 'turbolinks'
gem 'jbuilder', '~> 1.2'

group :doc do
  # bundle exec rake doc:rails generates the API under doc/api.
  gem 'sdoc', require: false
end

group :development, :test do
  gem 'sqlite3'
  gem 'rspec-rails', '~> 2.14.0'
  # gem 'guard-rspec', '1.2.1'
  # gem 'guard-spork', '1.2.0'
  # gem 'childprocess', '0.3.6'
  # gem 'spork', '0.9.2'
end

# Gems used only for assets and not required
# in production environments by default.
group :assets do
  gem 'sass-rails',   '~> 4.0.0'
  gem 'coffee-rails', '~> 4.0.0'
  gem 'uglifier', '>= 1.3.0'
end

group :test do
  gem 'capybara', '~> 2.2.0'
  gem 'factory_girl_rails', '~> 4.3.0'
  gem 'cucumber-rails', '~> 1.4.0', :require => false
  gem 'database_cleaner', '~> 1.2.0'
  # gem 'launchy', '2.1.0'
  # gem 'rb-fsevent', '0.9.1', :require => false
  # gem 'growl', '1.0.3'
end

group :production do
  gem 'pg'
  gem 'rails_12factor'
end
