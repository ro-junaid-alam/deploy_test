source 'https://rubygems.org'


gem 'rails', '4.2.2'
gem 'mysql2', '~> 0.3.18'
gem 'sass-rails', '~> 5.0'
gem 'uglifier', '>= 1.3.0'
gem 'coffee-rails', '~> 4.1.0'
gem 'jquery-rails'
gem 'turbolinks'
gem 'jbuilder', '~> 2.0'
gem 'sdoc', '~> 0.4.0', group: :doc
gem 'i18n', '0.7.0'

# Use ActiveModel has_secure_password
# gem 'bcrypt', '~> 3.1.7'

# Use Unicorn as the app server
# gem 'unicorn'

# Use Capistrano for deployment
group :development do
  gem 'capistrano'
  gem 'capistrano-bundler' # this will precompile asset, run migration. need to require asset and migraion in Capfile
  gem 'capistrano-rails'
  gem 'capistrano-rvm', github: "capistrano/rvm"
  gem 'capistrano-passenger' # this will restart passenger, need to require passenger in Capfile
end

group :development, :test do
  #gem 'byebug'
  gem 'web-console', '~> 2.0'
  gem 'spring'
end

