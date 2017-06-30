source 'https://rubygems.org'

git_source(:github) do |repo_name|
  repo_name = "#{repo_name}/#{repo_name}" unless repo_name.include?("/")
  "https://github.com/#{repo_name}.git"
end

gem 'rails',            '~> 5.0.2'
gem 'pg',               '~> 0.21.0'
gem 'puma',             '~> 3.0'
gem 'sass-rails',       '~> 5.0'
gem 'uglifier',         '>= 1.3.0'
gem 'coffee-rails',     '~> 4.2'
gem 'dotenv-rails',     '~> 2.2', '>= 2.2.1'

gem 'jquery-rails'
gem 'turbolinks',       '~> 5'
gem 'jbuilder',         '~> 2.5'
gem 'haml', '~> 5.0',   '>= 5.0.1'
gem 'materialize-sass', '~> 0.98.2'
gem 'material_icons',   '~> 2.2', '>= 2.2.1'
gem 'pubnub',           '~> 4.0.22'

group :development, :test do
  gem 'byebug', platform: :mri
end

group :development do
  gem 'web-console',           '>= 3.3.0'
  gem 'listen',                '~> 3.0.5'
  gem 'spring'
  gem 'spring-watcher-listen', '~> 2.0.0'
end

gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]
