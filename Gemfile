require 'rbconfig'
HOST_OS = RbConfig::CONFIG['host_os']
source 'http://rubygems.org'
gem 'rails', '3.1.1'
gem 'sqlite3'
group :assets do
  gem 'sass-rails',   '~> 3.1.4'
  gem 'coffee-rails', '~> 3.1.1'
  gem 'uglifier', '>= 1.0.3'
end
gem 'jquery-rails'
if HOST_OS =~ /linux/i
  gem 'therubyracer', '>= 0.8.2'
end
gem "rspec-rails", ">= 2.6.1", :group => [:development, :test]
gem "devise", ">= 1.4.7"
gem "frontend-helpers"
