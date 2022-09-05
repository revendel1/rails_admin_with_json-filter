appraise "rails-5.0" do
  gem 'rails', '~> 5.0.0'
  gem 'sassc-rails', '~> 2.1'
  gem 'devise', '~> 4.0'

  group :test do
    gem 'cancancan', '~> 2.0'
    gem 'paperclip', ['>= 3.4', '!= 4.3.0']
    gem 'mimemagic', '< 0.3.10'
    gem 'shrine', '~> 2.13.0'
    gem 'shrine-memory'
  end

  group :active_record do
    gem 'paper_trail', '>= 5.0'

    platforms :ruby, :mswin, :mingw, :x64_mingw do
      gem 'sqlite3', '~> 1.3.0'
    end

    platforms :jruby do
      gem 'activerecord-jdbcmysql-adapter', '~> 50.0'
      gem 'activerecord-jdbcpostgresql-adapter', '~> 50.0'
      gem 'activerecord-jdbcsqlite3-adapter', '~> 50.0'
    end
  end

  group :mongoid do
    gem 'mongoid', '~> 6.1'
    gem 'kaminari-mongoid'
    gem 'mongoid-paperclip', '>= 0.0.8', require: 'mongoid_paperclip'
    gem 'carrierwave-mongoid', '>= 0.6.3', require: 'carrierwave/mongoid'
    gem 'cancancan-mongoid'
    gem 'shrine-mongoid', '~> 0.2.4'
  end
end

appraise "rails-5.1" do
  gem 'rails', '~> 5.1.0'
  gem 'sassc-rails', '~> 2.1'
  gem 'devise', '~> 4.0'

  group :test do
    gem 'cancancan', '~> 2.0'
    gem 'paperclip', ['>= 3.4', '!= 4.3.0']
    gem 'shrine', '~> 3.0'
  end

  group :active_record do
    gem 'pg', '~> 0.14', platforms: :ruby
    gem 'paper_trail', '>= 5.0'

    platforms :jruby do
      gem 'activerecord-jdbcmysql-adapter', '~> 51.0'
      gem 'activerecord-jdbcpostgresql-adapter', '~> 51.0'
      gem 'activerecord-jdbcsqlite3-adapter', '~> 51.0'
    end
  end

  group :mongoid do
    gem 'mongoid', '~> 7.0'
    gem 'kaminari-mongoid'
    gem 'mongoid-paperclip', '>= 0.0.8', require: 'mongoid_paperclip'
    gem 'carrierwave-mongoid', '>= 0.6.3', require: 'carrierwave/mongoid'
    gem 'cancancan-mongoid'
    gem 'shrine-mongoid', '~> 1.0'
  end
end

appraise "rails-5.2" do
  gem 'rails', '~> 5.2.0'
  gem 'sassc-rails', '~> 2.1'
  gem 'devise', '~> 4.4'

  group :test do
    gem 'cancancan', '~> 2.0'
    gem 'paperclip', ['>= 3.4', '!= 4.3.0']
    gem 'shrine', '~> 3.0'
  end

  group :active_record do
    gem 'pg', '>= 1.0.0', platforms: :ruby
    gem 'paper_trail', '>= 5.0'

    platforms :jruby do
      gem 'activerecord-jdbcmysql-adapter', '~> 52.0'
      gem 'activerecord-jdbcpostgresql-adapter', '~> 52.0'
      gem 'activerecord-jdbcsqlite3-adapter', '~> 52.0'
    end
  end

  group :mongoid do
    gem 'mongoid', '~> 7.0'
    gem 'kaminari-mongoid'
    gem 'mongoid-paperclip', '>= 0.0.8', require: 'mongoid_paperclip'
    gem 'carrierwave-mongoid', '>= 0.6.3', require: 'carrierwave/mongoid'
    gem 'cancancan-mongoid'
    gem 'shrine-mongoid', '~> 1.0'
  end
end

appraise "rails-6.0" do
  gem 'rails', '~> 6.0.0'
  gem 'haml'
  gem 'sassc-rails', '~> 2.1'
  gem 'devise', '~> 4.7'

  group :test do
    gem 'cancancan', '~> 3.0'
    gem 'kt-paperclip'
    gem 'rspec-rails', '>= 4.0.0.beta2'
    gem 'shrine', '~> 3.0'
  end

  group :active_record do
    gem 'pg', '>= 1.0.0', platforms: :ruby
    gem 'paper_trail', '>= 5.0'

    platforms :jruby do
      gem 'activerecord-jdbcmysql-adapter', '~> 60.0'
      gem 'activerecord-jdbcpostgresql-adapter', '~> 60.0'
      gem 'activerecord-jdbcsqlite3-adapter', '~> 60.0'
    end
  end

  group :mongoid do
    gem 'mongoid', '~> 7.0'
    gem 'kaminari-mongoid'
    gem 'mongoid-paperclip', '>= 0.0.8', require: 'mongoid_paperclip'
    gem 'carrierwave-mongoid', '>= 0.6.3', require: 'carrierwave/mongoid'
    gem 'cancancan-mongoid'
    gem 'shrine-mongoid', '~> 1.0'
  end
end

appraise "rails-6.1" do
  gem 'rails', '~> 6.1.0'
  gem 'haml'
  gem 'sassc-rails', '~> 2.1'
  gem 'devise', '~> 4.7'
  gem 'webrick', '~> 1.7'

  group :test do
    gem 'cancancan', '~> 3.2'
    gem 'kt-paperclip'
    gem 'rspec-rails', '>= 4.0.0.beta2'
    gem 'shrine', '~> 3.0'
  end

  group :active_record do
    gem 'pg', '>= 1.0.0', platforms: :ruby
    gem 'paper_trail', '>= 5.0'
  end
end
