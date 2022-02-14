source 'https://rubygems.org'
ruby '2.6.3'

gem 'rails', '~> 5.2', '>= 5.2.6.2'
gem 'bootstrap', '>= 4.3.1'
gem 'attr_encrypted'
gem 'jquery-rails', '>= 4.3.3'
gem 'pagy'
gem 'local_time'
gem 'octicons_helper', '>= 8.5.0'
gem 'octokit'
gem 'omniauth-github'
gem 'puma', '>= 4.3.11'
gem 'sassc-rails', '>= 2.1.1'
gem 'turbolinks'
gem 'typhoeus'
gem 'faraday_middleware'
gem 'uglifier'
gem 'pg_search'
gem 'jbuilder'
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
  gem 'dotenv-rails', '>= 2.7.2'
  gem 'guard'
  gem 'guard-minitest'
  gem 'rails-controller-testing', '>= 1.0.4'
  gem 'sql_queries_count', '>= 0.0.1'
  gem 'active_record_query_trace'
  gem 'rubocop', require: false
  gem 'rubocop-performance'
end

group :test do
  gem 'factory_bot'
  gem 'simplecov'
  gem 'webmock'
  gem 'mocha'
  gem 'minitest'
  gem 'selenium-webdriver'
  gem 'capybara'
  gem 'action-cable-testing', '>= 0.5.0'
  gem 'timecop'
end

group :development do
  gem 'web-console', '>= 3.7.0'
  gem 'listen'
  gem 'spring'
  gem 'spring-watcher-listen'
  gem 'brakeman'
  gem 'bullet'
  gem 'binding_of_caller'
  gem 'better_errors'
end

group :production do
  gem 'skylight', '4.0.2'
  gem 'lograge', '>= 0.11.1'
  gem 'puma_worker_killer', '>= 0.1.1'
  gem 'hirefire-resource'
end
