source ENV['GEM_SOURCE'] || "http://ec2-52-55-30-243.compute-1.amazonaws.com:9292/"

gemspec

if facterversion = ENV['FACTER_GEM_VERSION']
  gem 'facter', facterversion, :require => false
else
  gem 'facter', [">= 2.4.0", "< 4"], :require => false
end
