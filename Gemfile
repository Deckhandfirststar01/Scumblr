source 'https://rubygems.org'

gem 'rails', '7.1.0'


#Support for attr_accessible
#gem 'protected_attributes'

#For Search Providers
gem 'google-api-client'
gem 'twitter'
gem 'koala', '>= 1.10.1'

#Database gems
gem 'sqlite3'
gem 'pg'

#OneLogin Authenticatable
#gem 'devise_saml_authenticatable'
#gem 'ruby-saml'
gem 'omniauth-saml', '>= 2.0.0'

#Workflow
gem 'workflowable', '>= 1.0.1'

#JIRA Integration
#gem 'jira-ruby', require: "jira"
gem 'jiralicious'

#Authorization
gem 'cancan'

#Searching
gem 'ransack', '>= 1.3.0'

#market search
gem 'market_bot', '>= 0.12.1'
#Image processing/attachments
gem 'paperclip', '>= 4.2.1'
gem 'aws-sdk', '>= 1.52.0'


#Nice select fields
gem "select2-rails"

#Faster json parsing
gem 'oj'

#Bulk edits
gem 'activerecord-import', '>= 0.6.0'

#Used for task queueing
gem 'sidekiq'
gem 'sidekiq-status', '>= 0.5.4'

#Pagination
gem 'kaminari', '>= 0.16.2'

#Sidekiq UI
gem 'sinatra', '>= 2.0.0', require: false

#Templating language, not sure if used
gem 'slim'

#Performance gem that changes how links are handed
##gem 'turbolinks'
gem 'jquery-turbolinks', '>= 2.1.0'

#Allowing exporting/importing data into database
gem 'yaml_db'


#Authentication
gem 'devise', '>= 4.7.0'

#Comments
gem 'acts_as_commentable_with_threading', '>= 2.0.0'

#JSON API Calls
gem "active_model_serializers", ">= 0.8.2"


#gem 'active_scaffold'
gem "therubyracer"
gem "less-rails" , ">= 2.6.0" #Sprockets (what Rails 3.1 uses for its asset pipeline) supports LESS
gem 'simple_form', '>= 4.0.0'
gem 'foundation-rails'
#gem 'jquery-datatables-rails', git: 'git://github.com/rweng/jquery-datatables-rails.git'
gem 'unicorn'
gem 'unicorn-rails', '>= 2.2.0'
gem 'ip'

group :development do
  gem 'quiet_assets', '>= 1.1.0'
  gem "ruby-prof"
  gem "better_errors"
  gem 'meta_request', '>= 0.8.0'
  gem "binding_of_caller"
  gem "bullet", ">= 4.13.2"
  #gem 'rails-footnotes'
  #gem 'rails-footnotes', github: 'josevalim/rails-footnotes', branch: 'release-4.0'
  gem 'rails-footnotes', '>= 4.1.0', '< 5'
  gem 'railroady'
  gem 'ruby_gntp'
  gem 'pry'

end

#Testing
group :development, :test do
  gem 'rspec-rails', '>= 3.1.0'
  gem 'factory_girl_rails', '>= 4.5.0'

end

group :test do
  #gem 'cucumber-rails', require: false
  gem 'database_cleaner'
  #gem 'selenium-webdriver'
  gem "capybara", ">= 2.4.2"
  gem "guard-rspec", "~> 4.3.0"
  gem 'shoulda', '>= 3.6.0'
  gem 'activerecord-nulldb-adapter', '>= 0.3.2'
end


# Gems used only for assets and not required
# in production environments by default.
# Removed 4.0 group :assets do
##gem 'sass-rails'
##gem 'coffee-rails'

# See https://github.com/sstephenson/execjs#readme for more supported runtimes
#gem 'therubyracer', :platforms => :ruby
gem 'sass-rails',   '~> 4.0.0'
gem 'coffee-rails', '~> 4.2.2'


gem 'uglifier'
# Remove 4.0 end

gem 'jquery-rails', '>= 4.0.1'

gem 'rb-readline'

# To use ActiveModel has_secure_password
# gem 'bcrypt-ruby', '~> 3.0.0'

# To use Jbuilder templates for JSON
# gem 'jbuilder'

# Use unicorn as the app server
# gem 'unicorn'

# Deploy with Capistrano
# gem 'capistrano'

# To use debugger
# gem 'debugger'
