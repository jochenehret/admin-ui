source 'http://rubygems.org'

ruby '2.3.1', :engine => 'jruby', :engine_version => '9.1.5.0'

gem 'faye-websocket', '0.10.7'
gem 'membrane', '1.1.0'
gem 'nats', '0.8.0'
gem 'net-sftp', '2.1.2'
gem 'parse-cron', '0.1.4'
gem 'rack-ssl', '1.4.1'
gem 'ruby_protobuf', '0.4.11'
gem 'sequel', '4.44.0'
gem 'sequel_pg', '1.6.17'
gem 'sinatra', '1.4.8'
gem 'sqlite3', '1.3.13'
gem 'yajl-ruby', '1.3.0'

group :mysql do
  gem 'mysql2', '0.3.20'
end

group :development do
  gem 'rake', '12.0.0' # Temporarily required since rubocop requires rainbow which requires rake: https://github.com/sickill/rainbow/issues/44
  gem 'rubocop', '0.47.1'
end

group :test do
  gem 'rspec', '3.5.0'
  gem 'selenium-webdriver', '3.3.0'
end
