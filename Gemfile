source 'https://rubygems.org'

gem 'rails', '3.2.1'


gem 'sqlite3'

# for deployment on Heroku
gem "heroku"

group :development do
  gem 'rspec-rails', '2.6.1'
end

group :test do
  gem 'rspec-rails', '2.6.1'
  gem 'webrat', '0.7.1'
  gem 'spork', '0.9.0.rc8'
end

group :production do
  gem 'pg'
  gem 'therubyracer-heroku', :platform => :ruby
end

gem 'execjs'

# Gems used only for assets and not required
# in production environments by default.
group :assets do
  gem 'sass-rails',   '~> 3.2.3'
  gem 'coffee-rails', '~> 3.2.1'
  gem 'uglifier', '>= 1.0.3'
end

gem 'jquery-rails'
