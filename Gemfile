source 'https://rubygems.org'

# Specify your gem's dependencies in conjur.gemspec
gemspec

gem 'conjur-api-dalek', git: 'https://github.com/conjurinc/api-ruby.git', branch: 'dalek'

group :test, :development do
  gem 'pry'
  gem 'ruby-prof'
end


group :development do
  gem 'conjur-asset-environment-api'
  gem 'conjur-asset-key-pair-api'
end