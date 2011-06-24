# Add your own tasks in files placed in lib/tasks ending in .rake,
# for example lib/tasks/capistrano.rake, and they will automatically be available to Rake.

#include Rake::DSL if defined?(Rake::DSL) this shit doesnt work either
require File.expand_path('../config/application', __FILE__)

#require 'rake/dsl_definition' - this piece of shit line didnt solve shit either.

require 'rake'

#removing the block of code right below. it didnt solve the Rakefile issue
#class Rails::Application 
#  include Rake::DSL 
#end 

DemoAppUbuntu::Application.load_tasks



