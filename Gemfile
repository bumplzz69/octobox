source 'https://rubygems.org'
ruby '2.6.3'

gem 'rails', '~> 6.1', '>= 6.1.7.5'
gem 'bootstrap', '>= 4.4.1'
gem 'attr_encrypted'
gem 'jquery-rails', '>= 4.3.4'
gem 'pagy'
gem 'local_time'
gem 'octicons_helper', '>= 9.0.0'
gem 'octokit'
gem 'omniauth-github'
gem 'puma'
gem 'sassc-rails', '>= 2.1.2'
gem 'turbolinks'
gem 'typhoeus'
gem 'faraday_middleware'
gem 'uglifier'
gem 'pg_search', '>= 2.2.0'
gem 'jbuilder', '>= 2.10.0'
gem 'rake', require: false
gem 'git'
gem 'rgb'
gem 'sidekiq'
gem 'sidekiq-unique-jobs'
gem 'sidekiq-scheduler', require: false
gem 'rack-canonical-host'
gem 'sidekiq-status'
gem 'gemoji', require: false
gem 'bootsnap', require: false
gem 'bugsnag'
gem 'jwt'
gem 'oj'
gem 'yard', require: false
gem 'commonmarker'

# Supported databases
gem 'mysql2', require: false
gem 'pg', '1.1.4', require: false

group :development, :test do
  gem 'byebug', platform: :mri
  gem 'dotenv-rails', '>= 2.7.6'
  gem 'guard'
  gem 'guard-minitest'
  gem 'rails-controller-testing', '>= 1.0.5'
  gem 'sql_queries_count'
  gem 'active_record_query_trace'
  gem 'rubocop', require: false
  gem 'rubocop-performance'
end

group :test do
  gem 'factory_bot', '>= 5.1.0'
  gem 'simplecov'
  gem 'webmock'
  gem 'mocha'
  gem 'minitest'
  gem 'selenium-webdriver'
  gem 'capybara'
  gem 'action-cable-testing', '>= 0.6.0'
  gem 'timecop'
end

group :development do
  gem 'web-console', '>= 4.0.0'
  gem 'listen'
  gem 'spring', '>= 2.1.0'
  gem 'spring-watcher-listen'
  gem 'brakeman'
  gem 'bullet', '>= 6.0.1'
  gem 'binding_of_caller'
  gem 'better_errors'
end

group :production do
  gem 'skylight', '4.1.0'
  gem 'lograge', '>= 0.11.2'
  gem 'puma_worker_killer'
  gem 'hirefire-resource'
end
