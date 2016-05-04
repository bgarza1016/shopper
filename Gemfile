source 'https://rubygems.org'


gem 'rails', '4.2.4'
gem 'pg'
gem 'sass-rails', '~> 5.0'
gem 'uglifier', '>= 1.3.0'
gem 'coffee-rails', '~> 4.1.0'
gem 'jquery-rails'
gem 'jbuilder', '~> 2.0'
gem 'sass', '3.2.19'
gem 'bower-rails'
gem 'angular-rails-templates'

gem "foreman"
group :production, :staging do
	gem "rails_12factor"
	gem "rails_stdout_logging"
	gem "rails_serve_static_assets"
end

group :test, :development do
	gem "rspec-rails", "~> 2.0"
	gem "factory_girl_rails", "~> 4.0"
	gem "capybara"
	gem "database_cleaner"
	gem "selenium-webdriver"
end
gem 'sdoc', '~> 0.4.0', group: :doc

group :development, :test do
  gem 'byebug'
end

group :development do
  gem 'web-console', '~> 2.0'
  gem 'spring'
end

