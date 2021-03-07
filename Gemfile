source 'https://rubygems.org'
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby '2.7.0'

gem 'rails',                    '5.2.4'
gem 'puma',                     '4.3.6'
gem 'sass-rails',               '5.0.5'
gem 'uglifier',                 '3.0.0'
gem 'coffee-rails',             '5.0.0'
gem 'jquery-rails',             '4.1.1'
gem 'turbolinks',               '5.0.0'
gem 'jbuilder',                 '2.9.0'
gem 'bootsnap'
gem 'bcrypt-ruby',              '3.1.2'
gem 'faker',                    '1.6.3'
gem 'will_paginate',            '3.1.7'


group :development, :test do
  gem 'sqlite3', '1.3.11'
  gem 'byebug',  '9.0.0', platform: :mri
end

group :development do
  gem 'web-console',           '3.1.1'
  gem 'listen',                '3.0.8'
  gem 'spring',                '1.7.2'
  gem 'spring-watcher-listen', '2.0.0'
  gem "better_errors"
  gem 'hirb'
end

group :test do
  gem 'rails-controller-testing', '0.1.1'
  gem 'minitest-reporters',       '1.1.9'
  gem 'guard',                    '2.13.0'
  gem 'guard-minitest',           '2.4.4'
end

group :production do
  gem 'pg', '0.18.4'
end

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]
