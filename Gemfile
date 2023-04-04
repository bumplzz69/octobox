source 'https://rubygems.org'
ruby '2.6.3'

gem 'rails', '~> 6.1', '>= 6.1.7.3'
gem 'bootstrap'
gem 'attr_encrypted'
gem 'jquery-rails', '>= 4.4.0'
gem 'pagy'
gem 'local_time'
gem 'octicons_helper'
gem 'octokit'
gem 'omniauth-github', '>= 2.0.0'
gem 'puma', '>= 4.3.12'
gem 'sassc-rails'
gem 'turbolinks'
gem 'typhoeus'
gem 'faraday_middleware'
gem 'uglifier'
gem 'pg_search'
gem 'jbuilder'
gem 'rake', '>= 12.3.3', require: false
gem 'git', '>= 1.13.0'
gem 'rgb'
gem 'sidekiq', '>= 6.2.1'
gem 'sidekiq-unique-jobs'
gem 'sidekiq-scheduler', require: false
gem 'rack-canonical-host'
gem 'sidekiq-status'
gem 'gemoji', require: false
gem 'bootsnap', require: false
gem 'bugsnag'
gem 'jwt'
gem 'oj'
gem 'yard', '>= 0.9.20', require: false
gem 'commonmarker', '>= 0.23.7'

# Supported databases
gem 'mysql2', require: false
gem 'pg', '1.1.4', require: false

group :development, :test do
  gem 'byebug', platform: :mri
  gem 'dotenv-rails', '>= 2.7.6'
  gem 'guard'
  gem 'guard-minitest'
  gem 'rails-controller-testing'
  gem 'sql_queries_count'
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
  gem 'action-cable-testing'
  gem 'timecop'
end

group :development do
  gem 'web-console'
  gem 'listen'
  gem 'spring'
  gem 'spring-watcher-listen'
  gem 'brakeman', '>= 4.7.1'
  gem 'bullet'
  gem 'binding_of_caller'
  gem 'better_errors', '>= 2.8.0'
end

group :production do
  gem 'skylight', '4.0.2'
  gem 'lograge'
  gem 'puma_worker_killer', '>= 0.1.1'
  gem 'hirefire-resource'
end
