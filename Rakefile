require 'bundler'
Bundler::GemHelper.install_tasks


require 'rake/testtask'
Rake::TestTask.new(:test) do |t|
  t.libs << 'test'
  t.test_files = FileList['test/*\.rb']
  t.verbose = true
end
	