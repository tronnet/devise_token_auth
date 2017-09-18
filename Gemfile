source "https://rubygems.org"

# Declare your gem's dependencies in devise_token_auth.gemspec.
# Bundler will treat runtime dependencies like base dependencies, and
# development dependencies will be added by default to the :development group.
gemspec

# Declare any dependencies that are still in development here instead of in
# your gemspec. These might include edge Rails or gems from your path or
# Git. Remember to move these dependencies to your gemspec before releasing
# your gem to rubygems.org.

# To use debugger
# gem 'debugger'

gem 'mongoid', '6.0.2'

group :development, :test do
  gem 'thor'
  gem "figaro",                 :git => 'https://github.com/laserlemon/figaro'
  gem 'omniauth-github',        :git => 'https://github.com/intridea/omniauth-github'
  gem 'omniauth-facebook',      :git => 'https://github.com/mkdynamic/omniauth-facebook'
  gem 'omniauth-google-oauth2', :git => 'https://github.com/zquestz/omniauth-google-oauth2'
  gem 'rack-cors',              :require => 'rack/cors'
  gem 'attr_encrypted'

  # testing
  #gem 'spring'
  gem "pry"
  gem "pry-remote"
  gem 'minitest'
  gem 'minitest-rails'
  gem 'minitest-focus'
  gem 'minitest-reporters'
  gem 'guard'
  gem 'guard-minitest'
  gem 'faker'
  gem 'fuzz_ball'
  gem 'mocha'
end

# code coverage, metrics
group :test do
  gem "codeclimate-test-reporter", require: nil
end

group :development do
  gem "github_changelog_generator"
end
