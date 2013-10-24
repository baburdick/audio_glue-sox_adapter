source "https://rubygems.org"

gem 'audio_glue', '~> 0.1.0'
gem 'ruby-sox'

group :development do
  gem "bundler", "~> 1.0"
  gem "jeweler", "~> 1.8.7"
  gem 'yard'
end

group :development, :test do
  gem 'pry'

  # code metrics:
  gem "metric_fu"
end

group :test do
  gem 'rspec', '~> 2.14.1'
  gem 'simplecov'          , :require => false
  gem 'simplecov-rcov-text', :require => false
  gem 'chromaprint'
end
