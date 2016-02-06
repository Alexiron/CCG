source 'https://rubygems.org'
ruby '2.3.0'

gem 'rails', '4.2.5.1' #4.0.2
gem 'bootstrap-sass' #'2.3.2.0'
gem 'bcrypt', '~> 3.1.7' #'bcrypt-ruby', '3.1.2'
gem 'faker' # '1.1.2'
gem 'will_paginate' # '3.0.4'
gem 'bootstrap-will_paginate' # '0.0.9'
gem 'pg', '~> 0.15' #0.15

gem 'chartkick'
gem 'sass-rails', '~> 5.0' #4.0.1
gem 'uglifier', '>= 1.3.0' #2.1.1
gem 'coffee-rails', '~> 4.1.0' #'4.0.1'
gem 'jquery-rails' #3.0.4
# Turbolinks makes following links in your web application faster. Read more: https://github.com/rails/turbolinks
gem 'turbolinks' #1.1.1
# Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder
gem 'jbuilder', '~> 2.0' #1.0.2
# bundle exec rake doc:rails generates the API under doc/api.
gem 'sdoc', '~> 0.4.0', group: :doc #0.3.20

# See https://github.com/rails/execjs#readme for more supported runtimes
# gem 'therubyracer', platforms: :ruby

# Use Unicorn as the app server
# gem 'unicorn'

# Use Capistrano for deployment
# gem 'capistrano-rails', group: :development

group :development, :test do
  # Call 'byebug' anywhere in the code to stop execution and get a debugger console
  gem 'byebug'
  gem 'rspec-rails' #'2.13.1'
end

group :development do
  # Access an IRB console on exception pages or by using <%= console %> in views
  gem 'web-console', '~> 2.0'
  # Spring speeds up development by keeping your application running in the background. Read more: https://github.com/rails/spring
  gem 'spring'
end

group :test do
  gem 'selenium-webdriver' # '2.35.1'
  gem 'capybara' #'2.1.0'
  gem 'factory_girl_rails' # '4.2.0'
  gem 'cucumber-rails', :require => false # '1.4.0'
  gem 'database_cleaner', github: 'bmabey/database_cleaner'
end

group :production do
  gem 'rails_12factor'#, '0.0.2'
end
