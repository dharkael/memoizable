# encoding: utf-8

source 'https://rubygems.org'

gemspec

gem 'rake', '~> 10.1'

group :test do
  gem 'coveralls', '~> 0.7.2'
  gem 'rspec',     '~> 3.1.0'
  gem 'simplecov', '~> 0.9.1'
end

platforms :ruby_18, :jruby do
  gem 'mime-types',  '~> 2.4.3'
  gem 'rest-client', '~> 1.6.7'  # blocked by coveralls
end
