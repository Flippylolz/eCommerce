source 'https://rubygems.org'

git_source(:github) do |repo_name|
  repo_name = "#{repo_name}/#{repo_name}" unless repo_name.include?("/")
  "https://github.com/#{repo_name}.git"
end

gem 'rails', '~> 5.0.2'

gem 'spree', '~> 3.2.0'
gem 'spree_auth_devise', '~> 3.2'
gem 'spree_gateway', '~> 3.2'

gem 'pg', '~> 0.18'
gem 'puma', '~> 3.0'
gem 'sass-rails', '~> 5.0'
gem 'uglifier', '>= 1.3.0'
gem 'coffee-rails', '~> 4.2'
gem 'therubyracer', platforms: :ruby
gem 'jquery-rails'
gem 'turbolinks', '~> 5'
gem 'jbuilder', '~> 2.5'

group :development do
  gem 'web-console', '>= 3.3.0'
  gem 'listen', '~> 3.0.5'
  gem 'spring'
  gem 'spring-watcher-listen', '~> 2.0.0'

  gem 'capistrano',         '3.6.1', require: false
  gem 'capistrano-rvm',     '0.1.2', require: false
  gem 'capistrano-rails',   '1.2.0', require: false
  gem 'capistrano-bundler', '1.2.0', require: false
  gem 'capistrano3-puma',   '1.2.1', require: false
  gem 'capistrano-rake',    '0.1.0', require: false
end

gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]
