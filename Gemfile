source 'https://rubygems.org'

gem 'rails', "3.2.22"

# Bundle edge Rails instead:
# gem 'rails', :git => 'git://github.com/rails/rails.git'

gem 'rails_12factor', group: :production
gem 'pg'
#gem 'lentil', :git => "git://github.com/bnorberg/lentil.git"
gem 'lentil', :git => 'git://github.com/NCSU-Libraries/lentil.git'
gem 'therubyracer'
gem 'whenever', require: false

# Gems used only for assets and not required
# in production environments by default.
group :assets do
  gem 'sass-rails',   '~> 3.2.3'
  gem 'coffee-rails', '~> 3.2.1'

  # See https://github.com/sstephenson/execjs#readme for more supported runtimes
  # gem 'therubyracer', :platforms => :ruby

  gem 'uglifier', '>= 1.0.3'
end

gem 'jquery-rails', '= 2.3.0'

# To use ActiveModel has_secure_password
# gem 'bcrypt-ruby', '~> 3.0.0'

# To use Jbuilder templates for JSON
# gem 'jbuilder'

# Use unicorn as the app server
  gem 'unicorn'

# Deploy with Capistrano
  group :production do
    gem 'capistrano',         require: false
    gem 'capistrano-rvm',     require: false
    gem 'capistrano-rails',   require: false
    gem 'capistrano-bundler', require: false
end
# To use debugger
# gem 'debugger'
