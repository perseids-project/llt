source 'https://rubygems.org'

# Specify your gem's dependencies in llt-tokenizer.gemspec
gemspec

gem 'coveralls', '0.8.21', require: false

gem 'llt-core', git: 'git://github.com/perseids-project/llt-core.git'
gem 'llt-constants', git: 'git://github.com/perseids-project/llt-constants.git'
gem 'llt-db_handler', git: 'git://github.com/perseids-project/llt-db_handler.git'
gem 'llt-helpers', git: 'git://github.com/perseids-project/llt-helpers.git'
gem 'llt-logger', git: 'git://github.com/perseids-project/llt-logger.git'
gem 'llt-review', git: 'git://github.com/perseids-project/llt-review.git'
gem 'llt-segmenter', git: 'git://github.com/perseids-project/llt-segmenter.git'
gem 'llt-xml_handler', git: 'git://github.com/perseids-project/llt-xml_handler.git'
gem 'llt-tokenizer', git: 'git://github.com/perseids-project/llt-tokenizer.git'

# Dependencies of db_handler
gem 'llt-core_extensions', git: 'git://github.com/perseids-project/llt-core_extensions.git'
gem 'llt-form_builder', git: 'git://github.com/perseids-project/llt-form_builder.git'

platform :ruby do
  gem 'pg'
end

platform :jruby do
  gem 'activesupport','3.2.22.2'
  gem 'activerecord-jdbc-adapter','1.3.19'
  gem 'activerecord-jdbcpostgresql-adapter','1.3.19'
  gem 'backports','3.6.8'
  gem 'celluloid', '0.16.0'
  gem 'haml','4.0.7'
  gem 'hitimes', '1.2.2'
  gem 'i18n','0.7.0'
  gem 'jruby-httpclient', '1.1.1'
  gem 'json','1.8.3'
  gem 'multi_json','1.11.2'
  gem 'nokogiri','1.6.7.2' # needed by llt-review
  gem 'rack','1.6.4'
  gem 'rack-test','0.6.3'
  gem 'sass','3.4.22'
  gem 'sinatra','1.4.7'
  gem 'term-ansicolor','1.3.2'
  gem 'thor','0.19.4'
  gem 'tilt','2.0.5'
  gem 'tins','1.6.0'
  gem 'tzinfo','0.3.46'
end

gem 'array_scanner', '0.0.2'
