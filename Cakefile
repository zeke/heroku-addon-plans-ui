fs     = require 'fs'
{spawn, exec} = require 'child_process'
request = require 'request'

task 'watch', 'Automatically recompile coffee, sass, and haml to JavaScript', ->
  coffee = spawn 'coffee', ['-cw', '-o', 'lib', 'src']
  coffee.stdout.on 'data', (data) -> console.log data.toString().trim()
