require 'rubygems'
require 'rake'

begin
  require 'jeweler'
  Jeweler::Tasks.new do |gem|
    gem.name = "iphone-style-checkboxes"
    gem.summary = %Q{Compass plugin for the iPhone-style checkboxes}
    gem.email = "tdreyno@gmail.com"
    gem.homepage = "http://github.com/tdreyno/compass-iphone-style-checkboxes"
    gem.authors = ["Thomas Reynolds"]
    gem.add_dependency "compass", ">= 0.10"
    # gem.add_development_dependency "thoughtbot-shoulda", ">= 0"
    # gem is a Gem::Specification... see http://www.rubygems.org/read/chapter/20 for additional settings
  end
  Jeweler::GemcutterTasks.new
rescue LoadError
  puts "Jeweler (or a dependency) not available. Install it with: gem install jeweler"
end

task :test => :check_dependencies

task :default => :test
