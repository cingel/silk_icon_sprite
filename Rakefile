require 'rake'
require 'rake/testtask'

task :default => :test

Rake::TestTask.new("test") do |t|
  t.libs << 'test'
  t.pattern = 'test/**/*_test.rb'
  t.ruby_opts << '-rubygems'
  t.warning = true
  t.verbose = true
end

