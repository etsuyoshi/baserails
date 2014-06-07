source 'https://rubygems.org'

# Ruby 2.0.0 on Heroku
# Heroku で Rails 4 を使うために下の一行が必須です
ruby "2.0.0"

# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'rails', '4.0.0.rc1'

### Development and Test Setting
# 開発環境とテスト環境では sqlite3 を使うようにします
group :development, :test do
  # Use sqlite3
  gem 'sqlite3'

  # Testing framework
  gem 'rspec-rails'

  # Speeding up Testing
  gem 'spork'

  # Detect the change of file for OSX
  gem 'rb-fsevent'
end

### Development Setting
group :development do
  gem 'heroku'
 
  # Manage Procfile-based applications
  gem 'foreman'

  # Auto reload the browser when files are changed
  # ブラウザのオートロード
  gem 'guard-livereload'

  # Use debugger
  gem 'pry-rails'
end

### Production Setting
# Heroku は PostgreSQL が必須です
group :production do
  gem 'pg' # Heroku use PostgreSQL
end

# Use SCSS for stylesheets
gem 'sass-rails', '~> 4.0.0.rc1'

# Use Uglifier as compressor for JavaScript assets
gem 'uglifier', '>= 1.3.0'

# Use CoffeeScript for .js.coffee assets and views
gem 'coffee-rails', '~> 4.0.0'

# See https://github.com/sstephenson/execjs#readme for more supported runtimes
# gem 'therubyracer', platforms: :ruby

# Use jquery as the JavaScript library
gem 'jquery-rails'

# Use Haml
gem 'haml-rails'

# Turbolinks makes following links in your web application faster. Read more: https://github.com/rails/turbolinks
gem 'turbolinks'

# Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder
gem 'jbuilder', '~> 1.0.1'

group :doc do
  # bundle exec rake doc:rails generates the API under doc/api.
  gem 'sdoc', require: false
end