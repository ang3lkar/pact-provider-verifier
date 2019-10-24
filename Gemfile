source 'https://rubygems.org'

gemspec

gem "pact-message", git: "https://github.com/ang3lkar/pact-message-ruby"

if ENV['X_PACT_DEVELOPMENT']
  gem "pact", path: '../pact'
  gem "pact-message", path: '../pact-message-ruby'
  gem "pact-support", path: '../pact-support'
end
