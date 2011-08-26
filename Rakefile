require 'rake'

begin
    require 'jeweler'
    files = ["Rakefile", "README.md"]
    files << Dir["lib/**/*"]

    Jeweler::Tasks.new do |s|
        s.name = "rcov_plugin"
        s.authors       = ["Alan Johnson", "Luca Invernizzi"]
        s.email         = ["alan@commondream.net", "invernizzi.l@gmail.com"]
        s.homepage      = "http://github.com/invernizzi/rcov_plugin"
        s.summary       = "The easiest way to measure coverage for your Rails project"
        s.description   = "rcov_plugin adds the rake tasks that you need to measure coverage in your Rails project"
        s.require_paths = ["lib"]
        s.files         = files.flatten
        s.add_dependency('rails', ">= 3.0.0.beta2")
        s.add_dependency('rcov', '>= 0.9.6')
        s.required_rubygems_version = ">= 1.3.6"
    end
    Jeweler::GemcutterTasks.new
rescue LoadError
    puts "Jeweler not available. Install it with: gem install jeweler"
end

