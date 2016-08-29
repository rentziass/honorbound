source 'https://rubygems.org'


########## RUBY VERSION
ruby "2.3.1"

########## RAILS VERSION
gem "rails", "5.0.0"

########## DATABASE
  # Use postgresql as the database for Active Record
gem "pg"

########## ASSETS & VIEWS
gem "bower-rails"
gem "sass-rails"
gem "uglifier"
gem "coffee-rails"
gem "slim-rails"
gem "jbuilder", "~> 2.0"
gem "jquery-rails"
gem 'gsdk', '>= 1.0.0.0'


########### PRY
gem "pry"
gem "pry-rails"

########## COLORIZE
gem "colorize"

group :development, :test do
  # Call 'byebug' anywhere in the code to stop execution and get a debugger console
  gem 'byebug', platform: :mri
end

group :development do
  # Access an IRB console on exception pages or by using <%= console %> anywhere in the code.
  gem 'web-console'
  gem 'listen', '~> 3.0.5'
  gem "better_errors", git: "https://github.com/charliesome/better_errors.git"
  gem "binding_of_caller"

  # Spring speeds up development by keeping your application running in the background. Read more: https://github.com/rails/spring
  gem 'spring'
  gem 'spring-watcher-listen', '~> 2.0.0'
end

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]
