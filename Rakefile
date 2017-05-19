require 'date'
task :default => [:server]

desc 'Build the Jekyll site for local previewing'
task :server do
  system "jekyll serve --watch"
end

task :serve => :server

task :post do
  d = DateTime.now
  filename = d.strftime("%Y-%m-%d") + "-title.markdown"
  sh "cp _templates/yyyy-mm-dd-title.markdown _posts/#{filename}"
end