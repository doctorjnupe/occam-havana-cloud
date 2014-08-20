require 'securerandom'
require 'yaml'
require 'rspec/core/rake_task'
require 'erb'

Dir.glob('tasks/*.rake').each {|r| import r }

task :default => :spec

desc "Run rspec tests"
RSpec::Core::RakeTask.new do |t|
  t.pattern = ['spec/*_spec.rb']
end
