guard 'rake', :task => 'lint' do
  watch(%r{^manifests/.*$})
  watch(%r{^templates/.*$})
  watch(%r{^files/.*$})
end

guard 'rake', :task => 'spec' do
  watch(%r{^spec/(classes|defines)/.+_spec\.rb$})
  watch('spec/spec_helper.rb')
  watch(%r{^lib/.*$})
  watch(%r{^manifests/.*$})
  watch(%r{^templates/.*$})
  watch(%r{^files/.*$})
end