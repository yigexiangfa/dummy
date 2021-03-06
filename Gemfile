source 'https://rubygems.org'
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

gem 'rails', '6.1.4'
gem 'puma'
gem 'sidekiq'

# Store
gem 'pg'
gem 'redis'
gem 'active_record_distinct_on'

# Assets
gem 'viter', github: 'qinmingyuan/viter'

# Views
gem 'jbuilder'

# Utils
gem 'kaminari'
gem 'acts_as_list'
gem 'bcrypt'
gem 'image_processing'
gem 'rqrcode'

# apm
gem 'scout_apm'
gem 'server_timing'

# Third Part
gem 'omniauth-wechat-oauth2', github: 'qinmingyuan/omniauth-wechat-oauth2'
gem 'upyun_rails', github: 'qinmingyuan/upyun_rails'

# Rails Helpers
gem 'default_form', github: 'qinmingyuan/default_form'
gem 'default_where', github: 'qinmingyuan/default_where'

# Engines
gem 'rails_ui', github: 'work-design/rails_ui'
gem 'rails_com', github: 'work-design/rails_com'

# Should after rails_com
gem 'turbo-rails'

gem 'bootsnap', require: false
gem 'amazing_print'
gem 'pry-rails'

group :development, :test do
  gem 'byebug', platforms: [:mri, :mingw, :x64_mingw]
  gem 'pry-stack_explorer'
  gem 'factory_bot_rails'
end

group :development do
  gem 'listen'
  gem 'spring'
  gem 'spring-watcher-listen'
  gem 'web-console'
end

group :test do
  gem 'capybara'
  gem 'selenium-webdriver'
  gem 'webdrivers'
end
