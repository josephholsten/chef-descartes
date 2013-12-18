#!/usr/bin/env rake

require 'foodcritic'

task :default => [:foodcritic]

 
FoodCritic::Rake::LintTask.new do
  options = {
    fail_tags: ['any']
  }
end
