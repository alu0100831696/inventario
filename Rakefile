require "bundler/gem_tasks"
require "rspec/core/rake_task"

RSpec::Core::RakeTask.new(:spec)

task :default => :spec

desc "run rspec code" 
    task :spec do
        sh "rspec -I. spec/inventario_spec.rb"
    end
