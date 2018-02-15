source 'https://rubygems.org'

gem 'rails', '~> 5.1'
gem 'mysql2'
gem 'puma'
gem 'sass-rails'
gem 'uglifier'
gem 'coffee-rails'
gem 'jquery-rails'
gem 'turbolinks'
gem 'bcrypt'
gem 'haml'
gem 'nifty-utils'
gem 'nilify_blanks'
gem 'authie'
gem 'kaminari'
gem 'hashie'
gem 'dynamic_form'
gem 'omniauth'
gem 'foreman'
gem 'nissh'
gem 'net-sftp', :require => 'net/sftp'
gem 'moonrope'
gem 'autoprefixer-rails'

require_relative './lib/bound/config'
if Bound.yaml_config['auth'] && strategy = Bound.yaml_config['auth']['strategy']
  gem "omniauth-#{strategy}"
end

group :development, :test do
  gem 'byebug'
  gem 'annotate'
end
