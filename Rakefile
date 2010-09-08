require 'rubygems'
$:.unshift(File.dirname(__FILE__) + "/lib")
require 'yelp'

begin
  require 'jeweler'
  Jeweler::Tasks.new do |gem|
    gem.name = "jonnii-yelp"
    gem.summary = "An object-oriented interface to the Yelp Developer API."
    gem.add_dependency "json", ">= 1.1.1"
    
    gem.description = %q{
The yelp rubygem provides a Ruby object-oriented interface to the Yelp 
REST API described in detail at:

http://www.yelp.com/developers/getting_started}
  
    gem.email = "shaper@fatgoose.com"
    gem.homepage = "http://rubyforge.org/projects/yelp"
    gem.authors = ["Josh Nichols"]
  end
rescue LoadError
  puts "Jeweler not available. Install it with: gem install jeweler"
end