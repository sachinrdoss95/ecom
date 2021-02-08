source "https://rubygems.org"

git_source(:github) do |repo_name|
  repo_name = "#{repo_name}/#{repo_name}" unless repo_name.include?("/")
  "https://github.com/#{repo_name}.git"
end

gem "angularjs-rails-resource"
gem 'bootsnap', require: false
gem "carrierwave", "~> 2.1"
gem "cancancan"
gem "font-awesome-rails"
gem 'jquery-rails'
gem 'mini_magick'
gem "rabl", "~> 0.14.2"
gem "rails", "~> 6.0.0"
gem 'ransack'
gem "pg", ">= 0.18", "< 2.0"
gem 'spree', '~> 4.1'
gem 'spree_auth_devise', '~> 4.1'
gem 'spree_gateway', '~> 3.7'
gem "uglifier", ">= 1.3.0"

group :development do
  gem "awesome_print"
  gem "capistrano"
  gem "capistrano-rails"
  gem "capistrano-rvm"
  gem 'faker', :git => 'https://github.com/faker-ruby/faker.git', :branch => 'master'
  gem "listen"
  gem 'meta_request'
  gem "pry"
  gem "spring"
  gem "spring-watcher-listen", "~> 2.0.0"
  gem "web-console", ">= 3.3.0"
end

gem "tzinfo-data", platforms: [:mingw, :mswin, :x64_mingw, :jruby]