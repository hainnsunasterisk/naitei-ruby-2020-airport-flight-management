source "https://rubygems.org"
git_source(:github){|repo| "https://github.com/#{repo}.git"}

gem "bcrypt", "3.1.13"
gem "bootsnap", ">= 1.4.2", require: false
gem "bootstrap4-kaminari-views", "~> 1.0.1"
gem "cancancan"
gem "config"
gem "devise", "~> 4.1"
gem "grape"
gem "grape-entity"
gem "grape_on_rails_routes"
gem "i18n-js"
gem "jbuilder", "~> 2.7"
gem "kaminari"
gem "mysql2", ">= 0.4.4"
gem "puma", "~> 4.1"
gem "rails", "~> 6.0.3", ">= 6.0.3.2"
gem "rails-i18n"
gem "sass-rails", ">= 6"
gem "turbolinks", "~> 5"
gem "webpacker", "~> 5.0"

group :development do
  gem "listen", "~> 3.2"
  gem "rails_best_practices"
  gem "reek"
  gem "rubocop", require: false
  gem "rubocop-rails", "~> 2.3.2", require: false
  gem "spring"
  gem "spring-watcher-listen", "~> 2.0.0"
end

gem "tzinfo-data", platforms: %i(mingw mswin x64_mingw jruby)

group :development, :test do
  gem "database_cleaner-active_record"
  gem "factory_bot_rails"
  gem "pry-rails"
  gem "rspec-rails"
  gem "shoulda-matchers"
  gem "simplecov", require: false
end

group :test do
  gem "faker"
end

group :test do
  gem "capybara"
end
