source 'https://rubygems.org'

gem 'rb-readline'
gem 'csv', '1.0.2'  # https://github.com/ruby/csv/issues/23

gem 'rails', '5.2.4.6'
gem "i18n-js"
gem "i18n",  '>= 0.7.0'

gem 'pg'
gem 'marginalia'

gem 'deep_cloneable', '~> 2.4.0'

gem 'sass-rails', '~> 5.0.1'

gem 'webpacker'

gem 'telephone_number'
gem 'rdkafka'
gem  'holidays'
gem 'graphql'
source "https://gems.graphql.pro/" do
  gem "graphql-pro"
end

# Use Uglifier as compressor for JavaScript assets
gem 'uglifier', '>= 3.0.0'
gem 'secure_headers'

# See https://github.com/rails/execjs for more supported runtimes
gem 'therubyracer', platforms: :ruby

#Email parser for use with InboundMailProcessor
gem 'extended_email_reply_parser'

group :development do
  gem 'puma'
  gem 'better_errors'
  gem "locale_base"
  gem 'meta_request'
  gem 'smartling'
  gem 'web-console'
  gem 'rack-mini-profiler', require: false
  gem 'ed25519'
  gem 'bcrypt_pbkdf'
  gem 'dropkiq'
end

group :development, :test  do
  gem 'awesome_print'
  gem 'i18n-tasks'
  gem 'licensed'
  gem 'pry'
  gem 'pry-byebug'
  gem 'pry-rails'
  gem 'pry-rescue'
  gem 'pry-stack_explorer'
  gem 'rake'
  gem 'dotenv-rails'
end

group :test do
  gem 'rails-controller-testing'
  gem 'minitest'
  gem 'webmock'
  gem 'simplecov', '>=0.13.0', require: false
  gem 'mocha', '>= 1.2'
  gem 'minitest-focus'
  gem 'minitest-stub-const'
  gem 'minitest-hooks'
end

gem 'rails_semantic_logger', group: %i[production demo stage sandbox]

gem 'rollbar'
gem 'scout_apm'

gem 'unicorn'
gem 'pghero'
gem 'pg_query'

# Standard Gems
gem 'aasm'
gem 'fuzzy_match', '~> 2.0.4', :require => 'fuzzy_match'
#Luhn - a checksum formula used to validate a variety of identification numbers, such as credit card numbers, IMEI numbers
gem 'luhn-ruby', :require => 'luhn'

# Declarative auth hasn't has a release in 3 years and we wanted to make one small modification (don't put all person info
# in the log) so we forked.  It seems that they haven't accepted pull requests in years, so we're going off of our fork.
# https://github.com/mobi/mobi/pull/3837
gem 'declarative_authorization', git: "https://github.com/mobi/declarative_authorization", branch: "rails_5.2"

# Required for the declarative_auth gem due to the stuff we do in the Role model
# Locking to 3.6.6 because tests don't pass in declarative_authorization with newer versions
#  https://github.com/seattlerb/ruby_parser/issues/219
gem 'ruby_parser', '3.6.6'

gem 'authlogic'
gem 'paperclip'
gem 'makara'
gem 'haml-rails'

gem 'has_config'
gem 'select2-rails', '~> 4.0.3'
gem 'chroma'
gem 'business_time'
gem "acts_as_list", "~> 0.9"

gem "simple_form", "~> 5.0.3"

gem "globalize"

gem 'ruby-saml'
gem 'multipart-post'
gem 'terrapin' # formerly 'cocaine'
gem 'globalize-accessors'
gem 'responders'

gem 'attr_encrypted'
gem 'cryptosystem'
gem "twilio-ruby"

# chronic is still in (sort of) active development but hasn't had a release since 2013
gem 'chronic', git: 'https://github.com/mojombo/chronic', branch: 'master'

gem "scopelist", "~> 0.0.2"
gem "ransack"
gem 'ar_outer_joins'
gem 'will_paginate'
gem 'dalli' # Used for memcache caching

gem 'simple_xlsx_writer'
#added zip-zip to make rubyzip compatible with simple_xlsx_writer, which relies on older rubyzip api
gem 'zip-zip'

gem 'jbuilder'
gem 'oj'
gem 'impressionist'
gem 'activerecord-reputation-system', git: 'https://github.com/NARKOZ/activerecord-reputation-system', branch: 'rails4'
gem 'rails-i18n'
gem 'zero_fill'
gem 'retries'
gem 'bcrypt'
gem 'ApiWrapperFor8x8', git: 'https://github.com/mobi/api-wrapper-for-8x8', branch: 'edge'
gem 'carmen'
gem 'wisper', '2.0.0'

# Gems involving the display for data
gem 'liquid', '~> 4.0.0'
gem 'render_anywhere', :require => false

### If you upgrade money, you must ensure functionality of monetize and google currency
gem "money", ">= 6.6.1"
gem "monetize"
gem "braintree"
gem "activemerchant"

gem 'smartystreets_ruby_sdk'

gem 'dynamic_form' # Re-adds error_messages_for which was removed in Rails 3.0

# Used for obfuscation
gem "faker"
gem 'chewy'

gem 'sidekiq-ent', source: 'https://enterprise.contribsys.com'

gem 'resque', require: 'resque/server'
gem 'resque-scheduler'
gem 'resque-status'

# Gem manually checked out and loaded directed either due to
# bugs, custom modifications, or dependancy issues
gem "classifier", git: "https://github.com/mobi/classifier"

gem 'mobi-vestal_versions', git: 'https://github.com/mobi/vestal_versions', branch: 'allow_rails_5.2', require: 'vestal_versions'

gem 'active_shipping', git: 'https://github.com/mobi/active_shipping', branch: '2.1.1.rails52'
gem 'fedex'

# Client API gems
gem 'draper'
gem 'rack-attack'
gem 'jsonapi-rails', '0.4.0'
gem 'jsonapi-serializable', '0.3.1'
gem 'jsonapi-renderer', '0.2.2'
gem 'jwt'

gem 'ruby-msg', require: 'mapi/msg'

# Bootsnap (from Shopify) should speed up boot times
gem 'bootsnap', require: false

gem 'graphiql-rails'
gem 'json_to_graphql'
gem 'oauth', '>= 0.5.5'
gem 'graphql-batch'

gem 'erubi', '1.10.0'

gem 'countries'
gem 'minitest-reporters'
