require 'rbconfig'
HOST_OS = RbConfig::CONFIG['host_os']
source 'https://rubygems.org'

gem 'rails'
gem 'pg'

gem 'oj'
gem 'capistrano'
gem 'unicorn', group: :production
gem 'foreman'

group :assets do
  gem 'sass-rails'
  gem 'bootstrap-sass'
  gem 'coffee-rails'
  gem 'handlebars_assets'
  gem 'uglifier'
  gem 'font-awesome-sass-rails'
  gem 'yui-compressor'
  gem "therubyracer", platform: :ruby
end

group :development do
  gem 'thin'
  gem 'taps', require: false
  gem 'sqlite3'
  gem "guard"
  gem "guard-bundler"
  gem "guard-rails"
  gem "guard-livereload"
  gem "guard-rspec"
  gem 'quiet_assets'
end

group :test do
  gem 'faker'
  gem 'fakeweb'
  gem 'capybara'
  gem 'launchy'
  gem 'spork'
  gem "database_cleaner"
  gem 'guard-spork'
  gem 'shoulda', require: false
  gem "email_spec"
  gem 'simplecov', require: false
end

gem 'jquery-rails'
gem 'jquery-ui-themes'
gem 'blankslate', git: 'https://github.com/masover/blankslate.git'
gem 'select2-rails'
gem "haml"
gem "haml-rails", :group => :development
gem "rspec-rails", ">= 2.10.1", :group => [:development, :test]
gem "factory_girl_rails", ">= 3.3.0", :group => [:development, :test]
gem "hominid"
gem "devise"
gem "devise_invitable"
gem "cancan"
gem "simple_form"
gem 'mini_magick'
gem 'rabl'
gem 'heroku'
gem 'fog', '1.11.1'
gem 'symbolize', "4.2.0", require: 'symbolize/active_record'
gem 'kaminari'
gem 'bootstrap_kaminari', git: 'git://github.com/dleavitt/bootstrap_kaminari.git'
gem 'hominid'
gem 'hipchat'
gem 'carrierwave'
gem 'geocoder'
gem 'bitmask_attributes'
gem 'country_select'
gem 'rb-readline'
gem 'koala'
gem 'acts-as-taggable-on'
gem 'meta-tags', :require => 'meta_tags'
gem "friendly_id"
gem "green_monkey"
gem 'omniauth'
gem 'omniauth-linkedin'
gem 'linkedin'
