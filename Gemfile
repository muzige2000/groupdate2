source "https://rubygems.org"

# Specify your gem's dependencies in groupdate.gemspec
gemspec

if defined?(JRUBY_VERSION)
  gem "activerecord-jdbcpostgresql-adapter", git: "https://github.com/jruby/activerecord-jdbc-adapter.git", platforms: :jruby
  gem "activerecord-jdbcmysql-adapter", git: "https://github.com/jruby/activerecord-jdbc-adapter.git", platforms: :jruby
  gem "activerecord-jdbcsqlite3-adapter", git: "https://github.com/jruby/activerecord-jdbc-adapter.git", platforms: :jruby
else
  gem "ruby-prof", require: false
end
