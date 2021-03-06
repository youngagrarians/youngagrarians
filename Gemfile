source 'https://rubygems.org'
ruby '1.9.3'

gem 'rails', '3.2.12'
gem 'rake', '~> 10.0.4'

# Bundle edge Rails instead:
# gem 'rails', :git => 'git://github.com/rails/rails.git'

gem 'mysql2'
gem 'ejs'
# Gems used only for assets and not required
# in production environments by default.
gem 'thin'

group :assets do
	gem 'sass-rails',   '~> 3.2.3'
	gem 'coffee-rails', '~> 3.2.1'
  # Add Foundation Here
  gem 'compass-rails' # you need this or you get an err
  gem 'foundation-rails'
  gem 'font-awesome-rails'
	gem 'eco'
	gem 'marionette-rails'
	gem 'haml'
	gem 'sass'
	gem 'uglifier', '>= 1.0.3'

	gem 'modernizr-rails'
end

gem 'gmaps4rails'
gem 'geocoder'

gem 'jquery-rails'
gem 'spreadsheet', '~> 0.8.3'
gem 'bcrypt-ruby', '~> 3.0.0'
gem 'warden',                 '~> 1.2.1'
gem 'rails_admin'
gem "rails_admin_import", :git => "git://github.com/yagudaev/rails_admin_import.git"

group :development, :test do
	gem 'rb-readline',					'~> 0.4.2'
	gem 'quiet_assets'

	gem 'better_errors'
	gem 'binding_of_caller'

	gem 'randexp',              '~> 0.1.7'
	gem 'awesome_print',        '~> 1.0.2'
	gem 'table_print',          '~> 1.0.0'
	gem 'pry'

	# Guard, guard!
	gem 'guard',                '~> 1.3.2'
	gem 'guard-rspec',          '~> 1.2.1'
	gem 'guard-spin',           '~> 0.3.0'
	gem 'guard-coffeescript',   '~> 1.2.0'
	gem 'rb-fsevent',           '~> 0.9.1'

	# Javascript Testing
	gem 'jasmine',              '~> 1.2.1'

	# Docs
	gem 'chef', '~> 11.4.0'
	gem 'yard', '~> 0.8.5.2'

	gem 'letter_opener'
end

group :test do
	gem 'rspec'
	gem 'rspec-rails',          '~> 2.11.0'
	gem 'capybara'
  gem 'capybara-webkit'
  gem 'selenium-webdriver'
	gem 'email_spec',           '~> 1.2.1'
	gem 'database_cleaner',     '~> 0.8.0'
	gem 'factory_girl_rails'
	gem 'cucumber-rails', :require => false
	gem "mocha", :require => false

	gem 'launchy'
	gem 'webmock'
	gem 'timecop'
end


gem "devise"