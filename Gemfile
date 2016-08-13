# frozen_string_literal: true
source 'https://rubygems.org'

ruby '2.3.1'

gem 'activesupport', '~> 5.0'

group :test do
  gem 'rspec', '~> 3.0'
  gem 'rubocop', '~> 0.41'
  gem 'simplecov', require: false, group: :test
end

group :development, :test do
  gem 'pry-byebug', github: 'deivid-rodriguez/pry-byebug'
end

group :doc do
  gem 'yard'
end
