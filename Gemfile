source 'https://rubygems.org'
#ruby-gemset=railstutorial_rails_4_0

gem 'rails', '4.0.2'
group :development do
	gem 'guard'
	gem 'guard-minitest'
	gem 'guard-bundler', require: false
end

group :development, :test do
  gem 'sqlite3'
  gem 'rspec-rails'
  gem 'guard-rspec', require: false
  gem 'spork-rails'
  gem 'guard-spork'
  gem 'childprocess'
end

group :test do
  gem 'selenium-webdriver'
  gem 'capybara'

  # OS X: раскомментируйте эти строки.
  # gem 'growl', '1.0.3'

  # Linux: раскомментируйте эти строки.
  # gem 'libnotify', '0.8.0'

  # Windows: раскомментируйте эти строки.
  # gem 'rb-notifu', '0.0.4'
  # gem 'win32console', '1.3.2'
  # gem 'wdm', '0.1.0'
end

gem 'sass-rails'
gem 'uglifier'
gem 'coffee-rails'
gem 'jquery-rails'
gem 'turbolinks'
gem 'jbuilder'

group :doc do
  gem 'sdoc', '0.3.20', require: false
end

group :production do
  gem 'pg', '0.15.1'
  gem 'rails_12factor'
end