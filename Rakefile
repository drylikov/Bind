
$:.unshift 'lib'
require 'bind'
require 'rubygems'
require 'rake'
require 'echoe'

Echoe.new "bind", Bind::VERSION do |p|
  p.author = "Denis Rylikov"
  p.email = "denis.rylikov@protonmail.com"
  p.summary = "bind actions to filesystem events"
  p.url = "http://github.com/drylikov/bind"
  p.runtime_dependencies = []
  p.runtime_dependencies << 'commander >=4.0.0'
end

Dir['tasks/**/*.rake'].sort.each { |lib| load lib }