# A sample Guardfile
# More info at https://github.com/guard/guard#readme

guard 'coffeescript', :input => 'js', :output => 'js'

guard 'coffeescript', :input => 'spec/coffeescripts', :output => 'spec/javascripts'

guard 'jasmine', :jasmine_url => 'http://localhost:8888/' do
  watch(%r{spec/javascripts/.+Spec\.coffee$}) { "spec/javascripts" }
  watch(%r{js/(.+)\.coffee$}) { "spec/javascripts" }
end