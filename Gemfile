#source "http://rubygems.org"
source "http://ruby.taobao.org"

gem 'rack'
gem 'rake'
gem 'sinatra'

#--------------------------------
# Json
#--------------------------------
# oj: A fast JSON parser and Object marshaller as a Ruby gem.
gem 'oj'

#--------------------------------
#DB ORM
#--------------------------------
#
#Mysql:
#       gem 'mysql2'
#       gem 'activerecord'
#Sqlite:
#       gem 'dm-sqlite-adapter'
#       gem 'sqlite3'
#       gem 'data_mapper'
#mongodb
gem 'bson'
gem 'bson_ext'
gem 'mongoid'

#--------------------------------
# Cache
#   Dalli: Dalli is a high performance pure Ruby client for accessing memcached servers.
#
#   Kgio: kgio provides non-blocking I/O methods for Ruby without raising exceptions on EAGAIN and
#         EINPROGRESS. It is intended for use with the Unicorn and Rainbows! Rack servers, but may be used
#         by other applications (that run on Unix-like platforms).
#--------------------------------
#      gem 'dalli', :require => 'active_support/cache/dalli_store'
#      gem 'kgio'
#      gem "second_level_cache", :git => "git://github.com/csdn-dev/second_level_cache.git"

#--------------------------------
# Deployment
#   Pry: pry is a powerful alternative to the standard IRB shell for Ruby.
#--------------------------------
gem 'pry'

group :production do
  gem 'rainbows'
end

group :development do
  gem 'thin'
  gem 'sinatra-contrib'
end

group :test do
  #gem 'minitest', "~>2.6.0", :require => "minitest/autorun"
  #gem 'rack-test', :require => "rack/test"
  #gem 'factory_girl'
  #gem 'database_cleaner'
end
