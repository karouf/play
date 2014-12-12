source 'https://rubygems.org'

gem 'jquery-rails'
gem "dnssd",            '~> 1.4'
gem 'font-awesome-rails', '~> 3.2.1.3'
gem 'mysql2',           '~> 0.3.11'
gem 'octokit',          '~> 1.25.0'
gem 'omniauth'
gem 'omniauth-github'
gem 'protected_attributes', '~> 1.0.1'
gem 'rails',            '4.0.0'
gem 'rake',             '~> 10.1.0'
gem 'ruby-mpd',         '~> 0.2.4'
gem 'sqlite3'
gem 'taglib-ruby',      '~> 0.6.0', :require => 'taglib'
gem 'turbolinks',       '~> 1.2.0'
gem 'unicorn',          '~> 4.6.3'
gem 'will_paginate',    '~> 3.0.4'

group :assets do
  # to solve https://github.com/sstephenson/sprockets/issues/540
  gem 'sprockets', '2.11.0' # 2.12.0 is broken
  gem 'sass-rails',     '~> 4.0.0'
  gem 'coffee-rails',   '~> 4.0.0'
  # lol what the fuck is compass doing
  gem "compass-rails",  :git => "https://github.com/Compass/compass-rails.git"
  gem 'uglifier',       '>= 1.3.0'
end

group :test do
  gem 'machinist'
  gem 'rack-test'
end
