require 'bundler'
Bundler::GemHelper.install_tasks

desc "Run the specs"
task :spec do
  exec "rspec spec/can_opener_spec.rb"
end

task :default => [:spec]
