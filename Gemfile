source 'https://rubygems.org'

# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'rails', '~> 4.2.7'
# Use postgresql as the database for Active Record
gem 'pg'
gem 'sdoc', '~> 0.4.0', group: :doc
# Use Unicorn as the app server
gem 'unicorn'
# Use Taperole for deployment
gem 'taperole'
gem 'devise_token_auth'

# Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder
# gem 'jbuilder', '~> 2.0'
# Use serializers to format json data
# gem 'active_model_serializers'
# Use active_interaction to manage business logic in a service layer
# gem 'active_interaction'
# bundle exec rake doc:rails generates the API under doc/api.
# Use rack-cors to make CORS requests from the browser client
# gem 'rack-cors', require: 'rack/cors'

group :development, :test do
  # Use smashing_docs for API documentation
  gem 'smashing_docs'
  # Use rspec as the testing framework
  gem 'rspec-rails'
  # Use factory girl for fixtures
  gem 'factory_girl_rails'
  # Use database cleaner for cleaning the database
  gem 'database_cleaner'
  # Call 'binding.pry' anywhere in the code to stop execution and get a debugger console
  gem 'pry-byebug'
  # Use awesome-print to pretty print Ruby objects
  gem 'awesome_print'
  # Use rubocop for linting
  gem 'rubocop'
  # Use shouldamatchers to test associations and validations
  gem 'shoulda-matchers'
  # Use to integrate Code Climate and Travis
  gem "simplecov"
  gem "codeclimate-test-reporter", "~> 1.0.0"
end

group :development do
  gem 'listen', '~> 3.0.5'
  # Use letter_opener to view emails in browser rather than send
  # gem 'letter_opener'
  # Use better_errors to get a full stack trace
  gem "better_errors"
  # Access an IRB console on exception pages or by using <%= console %> in views
  gem 'web-console', '~> 2.0'
  # Spring speeds up development by keeping your application running in the background. Read more: https://github.com/rails/spring
  gem 'spring'
end
