source 'https://rubygems.org'

# Specify your gem's dependencies in llt-tokenizer.gemspec
gemspec

gem 'coveralls', require: false

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
  gem 'activerecord-jdbcpostgresql-adapter'
  gem 'nokogiri' # needed by llt-review
  gem 'jruby-httpclient'
  gem 'celluloid'
end

gem 'array_scanner'
