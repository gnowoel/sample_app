source 'https://rubygems.org'

ruby '1.9.3'

gem 'rails', '3.2.13'
gem 'bootstrap-sass', '2.3.2.0'
gem 'bcrypt-ruby', '3.0.1'
gem 'jquery-rails', '2.0.2'

group :assets do
  gem 'sass-rails', '3.2.5'
  gem 'coffee-rails', '3.2.2'
  gem 'uglifier', '1.2.3'
end

group :development, :test do
  gem 'sqlite3', '1.3.5'
  gem 'rspec-rails', '2.11.0'
  gem 'guard-rspec', '1.2.1'
  gem 'guard-spork', '1.5.1'
  gem 'childprocess', '0.3.9'
  gem 'spork', '0.9.2'
end

group :test do
  gem 'capybara', '1.1.2'
  gem 'terminal-notifier-guard', '1.5.3'
  gem 'factory_girl_rails', '4.2.1'
  gem 'cucumber-rails', '1.3.1', :require => false
  gem 'database_cleaner', '1.0.1'
end

group :production do
  gem 'pg', '0.12.2'
end
