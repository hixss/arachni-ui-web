source 'https://rubygems.org'

gem 'rails', '6.0.3.1'

# Web server.
gem 'puma'

# SQLite DB (Default)
gem 'sqlite3'

# Postgres DB (Optional)
gem 'pg'

platforms :jruby do
    # Bunch of bundled DB adaptors for use when on JRuby.
    gem 'activerecord-jdbc-adapter'
    gem 'jdbc-postgres'
    gem 'jdbc-sqlite3'
end

# JavaScript support framework.
gem 'jquery-rails', '4.4.0'

# UI/CSS framework.
gem 'bootstrap-sass', '3.4.1'

# Markdown to HTML conversion.
gem 'kramdown'

# HTML form helper.
gem 'simple_form', '~> 5.0.2'

# User management/authentication.
gem "devise", "~> 4.7.1"

# User authorization management.
gem 'cancan', '~> 1.6.10'

# User role management.
gem 'rolify', '~> 5.3.0'

# Pagination helper.
gem 'kaminari'

gem 'loofah'

# Required for MS Windows.
gem 'tzinfo-data'

group :development do
    # Model factory.
    gem 'factory_girl_rails'
end

group :development, :test do
    # Test framework.
    gem 'rspec-rails', '>= 4.0.1'
end

group :assets do
    # Sass CSS preprocessor.
    gem 'sass-rails', '~> 6.0.0'

    # CoffeeScript JavaScript preprocessor, stick with '1.8.0' for Windows
    # compat.
    gem 'coffee-script-source', '1.12.2'
    gem 'coffee-rails', '~> 5.0.0'

    # JavaScript compression.
    gem 'uglifier', '~> 4.2.0'

    # JavaScript interpreters.
    gem 'therubyrhino', platform: 'jruby'
    gem 'libv8',    '~> 3.11.8', platform: 'ruby'

    # JavaScript interpreter wrapper.
    gem 'therubyracer', platform: 'ruby'
end

group :test do
    # Browser simulator.
    gem 'capybara',         '>= 3.32.2'

    # BDD for Rails.
    gem 'cucumber-rails',   '>= 2.0.0', require: false

    # Does what its name suggests.
    gem 'database_cleaner', '>= 1.8.5'

    # Saves and launches the last failing webapp page.
    gem 'launchy',          '>= 2.5.0'

    # Model factory.
    gem 'factory_girl'

    # Sample values for model attributes.
    gem 'faker'
end

gem 'arachni',:github => 'hixss/arachni',:branch => 'experimental'
