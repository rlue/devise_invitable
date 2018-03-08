source 'https://rubygems.org'

gemspec

group :test do
  platforms :jruby do
    gem 'activerecord-jdbcsqlite3-adapter', '>= 5.0.pre1'
  end

  platforms :ruby do
    gem "sqlite3", "~> 1.3.4"
  end

  gem 'devise', '~> 4.0', github: 'rlue/devise', branch: 'bugfix/find-or-initialize-with-errors'
  gem 'test_after_commit' # needed for devise >= 4.1 and rails < 5
  gem 'activerecord', '~> 5.1.0'
  gem 'actionmailer', '~> 5.1.0'
  gem "mongoid"
  # gem "mongoid", :github => "mongoid/mongoid", :branch => "master"
  gem "capybara"
  #gem "launchy", "~> 2.4.3"
  gem 'mocha'
  gem 'factory_girl_rails'
  gem 'nokogiri'
  gem 'rspec-rails'
end
