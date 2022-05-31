source "https://rubygems.org"
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby "3.1.1"
gem "rails", "~> 7.0.3"
gem "sprockets-rails"
gem "sqlite3", "~> 1.4"
gem "puma", "~> 5.0"
gem "importmap-rails"
gem "turbo-rails"
gem "stimulus-rails"
gem "jbuilder"
# gem "redis", "~> 4.0"
# gem "kredis"
# gem "bcrypt", "~> 3.1.7"
gem "tzinfo-data", platforms: %i[ mingw mswin x64_mingw jruby ]
gem "bootsnap", require: false
gem 'bootstrap-sass', '~> 3.3', '>= 3.3.6'
gem 'sassc-rails', '>= 2.1.0'
gem 'jquery-rails'
gem 'font-awesome-sass', '~> 6.1.1'
gem 'bootstrap-sass-extras', '~> 0.0.2'
gem 'devise', '~> 4.8', '>= 4.8.1'
gem 'simple_form'
# gem "sassc-rails"
# gem "image_processing", "~> 1.2"
group :development, :test do
  # See https://guides.rubyonrails.org/debugging_rails_applications.html#debugging-with-the-debug-gem
  gem "debug", platforms: %i[ mri mingw x64_mingw ]
end
group :development do
  # Use console on exceptions pages [https://github.com/rails/web-console]
  gem "web-console"
   # gem "rack-mini-profiler"
   # gem "spring"
end
group :test do
  # Use system testing [https://guides.rubyonrails.org/testing.html#system-testing]
  gem "capybara"
  gem "selenium-webdriver"
  gem "webdrivers"
end

group :production do
  gem 'rails_12factor', '~> 0.0.3'
  gem 'pg', '~> 1.3', '>= 1.3.5'
end