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
  gem 'activerecord-jdbcpostgresql-adapter','1.3.19'
  gem 'nokogiri','1.6.7.2' # needed by llt-review
  gem 'jruby-httpclient', '1.1.1'
  gem 'celluloid', '0.16.0'
  gem 'sinatra','1.4.7'
end

gem 'array_scanner', '0.0.2'
gem 'warbler', '1.4.9'
