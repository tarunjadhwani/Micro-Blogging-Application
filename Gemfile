source 'https://rubygems.org'
ruby '2.0.0'

gem 'rails', '4.0.0.beta1'
gem 'bootstrap-sass', '2.3.0.1'
gem 'bcrypt-ruby', '3.0.1'
gem 'faker', '1.1.2'
gem 'will_paginate', '3.0.4'
gem 'bootstrap-will_paginate', '0.0.9'

group :development, :test do
  gem 'sqlite3', '1.3.7'
  gem 'rspec-rails', '2.13.0'
  gem 'guard-rspec', '2.5.0'
  gem 'guard-spork', '1.5.0'
end

group :test do
  gem 'xpath',    github: 'jnicklas/xpath'
  gem 'capybara', github: 'jnicklas/capybara'
  gem 'rb-fsevent', '0.9.3', :require => false
  gem 'growl', '1.0.3'
  gem 'launchy', '2.2.0'
  gem 'factory_girl_rails', '4.2.0'
  gem 'cucumber-rails', '1.3.0', :require => false
  gem 'database_cleaner', github: 'bmabey/database_cleaner'
end

group :assets do
  gem 'sass-rails',   '4.0.0.beta1'
  gem 'coffee-rails', '4.0.0.beta1'
  gem 'uglifier', '1.0.3'
end

gem 'jquery-rails', '2.2.1'
gem 'turbolinks', '1.0.0'
gem 'jbuilder', '1.0.1'

group :production do
    gem 'pg', '0.15.1'
    gem 'rails_12factor', '0.0.2'
end