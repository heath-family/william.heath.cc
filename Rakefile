
task 'new' do
  require 'time'
  date = Time.now.strftime('%Y-%m-%d')
  header = <<-HEADER
---
layout: post
title:  "Cute pictures!"
date:   #{Time.now.strftime('%Y-%m-%d %H:%M:%S')}
categories: jekyll update
---
  HEADER
  filename = "src/_posts/#{date}-cute-for-#{date}.markdown"
  File.open(filename, 'w') {|f| f.write(header) }
end
