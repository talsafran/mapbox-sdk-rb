source "https://rubygems.org"
gemspec

if Gem::Version.new(RUBY_VERSION.dup) < Gem::Version.new('1.9.3')
  gem 'i18n', '< 0.7'
  gem 'rest-client', '~> 2.0.1'
  gem "activesupport", ">= 4.1.11"
  gem 'rake', '10.1.0'
end

group :development, :test do
  gem "coveralls", :require => false
end