source 'https://rubygems.org'

# Padrino supports Ruby version 1.9 and later
ruby '2.4.1'

# Distribute your app as a gem
# gemspec

# Server requirements
# gem 'thin' # or mongrel
# gem 'trinidad', :platform => 'jruby'

# Optional JSON codec (faster performance)
# gem 'oj'

# Project requirements
gem 'rake'

# Component requirements
gem 'activesupport', '>= 3.1'
gem 'bcrypt'
gem 'haml'
gem 'sass'
gem 'sequel'
gem 'sqlite3'

# Test requirements
gem 'rack-test', require: 'rack/test', group: 'test'
gem 'rspec', group: 'test'

# Padrino Stable Gem
gem 'padrino', '0.14.1.1'

# Or Padrino Edge
# gem 'padrino', :github => 'padrino/padrino-framework'

# Or Individual Gems
# %w(core support gen helpers cache mailer admin).each do |g|
#   gem 'padrino-' + g, '0.14.1.1'
# end

gem 'rubocop', group: :development

group :development, :test do
  gem 'pry-byebug'
  gem 'pry-stack_explorer'
end
