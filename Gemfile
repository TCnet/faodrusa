source 'https://rubygems.org'
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby '2.5.1'

# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'rails', '~> 6.0.0'
# Use sqlite3 as the database for Active Record
gem 'sqlite3', '~> 1.4'
# Use Puma as the app server
gem 'puma', '~> 3.11'
# Use SCSS for stylesheets
gem 'sass-rails', '~> 5'
# Transpile app-like JavaScript. Read more: https://github.com/rails/webpacker
gem 'webpacker', '~> 4.0'
# Turbolinks makes navigating your web application faster. Read more: https://github.com/turbolinks/turbolinks
gem 'turbolinks', '~> 5'
# Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder
gem 'jbuilder', '~> 2.7'
# Use Redis adapter to run Action Cable in production
# gem 'redis', '~> 4.0'
# Use Active Model has_secure_password
# gem 'bcrypt', '~> 3.1.7'

# Use Active Storage variant
# gem 'image_processing', '~> 1.2'
gem 'unicorn', '~> 5.5.1'

gem 'spree', '~> 4.0'
gem 'spree_auth_devise', '~> 4.0'
gem 'spree_gateway', '~> 3.6'
gem 'spree_dislu_link', github: 'TCnet/spree_dislu_link'
gem 'spree_dislu_album', github: 'TCnet/spree_dislu_album'
gem 'spree_analytics_trackers', '~> 1.0'
gem 'spree_static_content', github: 'TCnet/spree_static_content'
gem 'spree_variant_options', github: 'TCnet/spree_variant_options'
gem 'spree_i18n', github: 'TCnet/spree_i18n'
gem 'spree_paypal_express', github: 'spree-contrib/better_spree_paypal_express'
gem 'spree_sitemap', github: 'spree-contrib/spree_sitemap'
gem 'whenever', require: false


gem 'rubyzip', '>= 1.2.1', '< 2.0.0'
gem 'roo','~> 2.8.0'
gem 'roo-xls'
gem 'rb-readline'


group :development do
  gem 'capistrano', '~> 3.4.0'
  gem 'capistrano-rails', '~> 1.1.0'
  gem 'capistrano-bundler'
  gem 'capistrano-rbenv', "~> 2.0"
  gem 'capistrano-cookbook', require: false
  
  
end

# Reduces boot times through caching; required in config/boot.rb
gem 'bootsnap', '>= 1.4.2', require: false

group :development, :test do
  # Call 'byebug' anywhere in the code to stop execution and get a debugger console
  gem 'byebug', platforms: [:mri, :mingw, :x64_mingw]
end

group :development do
  # Access an interactive console on exception pages or by calling 'console' anywhere in the code.
  gem 'web-console', '>= 3.3.0'
  gem 'listen', '>= 3.0.5', '< 3.2'
  # Spring speeds up development by keeping your application running in the background. Read more: https://github.com/rails/spring
  gem 'spring'
  gem 'spring-watcher-listen', '~> 2.0.0'
end

group :test do
  # Adds support for Capybara system testing and selenium driver
  gem 'capybara', '>= 2.15'
  gem 'selenium-webdriver'
  # Easy installation and use of web drivers to run system tests with browsers
  gem 'webdrivers'
end

group :production do
  gem 'pg', '0.18.4'
end


# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]
