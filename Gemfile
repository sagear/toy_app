source 'https://rubygems.org'
git_source(:github) { |repo| "https://github.com/#{repo}.git" }
=begin
Using rake 12.3.2
Using concurrent-ruby 1.1.5
Using i18n 1.6.0
Using minitest 5.11.3
Using thread_safe 0.3.6
Using tzinfo 1.2.5
Using activesupport 5.2.3
Using builder 3.2.3
Using erubi 1.8.0
Using mini_portile2 2.4.0
Using nokogiri 1.10.3
Using rails-dom-testing 2.0.3
Using crass 1.0.4
Using loofah 2.2.3
Using rails-html-sanitizer 1.0.4
Using actionview 5.2.3
Using rack 2.0.7
Using rack-test 1.1.0
Using actionpack 5.2.3
Using nio4r 2.3.1
Using websocket-extensions 0.1.4
Using websocket-driver 0.7.1
Using actioncable 5.2.3
Using globalid 0.4.2
Using activejob 5.2.3
Using mini_mime 1.0.1
Using mail 2.7.1
Using actionmailer 5.2.3
Using activemodel 5.2.3
Using arel 9.0.0
Using activerecord 5.2.3
Using mimemagic 0.3.3
Using marcel 0.3.3
Using activestorage 5.2.3
Using public_suffix 3.1.1
Using addressable 2.6.0
Using io-like 0.3.0
Using archive-zip 0.12.0
Using bindex 0.7.0
Using msgpack 1.3.0
Using bootsnap 1.4.4
Using bundler 2.0.1
Using byebug 11.0.1
Using regexp_parser 1.5.1
Using xpath 3.2.0
Using capybara 3.25.0
Using childprocess 1.0.1
Using chromedriver-helper 2.1.1
Using coffee-script-source 1.12.2
Using execjs 2.7.0
Using coffee-script 2.4.1
Using method_source 0.9.2
Using thor 0.20.3
Using railties 5.2.3
Using coffee-rails 4.2.2
Using ffi 1.11.1
Using jbuilder 2.9.1
Using rb-fsevent 0.10.3
Using rb-inotify 0.10.0
Using ruby_dep 1.5.0
Using listen 3.1.5
Using puma 3.12.1
Using sprockets 3.7.2
Using sprockets-rails 3.2.1
Using rails 5.2.3
Using rubyzip 1.2.3
Using sass-listen 4.0.0
Using sass 3.7.4
Using tilt 2.0.9
Using sass-rails 5.0.7
Using selenium-webdriver 3.142.3
Using spring 2.1.0
Using spring-watcher-listen 2.0.1
Using sqlite3 1.4.1
Using turbolinks-source 5.2.0
Using turbolinks 5.2.0
Using uglifier 4.1.20
Using web-console 3.7.0
=end


ruby '2.5.3'


gem 'rails',                         '5.2.3'
gem 'puma',                          '3.12.3'
gem 'sass-rails',                    '5.0.7'
gem 'uglifier',                      '4.1.20'
gem 'coffee-rails',                  '4.2.2'
gem 'turbolinks',                    '5.2.0'
gem 'jbuilder',                      '2.9.1'
gem 'bootsnap',                      '1.4.4', require: false

group :development, :test do
  gem 'sqlite3',                      '1.4.1'
  gem 'byebug',                       '11.0.1',platforms: [:mri, :mingw, :x64_mingw]
end

group :development do
  gem 'web-console',                  '3.7.0'
  gem 'listen',                       '3.1.5'
  gem 'spring',                       '2.1.0'
  gem 'spring-watcher-listen',        '2.0.1'
end

group :production do
  gem 'pg',                            '1.1.4'
end 

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]
