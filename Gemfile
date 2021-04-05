source 'https://rubygems.org'
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

#security dependabot alerts
gem "activerecord", ">= 6.0.3.5"
gem "actionview", ">= 6.0.3.3"
gem "actionpack", ">= 6.0.3.5"
#

gem 'rails',      '>= 6.0.3.1'
gem 'puma',       '3.12.6'
gem 'sass-rails', '6.0.0'
gem 'webpacker',  '4.2.2'
gem 'turbolinks', '5.2.0'
gem 'jbuilder',   '2.9.1'
gem 'bootsnap',   '1.4.4', require: false
gem "nokogiri", "1.11.0"


group :development, :test do
  gem 'sqlite3', '1.4.1'
  gem 'byebug',  '11.0.1', platforms: [:mri, :mingw, :x64_mingw]
end

group :development do
  gem 'web-console',           '4.0.1'
  gem 'listen',                '3.5.1'
  gem 'spring',                '2.1.0'
  gem 'spring-watcher-listen', '2.0.1'
end

group :test do
  gem 'capybara',           '3.28.0'
  gem 'selenium-webdriver', '3.142.7'
  gem 'webdrivers',         '4.1.2'
end

group :production do
  gem 'pg', '1.1.4'
end

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]


