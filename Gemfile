source 'https://rubygems.org'
gemspec

gem 'jruby-openssl', :platforms => :jruby

group :test, :remote_test do
  # gateway-specific dependencies, keeping these gems out of the gemspec
  gem 'braintree', github: "braintree/braintree_ruby", branch: "raw_apple_pay_preview"
end
