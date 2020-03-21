source 'http://rubygems.org'

gemspec

gem 'rails', '5.2.4.2'

platforms :ruby do
  gem 'sqlite3'

  group :development do
    gem 'unicorn', '~> 4.0.1'
  end

  group :development, :test do
    gem 'jquery-rails', '~> 4.0.5'
    gem 'capybara', '>= 0.4.0'
    gem 'mynyml-redgreen', '~> 0.7.1', require: 'redgreen'
  end

  group :active_record do
    gem 'paperclip', '>= 5.0.0'
    gem 'carrierwave', '>= 0.11.2'
    gem 'dragonfly'
    gem 'mini_magick'
    gem 'refile', require: 'refile/rails'
    gem 'refile-mini_magick'
  end

  group :mongoid do
    gem 'mongoid', '~> 5.0.2'
    gem 'bson_ext'
    gem 'mongoid-paperclip', '0.0.10'
    gem 'carrierwave-mongoid', '0.9.0'
  end
end
