source 'https://rubygems.org'

ruby '2.3.0'

# Require 'rails' first otherwise Rails plugins won't work.
gem 'rails', '4.2.5'

gem 'bcrypt', '~> 3.1.7'
gem 'pg', '~> 0.15'
gem 'pry-rails'
gem 'jwt'
gem 'thin'

group :production do
  gem 'rails_12factor'
end

group :development, :test do
  gem 'byebug'
end

group :test do
  gem 'rspec-rails'
end
