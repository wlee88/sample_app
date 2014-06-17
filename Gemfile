source 'https://rubygems.org'

# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'rails', '4.1.1'
gem 'bootstrap-sass', '2.3.2.0'
gem 'sprockets', '2.11.0'
group :test do
  gem 'selenium-webdriver', '2.35.1'
  gem 'capybara', '2.1.0'
  gem 'factory_girl_rails', '4.2.1'
end

group :development do
  gem 'sqlite3', '1.3.8'
  gem 'rspec-rails','2.13.1'
  gem 'guard-rspec', '2.5.0'
end

group :test, :development do
	gem 'minitest'
end


gem 'sass-rails', '~> 4.0.3'
gem 'uglifier', '>= 1.3.0'
gem 'coffee-rails', '~> 4.0.0'
gem 'jquery-rails'
gem 'turbolinks'
gem 'jbuilder', '~> 2.0'
gem 'sdoc', '~> 0.4.0',          group: :doc

# Spring speeds up development by keeping your application running in the background. Read more: https://github.com/rails/spring
gem 'spring',        group: :development

 gem 'bcrypt', '~> 3.1.7'
group :production do
  gem 'pg', '0.15.1'
  gem 'rails_12factor', '0.0.2'
end

group:test do
  gem 'cucumber-rails', '1.4.0', :require => false
  gem 'database_cleaner', github: 'bmabey/database_cleaner'
end
