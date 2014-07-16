# 09/06/2014
source 'https://rubygems.org'
# Railstutorial.org indica a versao 1.9.3 para Windows
ruby '1.9.3'

# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
# 4.0.8 � a vers�o recomendada pelo railstutorial
gem 'rails', '4.0.8'
# Railstutorial/sample_app adota PostgreSQL para prod; ent�o resolvi adotar
# para test e desenv tamb�m, para teste este banco de dados.
gem 'pg', '0.15.1'
# Use sqlite3 as the database for Active Record
group :development, :test do
	# gem 'sqlite3', '1.3.8'
	gem 'rspec-rails', '2.13.1'
	gem 'guard-rspec', '2.5.0'
	gem 'spork-rails', '4.0.0'
	gem 'guard-spork', '1.5.0'
	gem 'childprocess', '0.3.6'
end

group :test do
	gem 'selenium-webdriver', '2.35.1'
	gem 'capybara', '2.1.0'
	gem 'rb-notifu', '0.0.4'
	gem 'wdm', '0.1.0'
end

# Use SCSS for stylesheets
gem 'sass-rails', '4.0.1'
# Use Uglifier as compressor for JavaScript assets
gem 'uglifier', '2.1.1'
# Use CoffeeScript for .js.coffee assets and views
gem 'coffee-rails', '4.0.1'
# See https://github.com/sstephenson/execjs#readme for more supported runtimes
# gem 'therubyracer',  platforms: :ruby

# Use jquery as the JavaScript library
gem 'jquery-rails', '3.0.4'
# Turbolinks makes following links in your web application faster. Read more: https://github.com/rails/turbolinks
gem 'turbolinks', '1.1.1'
# Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder
gem 'jbuilder', '1.0.2'
# bundle exec rake doc:rails generates the API under doc/api.
gem 'sdoc', '0.3.20', require: false,          group: :doc

# Use ActiveModel has_secure_password
# gem 'bcrypt', '~> 3.1.7'

# Use unicorn as the app server
# gem 'unicorn'

# Use Capistrano for deployment
# gem 'capistrano-rails', group: :development

# Use debugger
# gem 'debugger', group: [:development, :test]

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
# Da pau com 'rails generate rspec:install' se for habilitado.
#gem 'tzinfo-data', platforms: [:mingw, :mswin]

group :production do
	#gem 'pg', '0.15.1'
	gem 'rails_12factor', '0.0.2'
end
