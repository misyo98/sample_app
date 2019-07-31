source 'https://rubygems.org'
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby '2.6.0'

# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'rails'
gem 'bcrypt'
gem 'faker'
gem 'carrierwave'
gem 'mini_magick'
gem 'fog',                     '1.36.0'
gem 'will_paginate'
gem 'bootstrap-will_paginate'
gem 'bootsnap', require: false
gem 'bootstrap-sass'
gem 'sass-rails'
gem 'uglifier'
gem 'coffee-rails'
gem 'jquery-rails'
gem 'turbolinks'
gem 'jbuilder'
gem 'sdoc', group: :doc

group :development, :test do
  gem 'sqlite3'
  gem 'listen'
  gem 'byebug'
  gem 'web-console'
  gem 'spring'
end

group :test do
  gem 'minitest-reporters'
  gem 'mini_backtrace'
  gem 'guard-minitest'
end

group :production do
gem 'pg', '>= 0.18', '< 2.0'
  gem 'rails_12factor'
  gem 'puma'
end

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]
