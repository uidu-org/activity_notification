source 'https://rubygems.org'

gemspec

gem 'rails', '~> 5.2'

group :production do
  gem 'puma'
  gem 'pg'
  gem 'devise'
  gem 'devise_token_auth'
end

group :development do
  gem 'bullet'
end

group :test do
  gem 'rails-controller-testing'
  gem 'action-cable-testing'
  gem 'ammeter'
  gem 'timecop'
  gem 'committee'
  gem 'committee-rails'
  gem 'coveralls', require: false
end

gem 'webpacker', groups: [:production, :development]
gem 'rack-cors', groups: [:production, :development]
gem 'dotenv-rails', groups: [:development, :test]
