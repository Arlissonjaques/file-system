source 'https://rubygems.org'
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby '2.6.3'

# Bundle edge Rails instead: gem 'rails', github: 'rails/rails', branch: 'main'
gem 'rails', '~> 6.1.4', '>= 6.1.4.6'
# Use postgresql as the database for Active Record
gem 'pg', '~> 1.1'
# Use Puma as the app server
gem 'puma', '~> 5.0'
# Use SCSS for stylesheets
gem 'sass-rails', '>= 6'
# Transpile app-like JavaScript. Read more: https://github.com/rails/webpacker
gem 'webpacker', '~> 5.0'
# Turbolinks makes navigating your web application faster. Read more: https://github.com/turbolinks/turbolinks
gem 'turbolinks', '~> 5'
# Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder
gem 'jbuilder', '~> 2.7'
# Reduces boot times through caching; required in config/boot.rb
gem 'bootsnap', '>= 1.4.4', require: false
# Bootstrap rubygem for Rails. Read more: https://github.com/twbs/bootstrap-rubygem
gem 'bootstrap', '~> 5.1.3'
# A gem to automate using jQuery with Rails. Read more: https://github.com/rails/jquery-rails
gem 'jquery-rails'

group :test do
  # Call 'byebug' anywhere in the code to stop execution and get a debugger console
  gem 'pry', platforms: [:mri, :mingw, :x64_mingw]
  # RSpec for Rails 5+. Read more: https://github.com/rspec/rspec-rails
  gem 'rspec-rails', '~> 5.0.0'
  # Simple one-liner tests for common Rails functionality. Read more: https://github.com/thoughtbot/shoulda-matchers
  gem 'shoulda-matchers', '~> 4.0'
  # A Ruby code quality reporter. Read more: https://github.com/whitesmith/rubycritic
  gem 'rubycritic', require: false
  # Code coverage for Ruby with a powerful configuration library. Read more: https://github.com/simplecov-ruby/simplecov
  gem 'simplecov', require: false
  # factories. Read more: https://github.com/thoughtbot/factory_bot_rails
  gem 'factory_bot_rails'
  # A library for generating fake data such as names, addresses, and phone numbers. Read more: https://github.com/faker-ruby/faker
  gem 'faker'
end

group :development do
  # Access an interactive console on exception pages or by calling 'console' anywhere in the code.
  gem 'web-console', '>= 4.1.0'
  # Display performance information such as SQL time and flame graphs for each request in your browser.
  # Can be configured to work on production as well see: https://github.com/MiniProfiler/rack-mini-profiler/blob/master/README.md
  gem 'rack-mini-profiler', '~> 2.0'
  gem 'listen', '~> 3.3'
  # Spring speeds up development by keeping your application running in the background. Read more: https://github.com/rails/spring
  gem 'spring'
end

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]
