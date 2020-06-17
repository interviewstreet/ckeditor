source 'http://rubygems.org'

gemspec

gem 'rails', '5.0.0'

platforms :ruby do
  gem 'sqlite3'

  group :development do
    gem 'unicorn', '~> 4.0.1'
  end

  group :development, :test do
    gem 'jquery-rails', '~> 4.4.0'
    gem 'capybara', '>= 2.7.1'
    gem 'mynyml-redgreen', '~> 0.7.1', require: 'redgreen'
  end

  group :active_record do
    gem 'paperclip'
    gem 'carrierwave'
    gem 'dragonfly', '>= 1.0.12'
    gem 'mini_magick'
    gem 'refile', '>= 0.6.2', require: 'refile/rails'
    gem 'refile-mini_magick', '>= 0.2.0'
  end

  group :mongoid do
    gem 'mongoid', '~> 5.0.0'
    gem 'bson_ext'
    gem 'mongoid-paperclip', require: 'mongoid_paperclip'
    gem 'carrierwave-mongoid', require: 'carrierwave/mongoid'
  end
end
