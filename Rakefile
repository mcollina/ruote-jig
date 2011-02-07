begin
  require 'jeweler'
  Jeweler::Tasks.new do |gemspec|
    gemspec.name = "ruote-jig"
    gemspec.summary = "Ruote participant using rufus-jig"
    gemspec.description = "A ruote 2.0 participant implementation using rufus-jig to notify HTTP interfaces (mostly JSON-aware) about workitems."
    gemspec.email = "torsten.schoenebaum@planquadrat-software.de"
    gemspec.homepage = "http://github.com/tosch/ruote-jig"
    gemspec.authors = ["Torsten Schonebaum"]
    gemspec.add_dependency('ruote', '>= 2.0.0')
    gemspec.add_dependency('rufus-jig', '>= 0.1.2')
    gemspec.rdoc_options << '--line-numbers' << '--main' << 'README.rdoc'
  end
  Jeweler::GemcutterTasks.new
rescue LoadError
  puts "Jeweler not available. Install it with: sudo gem install jeweler"
end
