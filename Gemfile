source :rubygems
ruby '1.9.3'

gem 'rails'
# Load the Coursewareable engine
gem 'coursewareable', :git => 'https://0de5ffe2dda4bfcb19b1615a99295eafe7375bdc:x-oauth-basic@github.com/stas/coursewareable.git'
gem 'cancan'
gem 'haml-rails'
gem 'jquery-rails'
gem 'delayed_job_active_record'
gem 'gettext_i18n_rails'
gem 'roadie'
gem 'gravatar_image_tag'
gem 'daemons'
gem 'kaminari'
gem 'public_activity'
gem 'sorcery', '0.8.1'

# Speedup a bit things
gem 'multi_json'
gem 'oj'

group :production do
  gem 'pg'
  gem 'puma'
  gem 'aws-sdk'
  gem 'party_foul'
end

group :development do
  gem 'sqlite3'
  gem 'pry'
  gem 'quiet_assets'
  # gem 'rack-bug', :github => 'brynary/rack-bug', :branch => 'rails3'
  gem 'letter_opener'
  # gem 'rails-erd'
  gem 'yard', :require => false
  gem 'gettext', :require => false
  gem 'ruby_parser', :require => false
  gem 'cane'
  gem 'seedbank'
  gem 'mina', :require => false
  gem 'pry-rails'
end

group :assets do
  gem 'uglifier'
  gem 'therubyracer'
  gem 'sass-rails'
  gem 'compass-rails'
  gem 'zurb-foundation'
  gem 'turbo-sprockets-rails3'
end

group :development, :test do
  gem 'ffaker'
  gem 'fabrication'
  gem 'guard-rspec'
  gem 'rb-inotify'
  gem 'rspec-rails', '2.12.0'
  gem 'shoulda-matchers'
  gem 'database_cleaner'
  gem 'capybara'
  gem 'email_spec'
  gem 'simplecov', :require => false
  gem 'tddium', :require => false
end
